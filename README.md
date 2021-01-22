<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-acale=1.0, minimum-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Instagram Login</title>
  <style>
    ,
::before,
::after{
	margin: 0;
	padding: 0;
	box-sizing: inherit;
}

html{
	font-size: 10px;
	box-sizing: border-box;
}

img{
	width: 100%;
	max-width: 100%;
	height: 100%;
}

a{
	text-decoration: none;
}

body{
	background-color: #fafafa;
}

#wrapper{
	width: 100%;
	height: 100vh;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
	padding-top: 10rem;
}

.container{
	width: 100%;
	max-width: 93.5rem;
	margin: 3rem auto 0;
}

#wrapper > .container{
	display: flex;
	padding: 0 8rem;
}

.phone-app-demo{
	height: 61.8rem;
	background: url("https://www.cheatsheet.com/wp-content/uploads/2014/12/Instagram-post-with-likes-and-comments.png") center no-repeat;
    flex: 1;
}

.form-data form{
	background-color: #fff;
	border: 2px solid #eee;
	display: flex;
	flex-direction: column;
	padding: 2rem 4rem;
	text-align: center;
}

.logo img{
	width: 17.5rem;
	margin-bottom: 2.5rem;
}

.form-btn{
	margin: 1rem 0 1.5rem;
	height: 3rem;
	background-color: #3897f0;
	font-size: 1.4rem;
	color: #fff;
	font-weight: bold;
	border: none;
	border-radius: 4rem;
	cursor: pointer;
}

.has-seperator{
	font-size: 1.3rem;
	color: #999999;
	text-transform: uppercase;
	position: relative;
	margin-bottom: 2.5rem;
}

.has-seperator::before;
.has-seperator::after;{
	content: "";
	position: absolute;
	background-color: #eee;
	width: 40%;
	height: 1px;
	top: 50%;
	transform: translateY(-50%);
}

.has-seperator::before{
	left: 0;
}

.has-seperator::after{
	right: 0;
}

.facebook-login{
	font-size: 1.4rem;
	font-weight: bold;
	color: #385185;
	margin-bottom: 2.5rem;
}

.facebook-login i{
	font-size: 2rem;
	margin-right: .7rem;
}

.password-reset{
	font-size: 1.2rem;
    color: #003569;
}

.sign-up{
	text-align: center;
	font-size: 1.4rem;
	color: #262626;
	padding: 2rem 0;
	background-color: #fff;
	border: 2px solid #eee;
	margin: 1rem 0;
}

.sign-up a{
	color: #3897f0;
	font-weight: bold;
}

.get-the-app{
	font-size: 1.4rem;
	text-align: center;
}

.get-the-app span{
	display: block;
	margin: 2rem 0;
	color: #262626;
}

.badges{
	width: 100%;
	display: flex;
	justify-content: center;
}

.badges img{
	max-width: 14rem;
	cursor: pointer;
}

.badges img:first-child{
	margin-right: 1rem;
}

footer{
	padding: 5rem 0;
}
footer.container{
	display: flex;
	justify-content: space-between;
	font-weight: bold;
	text-transform: uppercase;
	font-size: 1.3rem;
	flex-wrap: wrap;
	margin-top: 0;
}

.footer-nav ul{
	display: flex;
	flex-wrap: wrap;
	list-style: none;
}

.footer-nav ul li{
	margin-right: 1.6rem;
}

.footer-nav ul li a{
	color:#003569;
}

.copyright-notice{
	color: #999999;
}

@media (max-width: 900px){
	.phone-app-demo{
		display: none;
	}
}

.form-data{
	margin: 0 auto;
}

#wrapper > .container{
	padding: 0;
}

footer .container{
	padding: 0 2rem;
	justify-content: center;
}

.footer-nav ul li{
	margin-bottom: 1rem;
}

@media (max-width: 450px){
	#wrapper{
		padding-top: 0;
	}
	.form-data form{
		background-color: transparent;
		border: none;
		padding: 0 2rem;
	}
    .sign-up{
    	background-color: transparent;
    	border: none;
    	margin: 4rem 0;
    }
    footer{
    	padding-bottom: 2rem;
    }
}
  </style>
</head>
<body>

<div id="wrapper">
	<div class="container">
		<div class="phone-app-demo"></div>
		<div class="form-data">
			<form action="">
				<div class="logo">
					<img src="https://i.pinimg.com/474x/0b/94/c8/0b94c8b58d2f188a2cc5db12e93e5ad7.jpg" alt="Instagram logo">
				</div>
				<input type="text" placeholder="Phone number, username, or email-id">
				<input type="password" placeholder="Password">
				<button class="form-btn" type="submit">Log in</button>
				<span class="has-seperator">or</span>
				<a class="facebook-login" href="#">
					<i class="fab fa-facebook"></i> Log in with Facebook
				</a>
				<a class="password-reset" href="#">Forgot password?</a>
			</form>
			<div class="sign-up">
				Don't have an account? <a href="#">Sign up</a>
			</div>
			<div class="get-the-app">
				<span>Get the app.</span>
				<div class="badges">
					<img src="https://www.instagram.com/static/images/appstore-install-badges/badge_ios_english-en.png/180ae7a0bcf7.png" alt="appstore-install-badges">
					<img src="https://www.instagram.com/static/images/appstore-install-badges/badge_android_english-en.png/e9cd846dc748.png" alt="playstore-install-badges">
				</div>
			</div>
		</div>
	</div>
	<footer>
		<div class="container">
			<nav class="footer-nav">
				<ul>
					<li>
						<a href="#">ABOUT</a>
					</li>
					<li>
						<a href="#">HELP</a>
					</li>
					<li>
						<a href="#">PRESS</a>
					</li>
					<li>
						<a href="#">API</a>
					</li>
					<li>
						<a href="#">JOBS</a>
					</li>
					<li>
						<a href="#">PRIVACY</a>
					</li>
					<li>
						<a href="#">TERMS</a>
					</li>
					
					<li>
						<a href="#">LOCATIONS</a>
					</li>
					<li>
						<a href="#">TOP ACCOUNTS</a>
					</li>
					<li>
						<a href="#">HASHTAGS</a>
					</li>
					<li>
						<a href="#">LANGUAGE</a>
					</li>
				</ul>
			</nav>
			<div class="copyright-notice">
				&copy; 2020 INSTAGRAM FROM FACEBOOK
			</div>
		</div>
	</footer>
</div>

</body>
</html>
