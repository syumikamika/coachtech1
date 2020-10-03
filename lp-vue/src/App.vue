<template>
  <div id="app">
    <CommonHeader></CommonHeader>
    <main>
    <div id="eyecatch">
      <p>機械ではできない仕事を</p>
    </div>

    <div class="news">
      <div class="content">
        <p>2019/01/01</p>
        <div class="content3">
        <p>ニュースタイトルがここには入ります。3月の決算報告書</p>
      </div>
      </div>
      <div class="content2">news</div>
    </div>

    <div id="about" class="wrap">
      <div class="flex around">
        <div class="about-center">
          <h1>お客様のために進化する成長企業であり続ける</h1>
          <p>
            顧客主導型サービスを提供する企業として、お客様の会社経営に必要なサービスと情報を提供し続ける企業支援会社を目指します。企業が現在直面している「勝ち残るため」の戦略を提供できる会社として、ホームページをはじめ、各種マーケティングをご提供いたします。
          </p>
          <a class="about-center-link"
            href="飛ばしたいページ">ミッション詳細</a>
        </div>
        <div class="about-center2">
          <img src="./assets/mission-img.jpg" alt="">
        </div>
      </div>
    </div>

    <div id="business">
      <h2 class="section-title">service</h2>
      <div class="flex around business-wrap">
       <div class="business-cat">
          <h3>web制作事業</h3>
          <p>コーチングのミッション</p>
          <p>
            ユーザーが求める物を分析し、ユーザビリティを備えた最適なサイトを提供。建設業から美容、ブライダル、飲食店まで多種多様な業種の制作実績があります
          </p>
          <a class="business-cat-link"
            href="飛ばしたいページ">サービス詳細</a>
        </div>
        <div class="business-cat2">
          <h3>web制作事業</h3>
          <p>コーチングのミッション</p>
          <p>
            ユーザーが求める物を分析し、ユーザビリティを備えた最適なサイトを提供。建設業から美容、ブライダル、飲食店まで多種多様な業種の制作実績があります
          </p>
          <a class="business-cat2-link"
            href="飛ばしたいページ">サービス詳細</a>
        </div>
        <div class="business-about">
          <img src="./assets/service2.jpg" alt="red">
        </div>
        <div class="business-about2">
          <img src="./assets/service1.jpg" alt="red">
        </div>
      </div>
    </div>

    <div class="parent">
      <div class="child">
        <h1>company</h1>
        <p>会社概要</p>
      </div>
      <div class="child2">
        <h1>recruit</h1>
        <p>採用情報</p>
      </div>
    </div>

    <div id="quesion">
      <h1>FAQ</h1>
      <p>良くある質問</p>
    </div>

    <div class="text-image">
      <img src="./assets/contact-bg.jpg" alt="">
      <h2>contact</h2>
      <h3>お問い合わせ</h3>
      <h1>お気軽にお問い合わせください。</h1>
      <p>
        資料請求・お問い合わせなどなんでも気軽にお問い合わせください。お仕事のご連絡もお問い合わせページに飛んでいただいて、入力フォームにご記入お願いいたします。
      </p>
      <a class="text-image-link"
        href="#">お問い合わせへ</a>
    </div>
  </main>
  <main id="main">
    <div class="flex between">
      <h1 class="main-logo">estra inc.</h1>
      <nav class="main-nav">
        <ul>
          <li><a href="飛ばしたいページ">home</a></li>
          <li><a href="飛ばしたいページ">about</a></li>
          <li><a href="飛ばしたいページ">service</a></li>
          <li><a href="飛ばしたいページ">works</a></li>
          <li><a href="飛ばしたいページ">price</a></li>
          <li><a href="飛ばしたいページ">contact</a></li>
        </ul>
      </nav>
    </div>
  </main>
    <CommonFooter></CommonFooter>
  </div>
</template>

<script>
import CommonHeader from "./components/CommonHeader";
import CommonFooter from "./components/CommonFooter";
export default{
  components:{
    CommonHeader,
    CommonFooter
  }
};
</script>


<style>
html, body, div, span, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
abbr, address, cite, code,
del, dfn, em, img, ins, kbd, q, samp,
small, strong, sub, sup, var,
b, i,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, figcaption, figure,
footer, header, hgroup, menu, nav, section, summary,
time, mark, audio, video {
    margin:0;
    padding:0;
    border:0;
    outline:0;
    font-size:100%;
    vertical-align:baseline;
    background:transparent;
}

