# githubtest
simple website, created using CSS and HTML
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Portfolio website</title>
	<link rel="stylesheet" type="text/CSS" href="projektas.css">
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.2/css/all.min.css" integrity="sha512-1sCRPdkRXhBV2PBLUdRb4tMg1w2YPf37qatUFeS7zlBy7jJI8Lf4VHwWfZZfpXtYSLy85pkm9GaYVYMfw5BC1A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
	<!-- Hero section start -->
	<div class="Hero">
		<nav>
			<h2 class="Logo">Portfo<span>lio</span></h2>
			<ul>
				<li><a href="#">Home</a></li>
				<li><a href="#">About me</a></li>
				<li><a href="#">Services</a></li>
				<li><a href="#">Skills</a></li>
				<li><a href="#">Conctact me</a></li>
			</ul>
			<a href="#" class="btn">Subscribe</a>
		</nav>
		<div class="Content">
		<h4>Hello, my name is</h4>
		<h1>Andrius <span>Adomaitis</span></h1>
		<h3>I'm a web developer</h3>
			<div class="newsletter">
				<form>
					<input type="email" name="email" id="mail" placeholder="Enter Your Email">
					<input type="submit" name="submit" value="Let's Start">
				</form>
			</div>
		</div>
	</div>
	<section class="about">
		<div class="main">
			<img src="img/Andrius.jpg" alt="">
			<div class="about-text">
				<h2>About me</h2>
				<h5>Developer <span>& Designer</span></h5>
				<p>Lorem, ipsum dolor, sit amet consectetur adipisicing elit. Perspiciatis exercitationem amet quaerat facilis iure voluptatem laboriosam inventore ratione ad autem molestiae ipsa, sed culpa, optio mollitia? Dolorem quam dicta ullam ipsum repellendus, debitis perferendis vel ducimus nostrum illum dolor commodi odit doloribus quidem molestiae hic quas iure nihil quo animi!</p>
				<button type="button">Let's Talk</button>
				
			</div>
		</div>
	</section>

	<!-- service section start -->
	<div class="service">
		<div class="title">
			<h2>Our services</h2>	
		</div>
		<div class="box">
			<div class="card">
				<i class="fa-solid fa-bars"></i>
				<h5>Web Development</h5>
				<div class="pra">
					<p>Lorem ipsum dolor, sit, amet consectetur adipisicing elit. Maxime neque temporibus dolore, harum magnam vero suscipit repellendus incidunt enim ea.</p>
				
					<p style="text-align: center">
						<a href="#" class="button">Read more</a>
					</p>
				</div>
			</div>

			<div class="card">
				<i class="fa-regular fa-user"></i>
				<h5>Web Development</h5>
				<div class="pra">
					<p>Lorem ipsum dolor, sit, amet consectetur adipisicing elit. Maxime neque temporibus dolore, harum magnam vero suscipit repellendus incidunt enim ea.</p>
				
					<p style="text-align: center">
						<a href="#" class="button">Read more</a>
					</p>
				</div>
			</div>

			<div class="card">
				<i class="fa-regular fa-bell"></i>
				<h5>Web Development</h5>
				<div class="pra">
					<p>Lorem ipsum dolor, sit, amet consectetur adipisicing elit. Maxime neque temporibus dolore, harum magnam vero suscipit repellendus incidunt enim ea.</p>
				
					<p style="text-align: center">
						<a href="#" class="button">Read more</a>
					</p>
				</div>
			</div>
		</div>
	</div>

	<!-- Contact me -->
	<div class="contact-me">
		<p>Let Me Get You A Beautiful Website</p>
		<a href="#" class="button-two">Hire Me</a>
	</div>
	<!-- Footer start -->
	<footer>
		<p>Andrius Adomaitis</p>
		<p>For more HTML, CSS and coding tutorial - please click on the link below to subscribe to my chanel:</p>
		<div class="social">
			<a href="#"><i class="fa-brands fa-facebook-f"></i></a>
			<a href="#"><i class="fa-brands fa-instagram"></i></a>
			<a href="#"><i class="fa-brands fa-youtube"></i></a>
		</div>
		<p class="end">Copyright by Andrius Adomaitis, 2022 &copy</p>
	</footer>
</body>
</html>

