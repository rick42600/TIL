## 순서 없는 목록(unordered list)
- ul : unordered list
- li : list item
```html
<ul>
    <li> 
      <b>목록1: </b> 첫번째 목록
    </li>
    <li> 
      <b>목록2: </b>두번쨰 목록
    </li>
    <li>
      <b>마지막</b>
    </li>
</ul>
```

## 순서 있는 목록(ordered list)
- ol : ordered list
- ol start="숫자" : 정해진 숫자부터 목록 시작
- ol start="A" : a, A, l, i 등 다양한 목록 타입
```html
  <ol>
    <li> 
      <b>목록1: </b> 첫번째 목록
    </li>
    <li> 
      <b>목록2: </b>두번쨰 목록
    </li>
    <li>
      <b>마지막</b>
    </li>
  </ol>
```
```html
  <ol start="5">
    <li> 
      <b>목록1: </b> 첫번째 목록
    </li>
    <li> 
      <b>목록2: </b>두번쨰 목록
    </li>
    <li>
      <b>마지막</b>
    </li>
  </ol>
```

## 설명 목록(description list)
- dl : description list (목록)
- dt : desription title (목록 제목)
- dd : description data (목록 내용)
```html
  <dl>
    <dt>이름(제목) 1</dt>
    <dd>값(설명) 1</dd>
    <dt>이름(제목) 2</dt>
    <dd>값(설명) 2</dd>
  </dl>

```
