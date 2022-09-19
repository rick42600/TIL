## 내부 스타일 시트
 - 문서안에 스타일시트를 함께 포함

 - 내부스타일시트는<head>와</head> 사이에 넣어야함

 - <style> 태그와</style> 사이에 사용할 스타일 작성

 - 문서안에 사용하기때문에 현재 문서에만 적용됨 → 사이트의 전체문서에서 공통으로 사용하는스타일은 ‘외부스타일시트＇로,→현재페이지에만 따로 사용하는스타일이 있다면
 ‘내부스타일시트＇로
 
 ```css
 <style>
  p {                /*p태그에 적용*/
  font-size:20px;
  color:brown;
  }
  .accent {          /*accent클래스 에 적용*/ 
  color:red;
  font-weight:bold;
  }
</style>

css에서 주석은 : /*주석내용*/
```

### VS Code 주석 단축키
 - 줄 전체를 주석처리 : Windows : ctrl + / , Mac : Command + /
 - 일부분만 주석처리 : Windows : Shift + Alt + A , Mac : Shift + Option +A

## 외부 스타일 시트
 - 웹 문서 밖에 별도의 스타일 시트 파일을 만듦. 파일 확장자는 css
 - <link> 태그를 사용해 연결할 외부 스타일 시트 지정
 - 스타일으 한번 만 정의하고 사이트 안의 다른문서에도 적용
 - 기본형 : ```<link rel="stylesheet" href="css/파일이름.css">```

### Link 태그
 - 웹 문서에 외부 파일을 연결하기 위한 태그
 - rel 속성 : 연결하는 파일의 유형 (참고자료 : [https://developer.mozilla.org/ko/docs/Web/HTML/Link_types](https://developer.mozilla.org/ko/docs/Web/HTML/Link_types))
 - href 속성 연결할 파일의 경로
 - ex) 
 - ```<link rel="stylesheet" href="style.css"> ```     :  style.css 라는 stylesheet 유형의 파일 연결
 - ```<link rel= "icon" href="favicon.ico">```       :  favicon.ico 라는 icon 유형의 파일 연결
   
       
