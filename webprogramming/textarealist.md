## 텍스트 영역과 목록

- 여러 줄의 텍스트 입력
- 게시판 글 입력 양식 등 많은 내용을 입력할 때 사용
- 기본형

  ```html
  <textarea[속성]>내용</textarea>
  ```

  - cols : 텍스트 영역의 가로 너비를 문자 단위로 지정합니다
  - rows : 텍스트 영역의 세로 길이를 줄 단위로 지정합니다. 지정한 숫자보다 줄 개수가 많아지면 그크롤 막대가 생깁니다

- 드롭다운 목록

  - 여러 옵션 중에서 선택
  - 공간을 최소한으로 사용하면서 여러 옵션 포시가능
  - 기본형

  ```html
  <select>
    <option value="값">내용1</option>
    <option value="값">내용2</option>
    ...
  </select>
  ```

  - value : 해당 항목을 선택할 때 서버로 넘겨줄 값을 지정합니다
  - selected : 드롭다운 메뉴를 삽입할 때 기본적으로 선택해서 보여 줄 항목을 지정합니다