body {
    line-height:1;
}

article,aside,details,figcaption,figure,
footer,header,hgroup,menu,nav,section {
    display:block;
}

nav ul {
    list-style:none;
}

blockquote, q {
    quotes:none;
}

blockquote:before, blockquote:after,
q:before, q:after {
    content:'';
    content:none;
}

a {
    margin:0;
    padding:0;
    font-size:100%;
    vertical-align:baseline;
    background:transparent;
}

/* change colours to suit your needs */
ins {
    background-color:#ff9;
    color:#000;
    text-decoration:none;
}

/* change colours to suit your needs */
mark {
    background-color:#ff9;
    color:#000;
    font-style:italic;
    font-weight:bold;
}

del {
    text-decoration: line-through;
}

abbr[title], dfn[title] {
    border-bottom:1px dotted;
    cursor:help;
}

table {
    border-collapse:collapse;
    border-spacing:0;
}

/* change border colour to suit your needs */
hr {
    display:block;
    height:1px;
    border:0;  
    border-top:1px solid #cccccc;
    margin:1em 0;
    padding:0;
}

input, select {
    vertical-align:middle;
}

.section-title{
  font-size: 30px;
  font-weight:bold;
  margin:30px 0;
  text-align:center;
}

img{
  display: block;
  width: 100%;
}

.wrap{
  width: 80%;
  margin:0 auto 50px;
}

.flex{
  display: flex;
  align-items: center;
  flex-wrap: wrap;
}

.between{
  justify-content: space-between;
}

.around{
  justify-content: space-around;
}

#eyecatch {
  height: 800px;
  width: 100%;
  background: url(./assets/eyecatch.jpg) no-repeat;
  background-size: cover;
  background-position: center;
  position: relative;
}

#eyecatch p {
  position: absolute;
  top: 65%;
  left: 25%;
  transform: translate(-50%, -50%);
  font-size: 45px;
  font-style: italic;
  font-weight: bold;
  color: #ccc;
  line-height: 1;
}

.eyecatchp2 {
  color: white;
  background: black;
  height: 20px;
  position: absolute;
  top: 90%;
}

#about {
  background-color: black;
  height: 400px;
  width: auto;
}

.about-center h1,
.about-center p {
  margin-bottom: 30px;
  color: white;
  margin-left: 7cm;
  margin-right: 7.5cm;
  line-height: normal;
  position: relative;
  z-index: 2;
}

.about-center2 {
  position: absolute;
  width: 550px;
  z-index: 0;
  top: 128%;
  right: 1cm;
}

.about-center h1 {
  margin-top: 3cm;
  font-size: 30px;
  z-index: 1;
  margin-right: 1cm;
}

.about-center-link {
  color: black;
  padding: 5px 20px;
  font-size: 14px;
  text-decoration: none;
  cursor: pointer;
  transition: 0.4s ease;
  background: white;
  position: relative;
  left: 17.5%;
}

.news {
  display: flex;
  justify-content: flex-end;
}

.content {
  padding: 10px 150px;
  background: white;
  position: absolute;
  right: 3cm;
  top: 111%;
}

.content p {
  color: black;
  font-size: 14px;
  position: relative;
  right: 4cm;
  width: 500px;
}

.content3 p {
  color: black;
  font-size: 12px;
  position: relative;
  right: 3.7cm;
  
}

.content2 {
  color: white;
  padding: 20px 60px;
  background: black;
  position: absolute;
  top: 111%;
  font-size: 12px;
}

#business {
  background: lightgray;
  background-size: cover;
  margin-top: 150px;
  height: 1400px;
  width: 100%;
}

#business .section-title {
  color: black;
  padding: 10px 0;
  margin: 0;
}

.business-wrap {
  text-align: center;
}

.business-cat {
  width: 600px;
  background-color: white;
  padding: 50px 35px 30px;
  height: 200px;
  position: relative;
  left: 200px;
  top: 120px;
}

.business-cat h3 {
  margin: 20px;
  text-align: left;
}

.business-cat p {
  color: black;
  line-height: 20px;
  text-align: left;
  margin: 20px;
  font-size: 15.2px;
}

