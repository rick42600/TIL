```css
/*login.css*/
@import url('https://fonts.googleapis.com/css2?family=Nanum+Gothic&display=swap');

/* The login Modal (background) */
.login_modal {
    display: none;
    position: fixed;
    z-index: 1;
    padding-top: 100px;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    overflow: auto;
    background-color: rgba(0,0,0,0.4);
}

/* login Modal Content */
.login_modal-content {
    background-color: #fefefe;
    margin: auto;
    padding: 20px;
    border: 1px solid #888;
    width: 30%;
    height: 80%;
    color: #386fab;
    border-radius: 20px;
}

.login_modal-content .container {
    padding: 20px;
    margin-top: 40px;
}

.login_modal-content .list-title {
    padding-top: 11px;
    padding-bottom: 11px;
    font-size: 18px;
    color: #888;
}
#payment_cancel button {
    font-size: 15px;
}
#save {
    font-size: 15px;
}
.login_modal-content ul {
    list-style: none;
    line-height: 4;
}

.login_modal-content ul#login_payment {
    line-height: 3;
}

.login_modal-content hr {
    margin-top: 0.5rem;
    margin-bottom: 0.5rem;
    color: #386fab;
    border-style: solid;
    background-color: #386fab;
}

.login_modal-content li#login_btn {
    text-align: center;
}

.login_modal-content li#login_btn button {
    width: 90%;
    background-color: #386fab;
    color: #ffff;
    border-radius: 30px;
    cursor: pointer;
}

.login_modal-content label#user_info {
    padding-right: 15px;
}

.login_modal-content input {
    height: 38px;
    width: 82%;
}

.login_modal-content input#credit_card {
    width: 100%;
}

/* The Close Button */
.close {
    color: #aaaaaa;
    float: right;
    font-size: 28px;
    font-weight: bold;
}

.close:hover, .close:focus {
    color: #386fab;
    cursor: pointer;
}

/* 미디어 쿼리 */
@media screen and (max-width: 1324px) {

    .login_modal-content ul {
        line-height: 5;
        font-size: 12px;
    }

    .login_modal-content label#user_info {
        padding-right: 11px;
    }
}

@media screen and (max-width: 1240px) {
    .login_modal-content ul {
        line-height: 5;
        font-size: 11px;
    }
}

@media screen and (max-width: 1200px) {
    
    .login_modal-content {
        width: 41%;
    }

    .login_modal-content ul {
        line-height: 5;
        font-size: 14px;
    }

    .login_modal-content label#user_info {
        padding-right: 12px;
    }
}

@media screen and (max-width: 1028px){
    .login_modal-content ul {
        line-height: 5;
        font-size: 13px;
    }
}

@media screen and (max-width: 968px) {
    .login_modal-content ul {
        line-height: 5;
        font-size: 12px;
    }
}

@media screen and (max-width: 920px) {
    
    .login_modal-content {
        width: 50%;
    }

    .login_modal-content ul {
        line-height: 5;
    }
}

@media screen and (max-width: 880px) {
    
    .login_modal-content ul {
        line-height: 5;
    }
}

@media screen and (max-width: 879px) {
    
    .login_modal-content {
        width: 50%;
    }

    .login_modal-content ul {
        font-size: 12px;
        line-height: 5;
    }

    .login_modal-content label#user_info {
        padding-right: 11px;
    }
}

@media screen and (max-width: 768px) {
    
    .login_modal-content {
        height: 80%;
    }

    .login_modal-content ul {
        font-size: 12px;
        line-height: 5;
    }
    
    .login_modal-content label#user_info {
        padding-right: 11px;
    }
}

@media screen and (max-width: 744px) {
    
    .login_modal-content ul {
    font-size: 11px;
    line-height: 5;
    }
}

@media screen and (max-width: 704px) {
    .login_modal-content ul {
        font-size: 10px;
        line-height: 5;
    }
}

@media screen and (max-width: 691px) {
    
    .login_modal-content {
        width: 50%;
    }

    .login_modal-content ul {
        line-height: 3;
    }

    .login_modal-content input {
        width: 100%;
    }
}

@media screen and (max-width: 425px) {
    
    .login_modal-content {
        width: 80%;
    }

    .login_modal-content ul {
        font-size: 11px;
    }
}
```
```css
/*membership.css*/
@import url('https://fonts.googleapis.com/css2?family=Nanum+Gothic&display=swap');

/* The Modal (background) */
.modal {
    display: none;
    position: fixed;
    z-index: 1;
    padding-top: 100px;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    overflow: auto;
    background-color: rgba(0,0,0,0.4);
}

/* Modal Content */
.modal-content {
    background-color: #fefefe;
    margin: auto;
    padding: 20px;
    border: 1px solid #888;
    width: 30%;
    height: 80%;
    color: #191970;
    border-radius: 20px;
}

.modal-content .container {
    padding: 20px;
    margin-top: 40px;
}

.modal-content .list-title {
    padding-top: 11px;
    padding-bottom: 11px;
    font-size: 18px;
    color: #888;
}

.modal-content ul {
    list-style: none;
    line-height: 3;
}

.modal-content hr {
    margin-top: 0.5rem;
    margin-bottom: 0.5rem;
    color: #386fab;
    border-style: solid;
    background-color: #386fab;
}

.modal-content li#payment_cancel {
    text-align: center;
}

.modal-content li#payment_cancel button {
    width: 90%;
    background-color: #386fab;
    color: #ffff;
    border-radius: 30px;
    cursor: pointer;
}

.modal-content li#user_membership_info span {
    border: 1.5px solid;
}

/* The Close Button */
.close {
    color: #aaaaaa;
    float: right;
    font-size: 28px;
    font-weight: bold;
}

.close:hover, .close:focus {
    color: #386fab;
    cursor: pointer;
}

/* 미디어 쿼리 */
@media screen and (max-width: 1200px) {
    
    .modal-content {
        width: 41%;
    }

    .modal-content ul {
        line-height: 3;
        font-size: 12px;
    }
}

@media screen and (max-width: 920px) {
    
    .modal-content {
        width: 50%;
    }
}

@media screen and (max-width: 880px) {
    
    .modal-content ul {
        line-height: 3;
    }
}

@media screen and (max-width: 768px) {
    
    .modal-content {
        height: 80%;
    }

    .modal-content ul {
        font-size: 12px;
        line-height: 3;
    }

    .modal-content label#user_info {
        padding-right: 11px;
    }
}

@media screen and (max-width: 425px) {
    
    .modal-content {
        width: 80%;
    }

    .modal-content ul {
        font-size: 11px;
    }
}
```
```css
/*style.css*/
@import url('https://fonts.googleapis.com/css2?family=Black+Han+Sans&display=swap');
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth;
}
a {
  text-decoration: none;
  color: #222;
}
body {
  font-family: 'Black Han Sans', sans-serif;
  background-color: #7fb9f7;
}

#banner {
  width: 100%;
  height: 100vh;
  background-image: linear-gradient(rgba(0, 0, 0, 0.1), rgba(0, 0, 0, 0.5)), url(../images/bg3.jpg);
  background-position: center;
  background-size: cover;
}
.navbar {
  width: 100%;
  margin: auto;
  padding: 16px 35px;
  display: flex;
  justify-content: space-between;
  align-items:center;
  transition: all 1s;
  position:fixed;
  z-index: 2;
}
.logo {
  width: 100px;
  cursor: pointer;
  color: white;
}
.logo img {
  width: 200%;
}
.navbar ul {
  list-style: none;
}
.navbar ul li {  
  display: inline-block;
  margin: 0 20px;
  position: relative;
}
.navbar ul li a {
  text-decoration: none;
  font-size: 20px;
  font-weight: bold;
  color:rgb(0, 0, 0);
  cursor: pointer;
}

.navbar ul li a::after {
  content: "";
  display: block;
  width: 0;
  height: 2px;
  background: #ffff;
  position: absolute;
  left:0;
  bottom: -10px;
  transition: 0.3s;
}
.navbar ul li a:hover::after {
  width: 100%;
}
.heading {
  width: 100%;
  position: absolute;
  top: 50%;
  transform: translateY(15%) translateX(15%);
  text-align: left;
  color: #fff;
}
.heading h2 {
  letter-spacing: 5px;
  font-size: 30px;
  text-shadow: 1px 1px 2px #222;
}
.heading p {
  margin: 40px auto;
  font-weight: bold;
  font-size: 20px;
  line-height: 36px;
}

button{
  width: 200px;
  padding: 15px 0;
  text-align: center;
  margin: 20px 10px;
  font-weight: bold;
  font-size: 28px;
  border-radius: 25px;
  border: 1px solid rgb(211, 211, 211);
  background: transparent;
  color: #fff;
  cursor: pointer;
  position: relative;
  overflow: hidden;
}
button > span {
  background: #7fb9f7;
  height: 100%;
  width: 0;
  border-radius: 25px;
  position: absolute;
  left: 0;
  bottom: 0;
  z-index: -1;
  transition: 0.5s;
}
button:hover span {
  width: 120%;
}
button:hover {
  border: none;

}
@media screen and (min-width: 770px) {
  .heading h3{ display: none; }
}
@media screen and (max-width: 769px) {
  
  .navbar {
    width: 100%;
  }
  .logo {
    width: 60px;
  }
  .navbar ul{
    width: 50%;
  }
  .navbar ul li {  
    margin: 0 6px;
  }
  .navbar ul li a {
    font-size: 15px;
  }
  .heading h2 {
    transform: translateY(-50%) translateX(-10%);
    font-family: 'Nanum Gothic', sans-serif;
    font-size: 20px;
  }
  .heading h3 {
    line-height: 2;
    font-family: 'Nanum Gothic', sans-serif;
    font-size: 17px;
    }
  .heading p {
    display: none;
  }
  .buttons {
    display: flex;
    flex-direction: row;
    align-items: left;
    transform: translateY(30%) translateX(-10%);
  }
  button{
    line-height: 1;
    font-size: 20px;
  }
}

/* 영화 보기 */
* 영화 보기 */
#browsing {
  width: 100%;
}
.title-text {
  width: 22%;
  padding-top: 180px;
  margin:30px auto;
  text-align: center;
  
}
.title-text h2 {
  font-size: 70px;
  color: #fff;
  margin-bottom: 20px;
  padding: 10px;
  background-color: #386fab;
  border-radius: 20px;
}
.title-text hr {
  width: 45%;
  margin: 10px auto;
}
.title-text p {
  color: #ffff;
  font-size: 32px;
}
.Movies {
  width: 100%;
  margin: auto;
  padding: 20px;
  display: flex;
}
.movie {
  margin: 40px auto;
  padding: 15px;
  background-color: #386fab;
}
.movie-img {
  flex-basis: 50%;
  height: 667px;
  width: 422px;
  width: 100%;
  
}
.movie-img img{
  height: 100%;
  width: 100%;
  border-radius: 20px;
}
.movie-desc {
  flex-basis: 50%;
  padding-left: 20px;
  padding-right: 20px;
  line-height: 55px; 
}

.movie-desc h3 {
  font-size: 25px;
  letter-spacing: 1px;
  margin-bottom: 20px;
  color: #ffff
}
.movie-desc p {
  font-size: 16px;
  line-height: 1.8;
  margin-bottom: 20px;
}
.movie-desc .more {
  padding: auto;
  margin: auto;
  background-color:#fff;
  border: none;
  border-radius: 5px;
  color: #7fb9f7;
}
@media screen and (max-width: 769px) {
  .title-text h2 {
    font-size: 32px;
  }
  .Movies {
    width: 100%;
  }
  .movie-img {
    flex-basis: 100%;
  }
  .movie-img img {
    width: 100%;
  }
  .movie-desc {
    flex-basis: 100%;
    margin-top: 30px;
    padding-left: 10px;
    padding-right: 10px;
  }
  .movie-desc h3 {
    font-size: 22px;
    letter-spacing: 1px;
    margin-bottom: 20px;
  }
  .movie-desc .more {
    font-size: 14px;
  }
}

button:hover span {
  width: 120%;
}
button:hover {
  border: none;
}

/* 시리즈 */
#series {
  width: 100%;
  padding-top: 100px;
  text-align: center;
}

.series-text h2 {
  font-size: 50px;
  margin-bottom: 20px;
  color: #666;
}

.series-text p {
  font-size: 50px;
  color: #000;
  /* color: rgb(255, 255, 255); */
  margin-bottom: 20px;
}

.slide {
  margin: 40px auto;
  padding-top: 20px;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around; 
  align-items:flex-start;
  /* position:relative; */
}

.images {
  flex-basis: 24%;
  margin: auto;
  text-align: center;
  border-radius: 7px;
  margin-bottom: 20px;
  position: relative;
}

.images img {
  width: 100%;
  border-radius: 7px;
}

.over {
  width: 100%;
  height: 100%;
  position: absolute;
  top: 0;
  border-radius: 7px;
  cursor: pointer;
  background: linear-gradient(rgba(86, 172, 233, 0.6), rgb(151, 154, 210));
  opacity: 0;
  transition: 1s;
}

.slide-desc {
  color: #fff;
  width: 80%;
  position:absolute;
  top: 0%;
  left: 50%;
  transform: translateX(-50%);
  font-size:15px;
  opacity: 0;
  transition: 1s;  
}

.slide-desc h3 {
  font-size: 40px;
}

.slide-desc hr {
  width: 60%;
  margin: 15px auto;
}

.slide-desc p {
  font-size: 20px;
}

.images:hover .over {
  opacity: 1;
}

.images:hover .slide-desc {
  opacity: 1;
  top: 40%;
}

@media screen and (max-width: 769px) {
  .images {
      flex-basis: 42%;
  }

  .slide-desc h3 {
      font-size: 20px;
  }

  .slide-desc p {
      font-size: 14px;
  }
}


/*faq*/
#faq {
  padding-top: 5em;
  width: 100%;
  background-color: #7fb9f7;
}
.faq-text {
  width: 90%;
  margin: 80px auto 0 auto;
  text-align: center;
}
.faq-text h3 {
  font-family: 'Nanum Gothic', sans-serif;
  font-size: 46px;
  color: #fff;
  margin-bottom: 20px;
}
.faq-text p{
  margin-left: 1em;
  color: #010d9c;
  border: 1px solid #eee;
  padding: 1em;
  font-size: 20px;
}
.container {  
  width: 80%;
  margin: 20px auto;
}
.coll-btn {
  background-color: #386fab;
  color: #fff;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  font-size: 22px;
  text-align: left;
  border: none;
  outline: none;
}
.coll-btn:hover,
.active {
  background-color: rgb(140, 129, 204);
  color: rgb(90 0 167);
}
.coll-btn::after {
  content: "\002b";
  /* content: "\2b";
  font: var(--fa-font-solid); */
  font-size: 13px;
  float: right;
  margin-left: 5px;
}
.active::after {
  content: "\2212";
  /* content: "\f00d";
  font: var(--fa-font-solid); */
}
.panel {
  width: auto;
  text-align: left;
  overflow: hidden;
  display: none;
}
@media screen and (max-width: 769px) {
  .container {
    width: 80%;
  }
  .faq-text h3 {
    font-size: 40px;
  }
  .coll-btn{
    font-size: 20px;
  }
}
/* 푸터 */
footer {
  width: 80%;
  padding: 30px;  
  background-color: #7fb9f7;
  margin: 10px auto;
}
.contact{
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-around;
}
.contact p {
  font-size: 20px;
  line-height: 2;
  color:#040c72;
}
.contact i {
  color: #040c72;
  margin-right: 15px;
}
.sns {
  text-align: center;
}
.sns i {
  width: 40px;
  height: 40px;
  font-size: 20px;
  line-height: 40px;
  border: 1px solid #040c72;
  border-radius: 50%;
  color: #040c72;
  cursor: pointer;
  transition: 0.6s;
}
.sns i:hover {
  background-color: #386fab;
  color: #fff;  
}
.copyright {
  width:100%;
  margin-top: 40px;
  color: rgb(0 0 0 / 50%);
  text-align: center;
  font-style: italic;
}
@media screen and (max-width: 769px) {
  footer {
    width: 100%;
  }
  .contact{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  .contact p {
    font-size: 14px;
    line-height: 2;
  }
  .sns i {
    margin-top: 20px;
  }
  .copyright {
    font-size: 14px;
  }
}
.fixed {
  position: fixed;
  right: 2%;
  bottom: 5%;
}
.fixed i {
  width: 60px;
  height: 60px;
  background-color: rgba(255, 255, 255, 0.2);
  border: 1px solid #666;
  border-radius: 5px;
  font-size: 30px;
  line-height: 60px;
  text-align: center;
}


```

