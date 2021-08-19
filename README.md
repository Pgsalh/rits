# rits
<!DOCTYPE html>

<html>

  <head>

    <meta http-equiv="content-type" content="text/html; charset=utf-8" />

     <link rel="stylesheet" href="Css/main.css" media="all" />

     <meta name="viewport" content="width=device-width, initial-scale=1.0">

     <script src="https://kit.fontawesome.com/d8707a5a7f.js" crossorigin="anonymous"></script>

<link rel="preconnect" href="https://fonts.googleapis.com">

<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

<link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@1,600&display=swap" rel="stylesheet">

    <title>Salah zenkar</title>

  </head>
<STYLE>
  .donkey {

  width:400px;

  height:auto;

}

.donkey {

  width:30px;

  height:auto;

}

body {

  margin:0px;

  padding: 0px;

  font-family:'Poppins', sans-serif;

}

*{

box-sizing:border-box;

	scroll-behavior: smooth;

}

ul {

  list-style: none;

}

a {

  text-decoration: none;

}

#main {

  width:100%;

  height:100vh;

  position: relative;

}

nav {

  display:flex;

  justify-content: space-between;

  align-items: center;

  position: fixed;

  box-shadow: 5px 10px 30px rgba(0,0,0,0.02);

  left:1px;

  top:0px;

  width:100%;

  z-index: 1;

  background-color: #FFFFFF;

}

nav ul {

  display:flex;

}

nav ul li a {

  height:40px;

  line-height:43px;

  margin:3px;

  padding: 0px 22px;

  display:flex;

  font-size:10px;

  text-transform:uppercase;

  font-weight: 500;

  color:#585b5b;

	letter-spacing: 1px;

}

.help {

  color:#39bfbd;

	font-weight: 500;

	font-size: 0.9rem;

	border-bottom: 2px solid #40c6c4;

}

nav ul li a:hover {

background-color: #2adabc;

	color:#FFFFFF;

	box-shadow: 5px 10px 30px rgba(64,198,196,0.3);

	transition: all ease 0.2s;

}

.model img{

	width:100%;

	height: 100%;

	object-fit: contain;

}

.model{

	width:500px;

	height: 500px;

}

.content{

	width:90%;

	display: flex;

	justify-content: space-around;

	align-items: center;

	position: absolute;

	left: 50%;

	top: 30%;

	transform: translate(-50%,-50%);

}

.main-text{

	width:500px;

}

.main-text h1{

	font-size: 3.5rem;

	color:#1c3548;

	margin:0px 0px 10px 0px;

	line-height: 60px;

}

.main-text p{

	color:#747474;

}

#portfolio{

	width:190px;

	height: 44px;

	display: flex;

	justify-content: center;

	align-items: center;

	color:#FFFFFF;

	background-color: #1db096;

	position: absolute;

  right:2%;

  bottom: 20%;

	border-radius: 20px;

	box-shadow: 4px 10px 30px rgba(24,139,119,0.2);

}

.portfolio:hover{

	background-color: #23cdaf;

	transition: all ease 0.2s;

}

#skills{

	display: flex;

	justify-content: space-around;

	align-items: center;

	width:90%;

	margin:auto auto 50px auto;

	position: absolute;

	bottom:0%;

	top:60%;

}

.skill-text{

	width:400px;

}

.skill-img{

	width:600px;

	height: 600px;

}

.skill-img img{

	width:100%;

	height: 100%;

}

.skill-heading span{

	color:#36b7b5;

	font-weight: 500;

	text-transform: uppercase;

	letter-spacing: 1px;

	font-size: 1rem;

	padding: 0px 0px 0px 15px;

}

.skill-heading h2{

	color: #1c3548;

	font-size: 2.3rem;

	margin:9px;

	font-weight: 400;

	letter-spacing: 1px;

}

.s-box-container{

	margin-top: 30px;

}

.skill-box{

	display: flex;

	margin: 25px 0px;

}

.s-box-icon{

	margin-right:12px;

}

.s-box-icon i{

	width:40px;

	height: 40px;

	border-radius: 50%;

	display: flex;

	justify-content: center;

	align-items: center;

	background-color: #f0f0f0;

	font-size: 1.1rem;

}

