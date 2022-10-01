## css gradation

- Gradation : 두가지 이상의 색상이 자연스럽게 연결되어 표시 되는것

  - 선형 그라데이션 : linear-gradient()
  - 원형 그라데이션 : radial-gradient()

- linear-gradient()

  - 색상이 수직, 수평 또는 대각선 방향으로 일정하게 변하는것
  - 색상이 어느 방향으로 바뀌는지, 어떤 색상으로 바뀌는지 지정해줘야 한다
  - 기본형

  ```css
  h1 {
    background: linear-gradient(to right bottom, black, red);
  }
  ```

  - 왼쪽 위에서 오른쪽 아래(right bottom)로
  - black에서 red로 색상이 변한다

- linear-gradient 각도

  - graidtion이 끝나는 각도 지정
  - 값은 deg로 표기
  - css에서 각도는 맨 윗부분이 0deg 이고 시계 방향으로 회전하면서 증가
  - 방향을 사용할 때보다 좀 더 세밀하게 지정할 수 있다

- linear-gradient 색상 중지점
- 그라데이션에 여러 색상이 사용될 때 색상이 바뀌는 지점
- 색상만 지정할 수도 있고 색상과 함꼐 중지점의 위치도 함께 지정할 수도 있다
- 색상을 지정할 때 rgba()함수를 사용해서 불투명도를 함께 지정할 수 있다  
  <img src="../image/gradend.png" alt="색상 중지점">
