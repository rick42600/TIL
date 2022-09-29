# CSS 기본 선택자

## 전체 선택자(universal selector)

- 페이지에 있는 모든 요소를 대상으로 스타일을 적용할 때 사용
- 웹 브라우저의 기본 스타일을 초기화 할때 자주 사용
- 기본형

```css
* {
  속성: 값;
}
```

- css 초기 세팅
- 이렇게 하고 css 시작

```css
* {
  margin: 0; /* 브라우저 기본 마진 리셋 */
  padding: 0; /* 브라우저 기본 패딩 리셋 */
  box-sizing: border-box; /* 테두리까지 포함해서 박스 모델 너비로 계산 */
}
```

## 타입 선택자(type selector)

- 페이지에서 특정 태그를 사용한 모든 요소에 적용할 스타일 저의
- 태그 선택자(tag selector) 라고도 함
- 기본형(h2에 모두 같은 스타일 적용)

```css
h2 {
  ...;
}
```

## class 선택자

- 요소에 이름 붙일 때 `class="..."` 형태로 사용
- css 에서 사용할 때는 마침표. 다음에 클래스 이름 지정
- 클래스 선택자를 사용한 스타일을 클래스 스타일 이라고 한다
- 한 문서에서 여러 번 사용할 수 있음
- 하나의 요소에 클래스 스타일 2개 이상 사용 가능
- 기본형

```html
<span class="classname">내용</span>
```

```css
.classname {
  color: black;
}
```

## id 선택자

- 요소 이름을 붙일 때는 `id="..."` 형태로 사용
- css에서 사용 할때는 # 다음에 id 이름 지정
- 문서 안에서 한번 만 사용 가능
- id를 사용하는 이유가 다른 요소들과 구별하기 위한 것이기 때문에 id는 한번만 사용해야 한다
- 기본형

```html
<div id="container">...</div>
```

```css
#container {
  width: 500px;
  padding: 20px;
  ...;
}
```

## class 선택자와 id 선택자

- 공통점
  - 요소의 특정 부분에 이름을 줕인 후 그 이름을 사용해 스타일 적용
  - class를 사용하거나 id를 사용해서 이름을 붙임
  - 웹 문서에서 원하는 부분에만 스타일을 적용할 수 있음
- 다른 점
  - class 스타일은 문서 안에서 여러 번 사용 가능, id 스타일은 한번 만 사용
  - 디자인을 위한 스타일은 주로 class스타일을 사용, id스타일은 JavaScript에서 웹 요소를 구분하는 용도로 많이 사용
  - 하나의 웹 요소에 두 개 이상의 스타일을 사용할 수 있음

## 선택자를 묶어서 사용하기

- 같은 스타일을 사용하는 선택자를 한꺼번에 정의
- , 로 구분해 여러 선택자를 나열
- 기본형

```css
h1,
h2,
p {
  color: red;
  margin: 20px;
  ...;
}
```

## 스타일의 우선 순위(priority)

- css = Cascading Style Sheet
- Cascading : 스타일 시트에서 스타일은 위에서 아래로, 계단식으로 적용된다는 뜻
  <img src="../image/csspriority" alt="csspri img">
- css 안에서 우선순위
  <img src="../image/csspriority2" alt="csspri img2">
