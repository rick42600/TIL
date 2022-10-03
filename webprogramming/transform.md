## transform

- 특정 요소의 크기나 모양이 바뀌는 것
- 예) 웹 요소를 이동시키는 병형 함수는 translate( )
- 예) 웹 요소를 x축으로 50px, y축으로 100px 이동하는 클래스 선택자 .photo
  - .photo{transform:translate(50px,100px);}
- 2차원 변형
  - 수평이나 수직으로 웹 요소 변형
  - x축으로 오른쪽으로 갈 수록, y축은 아래로 갈 수록 값이 커짐
  - 크기나 각도만 지정하면 됨
  - 2차원 좌표 사용  
    <img src="../image/2dimension.png" alt="2차원 변형함수">
- 3차원 변형
  - x축과 y축에 원근감 추가
  - z축은 앞뒤로 이동, 보는 사람 쪽으로 다가올 수록 값이 커짐  
    <img src="../image/3dimension.png" alt="3차원 변형함수">

## translate

- 이동할 거리를 지정하면 해당 요소를 이동시킨다
- 방향에 따라 사용하는 함수가 달라진다  
  <img src="../image/translate.png" alt="translate img">
- transform:translate(tx, ty) - x축 방향으로 tx만큼, y축 방향으로 ty만큼 이동
- tx와 ty 두 가지 값을 사용하지만 ty 값이 주어지지 않으면 0으로 간주
- transform:translate3d(tx, ty, tz) - x축 방향으로 tx만큼, y축 방향으로 ty만큼,z축 방향(앞뒤)으로 tz만큼 이동
- transform:translateX(tx) - x축 방향으로 tx만큼 이동
- transform:translateY(ty) - y축 방향으로 ty만큼 이동
- transform:translateZ(tz) - z축 방향으로 tz만큼 이동

## scale

- 지정한 크기만큼의 요소를 확대/축소  
  <img src="../image/scale.png" alt="scale img">
- transform:scale(sx, sy) - x축 방향으로 sx만큼, y축 방향으로 sy만큼 확대, sy 값이 주어지지 않는다면 sx 값과 같다고 간주.
  - 예) scale(2.0) = scale(2) = scale(2, 2) : 요소를 두 배로 확대.
- transform:scale3d(sx, sy, sz) - x축 방향으로 sx만큼, y축 방향으로 sy만큼, z축 방향으로 sz만큼 확대.
- transform:scaleX(sx) – x축 방향으로 sx만큼 확대.
- transform:scaleY(sy) - y축 방향으로 sy만큼 확대.
- transform:scaleZ(sz) -z축 방향으로 sz만큼 확대.
