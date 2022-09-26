## 폼 삽입하기
- `<form>` 태그
  * 폼 전체를 감싸는 기본 태그
  * `<form>,</form>` 사이에 여러 폼 요소 삽입(텍스트필드, 체크박스,버튼 등 역할마다 다른소스 사용)
- 기본형
```html
<form[속성="속성값"]> 여러 폼 요소 </form>
```

## 폼에서 구역 나누기
- `<fieldset>` 태그
  * 폼 요소를 그룹으로 묶는 태그
  * 필수적인 것 아님, 폼 안의 내용을 그룹으로 묶으려고 할 때 사용
  * 기본형 
   ```html
  <fieldset[속성="속성값"]> ~~ </fieldset>
   ```

- `<legend>` 태그
  * 그룹으로 묶는 구역에 제목을 붙이는 태그 제목을 생략할 수도 있다
  * 기본형
  ```html
  <fieldset>
    <legend> 그룹 이름 </legend>
  </fieldset>
  ```
  
  - 참고 : 필드셋 테두리 없애기 
  ```html
  <style>
    fieldset{border : none;}
    legend{display : none;}
  </style>
  ```
## `<input>` 태그
  - 한 줄짜리 사용자 입력을 받는 태그 & 버튼을 만드는 태그
  - type 속성에 따라 폼 요소가 달라짐
  - type 속성 값에 따라 함께 사용할 수 있는 속성도 달라짐
  ```html
  <input type="유형" [속성="값"]>
  ```
  <img src="../image/input_1.png" alt="input이미지1">
