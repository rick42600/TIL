```html
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>3조</title>
  <link rel="stylesheet" href="css/style.css">
  <link rel="stylesheet" href="css/membership.css">
  <link rel="stylesheet" href="css/login.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css" integrity="sha512-xh6O/CkQoPOWDdYTDqeRdPCVd1SpvCA9XXcUnZS2FmJNp1coAFzvtCN9BmamE+4aHK8yyUHUSCcJHgXloTyT2A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
  <!-- banner -->
  <script src="https://code.jquery.com/jquery-1.12.4.js"></script>
  <div id="banner">
    <div class="navbar">
      <div class="logo">
        <h1><a href="#"><img id="logo" src="images/logo1.png"></a></h1>
      </div>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#browsing" >영화</a></li>
        <li><a href="#series">시리즈</a></li>
        <li><a id="membershipBtn">멤버쉽</a></li>
        <li><a id="loginBtn">로그인</a></li>
        <li><a href="#faq">FAQ</a></li>
      </ul>
    </div>

    <div class="heading">
        <h2>매주 수요일 저녁 새로운 에피소드 공개</h2>
        <h3>큰 자기 X 아기자기 자기들 마음대로 떠나는 사람 여행!<br>
          자기님의,자기님에 의한,자기님을 위한<br>
          어쩌면 당신의 이야기...! 일상 속 선물 같은 순간,<br>
          “You Quiz?” <br></h3>
        <p>큰 자기 X 아기자기 자기들 마음대로 떠나는 사람 여행!<br>
          자기님의,자기님에 의한,자기님을 위한<br>
          길 위에서 만나는 우리네 이웃의 삶, 저마다 써 내려간인생 드라마의 주연들,<br>
          어쩌면 당신의 이야기...! 일상 속 선물 같은 순간,<br>
          “You Quiz?” <br>
        </p>
        <div class="buttons">
          <button><span></span>▶ 재생</button>
          <button><span></span>ⓘ 상세정보</button>
        </div>
      </div>
    </div>
  </div>

  <!-- 영화 -->
  <div id="browsing">
    <div class="title-text">
      <h2>Movie</h2>
      <hr>
      <p>Team3 Plus가 <br>추천 하는 영화</p>
      </div>
    <div class="Movies">
      <div class="movie">
        <div class="movie-img">
          <img src="images/movie-1.png">
        </div>
        <div class="movie-desc">
          <h3>모비우스</h3>
          <button class="more">더 보기 <i class="fa-solid fa-angle-right"></i></button>
        </div>
      </div>
      <div class="movie">
        <div class="movie-img">
          <img src="images/movie-2.png">
        </div>
        <div class="movie-desc">
          <h3>선과 악의 학교</h3>
          <button class="more">더 보기 <i class="fa-solid fa-angle-right"></i></button>
        </div>
      </div>
      <div class="movie">
        <div class="movie-img">
          <img src="images/movie-3.png">
        </div>
        <div class="movie-desc">
          <h3>엽문 4</h3>
          <button class="more">더 보기 <i class="fa-solid fa-angle-right"></i></button>
        </div>
      </div>
    </div>
  </div>



  <!-- 시리즈 -->
  <div id="series">
    <div class="title-text">
        <h2>Series</h2>
        <hr>
        <p>최근 개봉작 소개</p>
    </div>
    <div class="slide">
        <div class="images">
            <img src="images/slide_1.jpeg" align="center" float=left;>
            <div class="over"></div>
            <div class="slide-desc">
                <h3>신과 함께 </h3>
                <hr>
                <p>
                판타지, 드라마, 액션, 어드벤처
                </p>
            </div>
        </div>

        <div class="images">
            <img src="images/slide_0.jpeg" align="center" float=left;>
            <div class="over"></div>
            <div class="slide-desc">
                <h3>마녀2</h3>
                <hr>
                <p>
                SF, 스릴러, 액션, 다크 판타지, 슈퍼히어로
                </p>
            </div>
        </div>

        <div class="images">
            <img src="images/slide_2.jpeg" align="center" float=left;>
            <div class="over"></div>
            <div class="slide-desc">
                <h3>범죄도시2</h3>
                <hr>
                <p>
                범죄, 액션, 블랙 코미디, 스릴러, 느와르, 형사
                </p>
            </div>
        </div>

        <div class="images">
            <img src="images/slide_3.jpg" align="center" float=left;>
            <div class="over"></div>
            <div class="slide-desc">
                <h3>킹덤2</h3>
                <hr>
                <p>
                다크 판타지, 미스터리, 좀비 아포칼립스, 스릴러, 사극, 액션, 드라마
                </p>
            </div>
        </div>
    </div>
  </div>



  <!-- 멤버쉽 -->
  <div id="membership" class="modal">
    <!-- Modal Content -->
    <div class="modal-content">
        <span class="close">
            <i class="fa-regular fa-circle-xmark"></i>
        </span>
        <div class="container">
            <div class="list-title">멤버십 & 결제 정보</div>
            <ul class="list-group" id="user_info">
                <li class="list-group-item" id="user_email">Email</li>
                <li class="list-group-item" id="user_password">Password</li>
                <li class="list-group-item" id="user_phone_number">Phone Number</li>
            </ul>
            <hr>
            <ul class="list-group" id="payment">
                <li class="list-group-item" id="user_credit_card">신용카드</li>
            </ul>
            <hr>
            <div class="list-title">결제 상세 정보</div>
            <ul class="list-group" id="payment_info">
                <li class="list-group-item" id="payment_cancel">
                    <button>멤버십 해지</button>
                </li>
            </ul>
            <hr style="border-style: none;">
            <div class="list-title">멤버십 상세 정보</div>
            <ul class="list-group" id="membership_info">
                <li class="list-group-item" id="user_membership_info">프리미엄 <span>ULTRA HD</span></li>
            </ul>
        </div>
    </div>
</div>


<!-- 로그인 -->
<div id="login" class="login_modal">
    <!-- login Modal Content -->
    <div class="login_modal-content">
        <span class="close">
            <i class="fa-regular fa-circle-xmark"></i>
        </span>
        <div class="container">
            <div class="list-title">로그인</div>
            <ul class="list-group">
                <li>
                    <label for="email" id="user_info">이메일</label>
                    <input type="text" id="email" placeholder="Email">
                </li>
                <li>
                    <label for="password">비밀번호</label>
                    <input type="password" id="password" placeholder="Password">
                </li>
                <li>
                    <label for="phone_number">전화번호</label>
                    <input type="number" id="phone_number" placeholder="XXX-XXXX-XXXX">
                </li>
            </ul>
            <hr>
            <ul class="list-group" id="login_payment">
                <li class="list-group-item">신용카드</li>
                <input id="credit_card" type="text" placeholder="DONT-USEA-REAL-NMBR"></label>
            </ul>
            <hr>
            <div class="list-title"></div>
            <ul class="list-group">
                <li class="list-group-item" id="login_btn">
                    <button id="save">로 그 인</button>
                </li>
            </ul>
        </div>
    </div>
</div>

<!--faq-->
  <div id="faq">
    <div class="container">
      <div class="faq-text">
        <h3>자주 묻는 질문</h3>
      <button class="coll-btn">팀3플러스 비밀번호 변경하는 방법</button>
      <div class="panel">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Facere provident magnam sint doloremque minus expedita nobis molestiae assumenda. Ea, fugit.</p>
      </div>
      <button class="coll-btn">팀3플러스에 로그인 하려는데 가입하라는 메시지가 표시됨</button>
      <div class="panel">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Molestias reprehenderit est ut distinctio voluptatem?</p>
      </div>
      <button class="coll-btn">'사용 중인 디바이스와 팀3플러스 앱 버전이 호환되지 않습니다.'라는 메시지가 표시됨</button>
      <div class="panel">
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Qui eius natus nihil culpa doloremque nisi dolorum hic. Repudiandae id eveniet accusamus necessitatibus laboriosam atque praesentium!</p>
      </div>
      <button class="coll-btn">프로필을 생성, 변경 또는 삭제하는 방법</button>
      <div class="panel">
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Qui eius natus nihil culpa doloremque nisi dolorum hic. Repudiandae id eveniet accusamus necessitatibus laboriosam atque praesentium!</p>
      </div>
      <button class="coll-btn">콘텐츠를 저장하여 오프라인에서 시청하는 방법</button>
      <div class="panel">
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Qui eius natus nihil culpa doloremque nisi dolorum hic. Repudiandae id eveniet accusamus necessitatibus laboriosam atque praesentium!</p>
      </div>
      <button class="coll-btn">내 계정에서 새로운 로그인이 발생했다는 이메일을 수신했습니다</button>
      <div class="panel">
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Qui eius natus nihil culpa doloremque nisi dolorum hic. Repudiandae id eveniet accusamus necessitatibus laboriosam atque praesentium!</p>
      </div>
      <button class="coll-btn">내 계정에서 새로운 로그인이 발생했다는 이메일을 수신했습니다</button>
      <div class="panel">
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Qui eius natus nihil culpa doloremque nisi dolorum hic. Repudiandae id eveniet accusamus necessitatibus laboriosam atque praesentium!</p>
      </div>
  </div>


  <footer>
    <div class="contact">
      <p>
        <i class="fa-solid fa-location-dot"></i> XX시 XX동 1234번지 
      </p>
      <p>
        <i class="fa-solid fa-phone"></i> 02-1234-5678 
      </p>
      <div class="sns">
        <i class="fa-brands fa-youtube"></i>
        <i class="fa-brands fa-facebook"></i>
        <i class="fa-brands fa-instagram"></i>
        <i class="fa-brands fa-twitter"></i>
      </div>
    </div>
    <div class="copyright">
      <p>Copyright Lorem ipsum dolor sit.</p>
    </div>    
  </footer>
  <div class="fixed">
    <a href="#banner">
      <i class="fa-solid fa-arrow-up"></i>
    </a>
  </div>
  <script src="js/index.js"></script>
</body>
</html>
```