.business-cat-link {
  margin-left: 450px;
  padding: 5px 20px;
  /* 上下に5px、左右に20px */
  font-size: 14px;
  color: black;
  text-decoration: none;
  /* テキストのスタイルを消す */
  cursor: pointer;
  border: 1px black solid;
  /* 境界線を引く */
  transition: 0.4s ease;
  /* スタイルが変化する時間 */
}

.business-cat-link:hover {
  color: #fff;
  background: black;
}

.business-about {
  width: 50%;
  margin-top: -7cm;
  margin-left: 50%;
}

.business-cat2 {
  width: 600px;
  background-color: white;
  padding: 50px 35px 30px;
  height: 200px;
  position: relative;
  right: 5cm;
  top: 800px;
}

.business-cat2 p {
  color: black;
  line-height: 20px;
  text-align: left;
  margin: 20px;
  font-size: 15.2px;
}

.business-cat2 h3 {
  margin: 20px;
  text-align: left;
}

.business-cat2-link {
  margin-left: 450px;
  padding: 5px 20px;
  /* 上下に5px、左右に20px */
  font-size: 14px;
  color: black;
  text-decoration: none;
  /* テキストのスタイルを消す */
  cursor: pointer;
  border: 1px black solid;
  /* 境界線を引く */
  transition: 0.4s ease;
  /* スタイルが変化する時間 */
}

.business-cat2-link:hover {
  color: #fff;
  background: black;
}

.business-about2 {
  width: 50%;
  margin-top: 5cm;
  margin-right: 20.1cm;
}

body {
  color: white;
}

.parent {
  display: flex;
  justify-content: space-between;
}

.child {
  width: 46%;
  height: 200px;
  padding: 10px;
  margin-top: 150px;
  background: url(./assets/company.jpeg);
  background-size: cover;
  background-position: center;
  position: relative;
}

.child h1 .child2 h1 {
  color: white;
  position: absolute;
  left: 50%;
  top: 45%;
  font-size: 36px;
}

.child p .child2 p {
  color: white;
  position: absolute;
  top: 65%;
  left: 50%;
  transform: translate(-50%, -50%);
  font-size: 18px;
  font-weight: bold;
}

.child2 {
  width: 46%;
  height: 200px;
  padding: 10px;
  margin-top: 150px;
  background: url(./assets/recruit.jpg);
  position: relative;
  background-size: cover;
  background-position: center;
}

#quesion {
  height: 100px;
  margin-top: 150px;
  margin-right: 5cm;
  margin-left: 6.5cm;
  background: black;
  width: 70%;
  position: relative;
}

#quesion p {
  position: absolute;
  top: 50%;
  left: 48%;
  transform: translate(-50%, -50%);
  font-size: 15px;
  font-style: italic;
  color: white;
}

#quesion h1 {
  font-size: 25px;
  position: absolute;
  top: 40%;
  left: 3%;
}

.text-image {
  position: relative;
  width: 100%;
  margin-top: 150px;
}

.text-image img {
  width: 100%;
}

.text-image p {
  position: absolute;
  top: 55%;
  left: 10%;
  font-size: 16px;
  color: #ffffff;
}

.text-image h1 {
  color: white;
  font-size: 26px;
  position: absolute;
  top: 48%;
  left: 37%;
}

.text-image h2 {
  color: white;
  font-size: 35px;
  position: absolute;
  top: 37%;
  left: 45.5%;
}

.text-image h3 {
  color: white;
  font-size: 18px;
  position: absolute;
  top: 42%;
  left: 46.5%;
}

.text-image-link {
  color: white;
 
  padding: 15px 40px;
  /* 上下に5px、左右に20px */
  font-size: 14px;
  text-decoration: none;
  /* テキストのスタイルを消す */
  cursor: pointer;
  border: 1px white solid;
  /* 境界線を引く */
  transition: 0.4s ease;
  /* スタイルが変化する時間 */
  position: absolute;
  top: 60%;
  left: 45%;
  
}

#main {
  height: 70px;
  background: #000;
}

.main-logo {
  font-size: 20px;
  font-weight: bold;
  margin-left: 35px;
  color: #f2f2f2;
  line-height: 70px;
}

.main-nav li {
  display: inline-block;
  margin-right: 35px;
  font-size: 16px;
}

