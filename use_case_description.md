## Use case description : 회원 가입

| Actor Action | System Response |
| --- | --- |
| 1. 비회원 사용자가 ‘회원 가입’ 버튼을 클릭한다. | 2. 시스템은 회원 가입 입력 폼을 화면에 출력한다. |
| 3. 비회원 사용자가 ID, 비밀번호, 전화번호를 입력한다. |  |
| 4. 비회원 사용자가 ‘가입 완료’ 버튼을 클릭한다. | 5. 시스템은 가입 완료 메시지를 출력한다. |

---

## Use case description : 로그인

| Actor Action | System Response |
| --- | --- |
| 1. 사용자가 ID와 비밀번호를 입력한다. |  |
| 2. 사용자가 ‘로그인’ 버튼을 클릭한다. | 3. 시스템은 인증에 성공하면 메인 화면으로 이동시킨다. |

## Alternative Courses

- **입력한 ID 또는 비밀번호가 일치하지 않는 경우**
  → 시스템은 "로그인 실패" 메시지를 출력하고, 로그인 화면을 유지한다.
  → 사용자는 ID 및 비밀번호를 수정하여 다시 시도할 수 있다.

---

## Use case description : 로그아웃

| Actor Action | System Response |
| --- | --- |
| 1. 사용자가 ‘로그아웃’ 버튼을 클릭한다. | 2. 시스템은 로그인 화면으로 이동시킨다. |

---

## Use case description : 자전거 등록

| Actor Action | System Response |
| --- | --- |
| 1. 관리자가 자전거 ID, 자전거 제품명을 입력한다. |  |
| 2. 관리자가 ‘등록’ 버튼을 클릭한다. | 3. 시스템은 자전거 등록 완료 메시지를 출력한다. |

---

## Use case description : 자전거 대여

| Actor Action | System Response |
| --- | --- |
| 1. 회원이 특정 자전거의 '대여' 버튼을 클릭한다. | 2. 시스템은 자전거 대여 완료 메시지를 출력한다. |

---

## Use case description : 자전거 대여 정보 조회

| Actor Action | System Response |
| --- | --- |
| 1. 사용자가 ‘자전거 대여 정보 조회’ 메뉴를 선택한다. | 2. 시스템은 사용자가 대여 중인 자전거 정보 리스트를 화면에 출력하며, 각 항목에 대해 자전거 ID, 자전거 제품명을 함께 출력한다. |

---