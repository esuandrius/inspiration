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