.main-nav a {
  color: #f2f2f2;
}

@media screen and (max-width: 768px) {
  #eyecatch p{
  width: 60%;
  top: 40%;
  margin-left: 25%;
  text-align: center;

}

.content2{
  margin-top: 60px;
  padding:  35px 25px;
  font-size: 16px;
  
}
.content{
  margin-top: 60px;
  padding-top: 35px;
  left: 0px; 
  height:40px;
}

.content p{
  height: 10px;
  top: -20px;
  font-size: 18px; 
  margin-left: 10px;
}

.content3 p{
  font-size: 15px;
  position: absolute;
  right: 10%;
  left: 5%;
  top: 40px;
  line-height: 25px;
  width: 250px;
}
#about{
  height: 550px;
}
.about-center h1{
  margin-top: 50px;
  font-size: 35px;
  position: relative;
  text-align: center;
  width: 100%;
  margin-left: 10px;
  text-align: left;

}

.about-center{
  width: 80%;
  height: 500px;
  
}


.about-center p{
  font-size: 17px;
  top: 10px;
  width: 95%;
  margin-top: 10px;
  position: relative;
  margin-left: 10px;
  
}

.about-center-link{
  left: 12px;
  padding: 10px 40px;
}

.about-center2{
  width: 40%;
  position: relative;
  right: -90px;
  top: 0px;
  z-index: 1;
}

#business{
  position: relative;
  margin-top: -10px;
  z-index: 0;
  height: 1150px;
}

.section-title{
  position: relative;
  top: 10px;
}

.business-about2{
  width: 10%;
  margin-right: 200px;
}

.business-about img {
  width: 330px;
  position: relative;
  left: -165px;
  top: 260px;
}


.business-cat {
  position: absolute;
  left: 22px;
  width: 261px;
  margin-top: 165px;
}

.business-cat h3{
  position: relative;
  top: -40px;
  left: -35px;
  color: black;
}

.business-cat p{
  position: relative;
  top: -35px;
  left: -35px;
  width: 110%;
}

.business-cat-link{
  margin-left: 0px;
  position: relative;
  left: 60px;
  top: -20px;
  padding: 10px 40px;
}


.business-about2 img {
  position: absolute;
  left: 22.5px;
  width: 330px;
  top: 55%;
}


.business-cat2 {
  position: absolute;
  left: 22px;
  width: 261px;
}

.business-cat2 h3{
  position: relative;
  top: -30px;
  left: -35px;
  color: black  
}

.business-cat2 p{
   position: relative;
   top: -35px;
   left: -35px;
   width: 110%;
}

.business-cat2-link{
   margin-left: 0px;
   position: relative;
   left: 60px;
   top: -20px;
   padding: 10px 40px;
}

.parent{
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}

.child{
  width: 100%;
  height: 300px;
  margin-top: 40px;
}

.child2{
  width: 100%;
  height: 300px;
  margin-top: 0px;
}

.child h1,
.child2 h1{
  font-size: 50px;
  text-align: center;
  position: relative;
  top: 40%;
}

.child p,
.child2 p{
  font-size: 20px;
  text-align: center;
  position: relative;
  top: 45%;
}

#quesion{
  width: 100%;
  margin-left: 0px;
  margin-top: 40px;
  height: 130px;
}

#quesion h1{
  font-size: 40px;
  position: absolute;
  margin-left: 40px;
  top: 35%;
}

#quesion p{
  font-size: 20px;
  left: 210px;
}

.text-image{
  position: relative;
  margin-top: 40px;
  
}

.text-image img{
  height: 600px;
}

.text-image h1{
  width: 80%;
  position: absolute;
  top: 25%;
  font-size: 40px;
  left: 40px;
  text-align: center;
}

.text-image h2{
  position: absolute;
  top: 40px;
  left: 115px;
}

.text-image h3{
  position: absolute;
  top: 90px;
  left: 125px;
}

.text-image p{
  position: absolute;
  top: 55%;
  font-size: 16px;
  text-align: center;
  line-height: 25px;
  left: 30px;
  width: 80%;
}

.text-image-link{
  width: 30%;
  left: 110px;
  top: 85%;
  padding: 10px 20px;
  text-align: center;
}

.main-logo{
  position: relative;
  left: 100px;
  top: 5px;
}
}
</style>