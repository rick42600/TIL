## 하이퍼링크 삽입하기 `<a>` 태그
- 다른 문서, 혹은 다른 사이트로 바로 연결해 주는 기능
- 절대 경로, 상대 경로 가 있음
- 메뉴 뿐만 아니라 원하는 곳에 링크를 만들 수 있다.
- 기본형

```html
<a href="링크할 주소">텍스트 또는 이미지</a>
````

## 텍스트 링크
```html
<p><a href="https://google.com">google</a></p>
```
- 주의 할점 : `<p>`태그 사용시 `<p>` 태그로 `<a>` 태그를 감싸야 한다. 반대로 x
```html
  * 잘못된 방식 : <a href="https://google.com"><p>google</p></a>
  * 잘된 방식 : <p><a href="https://google.com">google</a></p>
```

## 이미지 링크
```html
<a href="https://google.com"><img src="images/logo.png" alt="구글 로고"></a>
```

- `target="_blank"` 로 지정하면 연결된 문서가 새 탭으로 열림
예시)
```html
<a href="https://google.com" target="_blank"><img src="images/logo.png" alt="구글 로고"></a>
```

## 한 페이지 안에서 점프하기 - 앵커
- 앵커를 사용하려면 우선 이동하고 싶은 위치마다 id 속성을 이용해 앵커를 만든다
- `<a>` 태그의 href 속성을 사용해 링크한다. 단, 앵커 이름 앞에 #을 붙여서 앵커를 표시한다
```html
<태그 id="앵커이름"> 내용</태그>
<a href="#앵커이름">텍스트 또는 이미지</a>
```
예시)
```html
  <a id="top"></a>
  <object data="medias/product.pdf" type="application/pdf" width="900" height="800" ></object><!--pdf삽입-->
  <a href="#top">[맨위로]</a>
```
