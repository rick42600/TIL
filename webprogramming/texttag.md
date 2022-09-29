## 글자 굵게 표시

    ```html
    <p>보통글씨 <b>굵은글씨</b></p>

    ```

## 이텔릭체 표시

- 강조, 인용, 생각, 저작물 표시 사용시
- 세가지 방법
  ```html
  <p>
    <em>하나</em>
    <i>둘</i>
    <cite>셋</cite>
  </p>
  ```

## 형광펜 효과

    ```html
    <p>
        <mark>형광펜효과</mark>
    </p>
    ```

## 특수문자

- 예시)
  ```html
  <p>&bigstar</p>
  ```

W3C에서 제공하는 특수문자 엔티티 코드 주소 : [https://html.spec.whatwg.org/multipage/named-characters.html](https://html.spec.whatwg.org/multipage/named-characters.html)

## color 속성

- 글자색 지정
- 부모 요소의 색상을 물려 받음
  - `<body>` 태그 스타일에서 글자색을 지정하면 문서에 있는 모든 글자에 적용됨
  - 기본형
  ```css
  body {
    color: red;
  }
  ```

## font-family 속성

- 웹 문서에서 사용할 글꼴 지정
- `<body>` 태그를 비롯해 `<p>` 태그나 `<h1>` 태그 처럼 텍스트를 사용하는 요소들에서 사용
- font-family 에서 지정한 글꼴은 **<u>사용자 시스템</u>**에 설치되어 있어야 의도한대로 표시된다
- 사용자 시스템에 글꼴이 없다면 브라우저 기본 글꼴로 표시된다
  - 주로 사용하는 방법
    - MAC 이나 Windows에 있는 기본 글꼴 사용
    - 필요한 폰트를 직접 웹 서버에 올려놓고, 접속하는 사용자가 다운받도록 한다
    - 폰트를 제공하는 사이트에서 필요한 폰트를 링크 해둔다
    - 글꼴을 지정할때 여러 개의 글꼴을 함께 지정한다
    - 1번 글꼴이 없으면 2, 3 순으로 사용한다
    - 기본형
      ```css
      body {
        font-family: "맑은 고딕", 돋움, 굴림; /* 맑은 고딕 처럼 2개이상의 단어글꼴은 "" 로 묶어줘야한다*/
      }
      ```

## font-size 속성

- 브라우저의 기본 스타일에서 글자의 기본적인 크기가 정해져 있음
- 브라우저의 기본 글자 크기는 1em = 16px
  - `<p>` 를 사용한 텍스트 단락의 크기
- h1 텍스트의 기본 크기는 2em(32px)
- h2 텍스트의 기본 크기는 1.5em(24px)
- 키워드를 사용해 글자 크기 지정하기
  - xx-small < x-small < small < medium(기본) < large < x-large < xx-large
  ```css
  .accent {
    font-size: large;
  }
  ```
- 백분율을 사용해 글자 크기 지정하기
  - **부모 요소**의 크기를 기준으로 % 인지 지정
  ```css
  .accent {
    font-size: 150%;
  }
  ```
- px 단위
  - px단위를 사용하면 폰트 크기가 고정된다
  - 단, px로 지정하면 PC 와 모바일의 픽셀 크기가 다르기 때문에 모바일 상에는 아주 작은 글씨로 표시된다
    - 이유는 모바일 기기는 PC보다 많은 픽셀로 구성되어 있기 때문이다. 뷰포트로 해결가능
- em 단위
  - **부모 요소**의 크기를 기준으로 상대적인 크기 지정
  - **부모 요소**에서 지정한 폰트의 대문자 M 의 너비를 1em으로 지정한다(1em=16px)
  - 글자크기(em) = 글자크기(px)/16px
- rem 단위

  - body 스타일에서 기본 크기를 지정하고 그것을 기준으로 글자 크기 지정

- font-style 속성
  - 글자를 이탤릭체로 표기
  - normal : 기본
  - italic : 이탤릭체
  - oblique : 이탤릭체
  - 기본형
  ```css
  .accent {
    font-style: italic;
  }
  ```
- font-weight 속성
  - 글자 굵기 지정
  - 키워드 사용
    - normal, bold(굵게), bolder(더 굵게), lighter(얇게)...
  - 값 사용
    - 사용값 : 100,200...900
    - 400 이 normal, 700 이 bold
