## img 태그
- `<img src="이미지 파일 경로" alt="대체용 텍스트">`

## img 태그의 src 속성
- 웹문서 파일의 위치를 기준으로 이미지 경로 지정

- HTML과 이미지파일이 같은폴더에 있다면src속성에파일이름만적음 예) `<img src="apple.jpg">`

- 하위 폴더에 이미지 파일이 있다면 하위폴더까지 같이 적음 예) `<img src="images/apple.jpg">`

## img 태그의 alt 속성
- 이미지를 설명하는 대체 텍스트

- 화면 낭독기에서 이미지 대신 대체텍스트를 읽어줌. (웹접근성)

- 이미지를 표시할 수 없는 상황일때 대체텍스트 표시

- 텍스트자체를 이미지로 만들었을 경우 대체텍스트안에 이미지파일의 내용을 그대로 넣어주어야함.

- 불릿이미지나 작은아이콘처럼 대체텍스트가 필요하지않은 경우에는 alt="" 처럼지정

## img 태그의 width, height 속성
- 이미지 크기를 조정하는 방법
- `width="50%"` : 이미지 크기 값을 퍼센트(%)로 지정하면 현재 웹 브라우저 창의 너비와 높이를 기준으로 이미지 크기를 결정합니다.
- `width="50"`  : 이미지 크리 값을 픽셀(px)로 지정하면 이미지의 너비나 높이를 해당 픽셀 크기만큼 표시합니다 
- 예시
```html
<img src="images/apple.jpg" alt="사과 사진” width=“50%”>
```
# 참고
- 무료 이미지 사이트
- unsplash : [https://unsplash.com/](https://unsplash.com/)
- Pexels : [https://www.pexels.com/ko-kr/](https://www.pexels.com/ko-kr/)
- pixabay : [https://pixabay.com/](https://pixabay.com/)
