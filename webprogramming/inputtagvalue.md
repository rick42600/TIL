## `<input>`태그의 속성

- autofocus
  - 검색 사이트에 접속하면, 자동으로 검색 창에 커서가 올라가서 즉시 검색어를 입력할 수 있음
  - 로그인 화면에서는 아이디를 입력할 수 있는 필드에 커서가 올라간다
  - 폼 필드에서 무조건 autofocus 를 사용할 필요는 없다
  - 기본형
  ```html
  <input type="text" autofocus />
  ```
- placeholder
  - 이름 그대로 입력이 되기전에 위치를 잡고 있는 내용
  - 무슨 내용을 적어야 할지 일종의 힌트를 준다고 생각하면 된다
  - 기본형
  ```html
  <input type="email" autofocus placeholder="이메일 주소" />
  ```
- readonly
  - 읽기 전용 필드
  - 텍스트 필드에 내용이 표시만 되고 사용자가 입력할 수 없음
  - 읽기 전용 필드를 사용하지 않고 그냥 텍스트로 표시하기도 함
  - 기본형
  ```html
  <input type="text" readonly />읽기전용
  ```
- required
  - 필수 체크 필드
  - 필수 체크 필드는 브라우저에서 직접 체크하는 것이므로 오류 메세지 내용은 브라우저들 마다 다르다
  - html5 이후에는 type값이나 속성을 사용해서 필수 필드를 체크하거나 입력할 형식을 미리 지정하고 submit 버튼을 누르면 알아서 체크
  - 기본형
  ```html
  <input type="text" autofocus placeholder="이메일 주소" required />
  ```
