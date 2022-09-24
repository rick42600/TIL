## 새로운 이미지 삽입 방법이 필요한 이유
- 기존 `<img src="" alt="">` 방식은 웹, 모바일, 패드 등 다양한 디바이스에 각각 width, height 을 조절해줘야한다(비효율적)
- 화면 크기, 화질에 따라 적합한 이미지를 자동으로 선택하여 표시할 수 있는 방법

## 새로운 속성 srcset
- `<img src="이미지" srcset="이미지1"[,이미지2,이미지3,....]>`
- 사용할 이미지를 크기에 따라 여러개 준비하고
- 뷰포트 : pc, 스마트폰등 디바이스의 화면에서 실제 내용이 표시되는 영역
- 뷰포트 너비(w) 나 픽셀 비율(x)에 따라 이미지 지정
- 작은 이미지에서 큰 이미지 순으로 입력

- 기존 이미지 삽입방법

```html
<img src="../image/bordercollie.jpg" alt="보더콜리">
```

- srcset 속성 사용(w 너비 descriptor)
  * 화면 너비가 500px 이하면 bordercollie_small.jpg
  * 화면 너비가 1000px 이하면 bordercollie_m.jpg
  * 화면 너비가 1500px 이하면 bordercollie_large.jpg

```html
<img srcset="../image/bordercollie-small.jpg 500w,
             ../image/bordercollie-m.jpg 1000w,
             ../image/bordercollie-large.jpg 1500w"
             src="../image/bordercollie.jpg" alt="보더콜리">
```

- srcset 속성 사용(x 픽셀비율 descriptor)
  * 화면 픽셀 비율에 따라 이미지 변경
  * x값이 클 수록 고화질의 이미지 사용가능
  * 현재 브라우저 정보제공 사이트 : [https://www.mydevice.io/](https://www.mydevice.io/)

```html
<img src = "pic.png" srcset = "pic-low.png 1x, pic-high.png 2x" alt = "이미지">
```

## `<picture>,<source>` 태그
- 화면 크기에 따라 다른 이미지를 표시 하는 방법
- `<picutre>` 태그 안에 필요한 이미지와 속성 지정

```html
<picture>
 <source srcset=“이미지 파일 경로“ 속성들>
 <source srcset=“이미지 파일 경로“ 속성들>
..... 
</picture>
```

예시

```html
<picture>
  <source srcset="images/apple-large.jpg" media="(min-width:1024px)">
  <source srcset="images/apple-medium.jpg" media="(min-width:768px)">
  <source srcset="images/apple-small.jpg" media="(min-width:320px)">
  <img src="images/apple.jpg" alt="사과" style="width:100%;">
</picture>

```