*{
	padding: 0;
	margin: 0;
	font-family: "Times New Roman", Times, serif;
	box-sizing: border-box;
}
.Hero {
	height: 100vh;
	width: 100%;
	background-image: url(img/background.jpg);
	background-size: cover;
	background-position: center;
}
nav {
	display: flex;
	align-items: center;
	justify-content: space-between;
	padding-top: 45px;
	padding-left: 8%;
	padding-right: 8%;
}
.Logo {
	color: white;
	font-size: 35px;
	letter-spacing: 1px;
	cursor: pointer;
}
span {
	color:#FF142A;
}
nav ul li {
	list-style-type: none;
	display: inline-block;
	padding: 10px 25px;
}
nav ul li a {
	color: black;
	text-decoration: none;
	font-weight: bold;
	text-transform: capitalize;
}
nav ul li a:hover {
	color:#FF142A;
	transition: .4s;
}
.btn {
	background-color: #FF142A;
	color: white;
	text-decoration: none;
	border: 2px solid transparent;
	font-weight: bold;
	padding: 10px 25px;
	border-radius: 30px;
	transition: transform .4s;
}
.btn:hover {
	transform: scale(1.2);
}
.Content {
	position: absolute;
	top: 50%;
	left: 8%;
	transform: translateY(-50%);
}
h1 {
	color:white;
	margin:20px 0px 20px;
	font-size: 75px;
}
h3 {
	color:white;
	font-size: 25px;
	margin-bottom: 50px;
}
h4 {
	color: #fcfc;
	letter-spacing: 2px;
	font-size: 20px;
}
.newsletter form {
	width: 300px;
	max-width: 100%;
	position: relative;
}
.newsletter form input:first-child {
	display:inline-block;
	width: 100%;
	padding: 14px 130px 14px 15px;
	border: 2px solid #FF142A;
	outline: none;
	border-radius: 30px;
}
.newsletter form input:last-child {
	position: absolute;
	display: inline-block;
	outline: none;
	border: none;
	padding: 10px 30px;
	border-radius:30px;
	background-color: #FF142A;
	color: white;
	box-shadow: 0px 0px 5px #000, 0px 0px 15px #858585;
	top: 6px;
	right: 6px;
	}
.newsletter form input:last-child:hover{
	transform: scale(1.2);
	cursor: pointer;
}
	.about {
		width: 100%;
		padding: 100px 0px;
		background-color: #191919;
	}
	.about img {
		height: auto;
		width: 430px;
		border-radius: 300px;
	}
	.about-text {
		width: 550px;
	}
	.main {
		width: 1130px;
		max-width: 95%;
		margin: 0 auto;
		display: flex;
		align-items: center;
		justify-content: space-around;
	}
	.about-text h2 {
		color: white;
		font-size: 75px;
		text-transform: capitalize;
		margin-bottom: 20px;
	}
	.about-text h5 {
		color: white;
		letter-spacing: 2px;
		font-size: 22px;
		margin-bottom: 25px;
		text-transform: capitalize;
	}
	.about-text p {
		color: #fcfc;
		letter-spacing: 1px;
		line-height: 28px;
		font-size: 18px;
		margin-bottom: 45px;
	}
	button{
		background-color: #FF142A;
		color: white;
		text-decoration: none;
		border: 2px solid transparent;
		font-weight: bold;
		padding: 13px 30px;
		border-radius: 30px;
		transition: .4s;
	}
	button:hover{
		background-color: transparent;
		border: 2px solid #FF142A;
		cursor: pointer;
	}

.service{
	background-color: #101010;
	width: 100%;
	padding: 100px 0px;
}
.title h2{
	color: white;
	font-size: 75px;
	width: 1130px;
	margin: 30px auto;
	text-align: center;
}
.box{
	display: flex;
	justify-content: center;
	align-items: center;
	min-height: 400px;
}
.card{
	height: 365px;
	width: 335px;
	padding:20px 35px;
	background: #191919;
	border-radius: 20px;
	margin: 15px;
	position: relative;
	overflow: hidden;
}
.card i{
	font-size: 50px;
	display: block;
	text-align: center;
	margin: 25px 0px;
	color: #FF142A;
}
h5{
	color: white;
	font-size: 23px;
	margin-bottom: 15px;
}
.pra p{
	color: #fcfc;
	font-size: 16px;
	line-height: 27px;
	margin-bottom: 25px;
}
.card .button{
	background-color: #FF142A;
	color: white;
	text-decoration: none;
	border: 2px solid transparent;
	font-weight: bold;
	padding: 9px 22px;
	border-radius: 30px;
	transition: .4s;
}
.card .button:hover{
	background-color: transparent;
	border: 2px solid #FF142A;
	cursor: pointer;	
}
.contact-me{
	width: 100%;
	height: 290px;
	background: #191919;
	display: flex;
	align-items: center;
	flex-direction: column;
	justify-content: center;
}
.contact-me p{
	color: white;
	font-size: 30px;
	font-weight: bold;
	margin-bottom: 25px;
}
.contact-me .button-two{
	background-color: #FF142A;
	color: white;
	text-decoration: none;
	border: 2px solid transparent;
	font-weight: bold;
	padding: 13px 30px;
	border-radius: 30px;
	transition: .4s;	
}
.contact-me .button-two:hover{
	background-color: transparent;
	border: 2px solid #FF142A;
	cursor: pointer;
}
footer{
	width: 100%;
	height: 400px;
	background: #101010;
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: center;
	position: relative;
}
footer p:nth-child(1){
	font-size:30px;
	color: white;
	margin-bottom: 20px;
	font-weight: bold;
}
footer p:nth-child(2){
	color: #fcfc;
	font-size: 17px;
	width: 500px;
	text-align: center;
	line-height: 26px;
}
.social{
	display: flex;
}
.social a{
	width: 45px;
	height: 45px;
	display: flex;
	align-items: center;
	justify-content: center;
	background: #FF142A;
	border-radius: 50%;
	margin:22px 10px;
	color: white;
	text-decoration: none;
	font-size: 20px;
}
.social a:hover{
	transform: scale(1.3);
	transition: .3s;
}
.end{
	position: absolute;
	color: #FF142A;
	bottom: 35px;
	font-size: 14px;
}