.s-box-text strong{

	color:#1c3548;

	margin: 0px;

	font-size: 0.9rem;

	font-weight: 600;

}

.s-box-text p{

	color:#747474;

	font-size: 0.9rem;

}

.fa-html5{

	color:#e06061;

	margin: 0px 0px 0px 10px;

}

.fa-css3-alt{

	color:#416cdf;

	margin: 0px 0px 0px 10px;

}

.fa-js-square{

	color:#f98231;

	margin: 0px 0px 0px 10px;

}

#contact {

  display: flex;

  flex-direction: column;

  justify-content: center;

  align-items: center;

  margin:40px 0px;

}

#contact h3{

  font-size:1.5rem;

  margin:10px;

  position: absolute;

  left:2%;

  top:90%;

}

#contact img{

  height: 200px;

  position: absolute;

  left:9%;

  top:99%;

}

.contact-input{

	width:400px;

	height:50px;

	background-color:#FFFFFF;

	display:flex;

	justify-content: center;

	position: absolute;

	left:2%;

	top:110%;

	border-radius: 50px;

	box-shadow: 2px 2px 30px rgba(0,0,0,0.15);

}

.contact-input input{

	width:100%;

	background-color: transparent;

	border:none;

	outline: none;

	text-align: center;

	color:#242425;

}

.contact-input a{

	width:200px;

	height:35px;

	background-color:#1db096;

	color:#FFFFFF;

	display: flex;

	font-size: 0.9rem;

	justify-content: center;

	align-items: center;

	margin: auto 10px;

	border-radius: 20px;

	font-weight: 500;

}

footer{

  position: absolute;

  left:9%;

  top:150%;

	display:flex;

	justify-content: space-around;

	border-top: 1px solid rgba(232,232,232,0.5);

	background-color:#FFFFFF;

}

footer p{

	margin:15px 0px;

	color:#5f5f5f;

	font-size: 0.9rem;

}
  </STYLE>
  <body>

    

    

    <section class="main">

      <nav>

    <img class="donkey" src="img/Donkeypng.png"/>

  <ul class="menu">

    <li><a href="#menu">Home </a></li>

    <li><a href="#skills">skills</a></li>

    <li><a href="#contact">Contact</a></li>

  </ul>

  <a href="https://t.me/Pgsalh" class="help">

    Need help?</a>

  </nav>

  </section>

  

  <div class="content">

    

    <div class="model">

      <img src="img/dnk.png"/>

    </div>

    

    <div class="main-text">

     <h1>Hi, i'm Salah zenkar</h1>

     <p> <H6 style="font-size:9px;">This is my portfolio, in this website you will show all my projects and skills. 

     </H6>

     </p>

    </div>

    

    <a href="#portfolio" id="portfolio">See my portfolio</a>

  </div>

    

	<section id="skills">

		<div class="skill-text">

		

		<div class="skill-heading">

		<span>My Skills</span>

		<h2>My experience</h2>

		</div>

		<div class="s-box-container">

		

		<div class="skill-box">

	

		<div class="s-box-icon">

  <i class="fab fa-html5"></i>

		</div>

		

		<div class="s-box-text">

		<strong>Hyper Text Markup Language(HTML)</strong>

		<p>I have 6 month experience in html.</p>

		</div>

		</div>

		

		<div class="skill-box">

		

		<div class="s-box-icon">

			<i class="fab fa-css3-alt"></i>

		</div>

		

		<div class="s-box-text">

		<strong>Cascading Style Sheets(CSS)</strong>

		<p>I have 2 month experience in CSS.</p>

		</div>

		</div>

		

		<div class="skill-box">

		</div>

		</div>

	</div>

	</section>

	

	<section id="contact">

	  

	  <img src="img/contact.svg" />

	  

	  <h3>Get best projects in 48 hours only.</h3>

	  

	  <div id="contact-input">

	  

	  <input type="email" placeholder="Example@gmail.com"/>

	  <a href="#">Continue</a>

	  </div>

	</section>

	<footer>

	  <p>Salah zenkar, Ltd Consumer Website</p>

	  <p>© Copyright - 2021 | All Rights Reserved</p>

	</footer>

  </body>

</html>
