# Zhanwuli
+<!DOCTYPE html>
<html>
<head>
<title>Account</title>
<link href="css/bootstrap.css" rel='stylesheet' type='text/css' />
<!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
<script src="js/jquery.min.js"></script>
<!-- Custom Theme files -->
<link href="css/style.css" rel="stylesheet" type="text/css" media="all" />
<link href="css/demo1.css" rel="stylesheet" type="text/css" media="all" />
<!-- Custom Theme files -->
<meta name="viewport" content="width=device-width, initial-scale=1">
<script type="application/x-javascript"> addEventListener("load", function() { setTimeout(hideURLbar, 0); }, false); function hideURLbar(){ window.scrollTo(0,1); } </script>
<!--webfont-->
<link href='https://fonts.googleapis.com/css?family=Yanone+Kaffeesatz:400,200,300,700' rel='stylesheet' type='text/css'>
<link href='https://fonts.googleapis.com/css?family=Source+Sans+Pro:200,300,400,600,700,900,200italic,300italic,400italic,600italic,700italic,900italic' rel='stylesheet' type='text/css'>
<link href='https://fonts.googleapis.com/css?family=Karla:400,400italic,700,700italic' rel='stylesheet' type='text/css'>
		<!-- JavaScript includes -->
		<script src="js/ipresenter.packed.js"></script>
		<script>
			$(document).ready(function(){
				$('#ipresenter').iPresenter({
					timerPadding: -1,
					controlNav: true,
					controlNavThumbs: true,
					controlNavNextPrev: false
				});
			});
		</script>
		    <script type="text/javascript" src="js/move-top.js"></script>
<script type="text/javascript" src="js/easing.js"></script>
<script type="text/javascript">
			jQuery(document).ready(function($) {
				$(".scroll").click(function(event){		
					event.preventDefault();
					$('html,body').animate({scrollTop:$(this.hash).offset().top},1200);
				});
			});
		</script>
</head>
<body>
	<!-- header-section-starts -->
	<div class="user-desc">
		<div class="container">
			<ul>
				<li><a href="checkout.html">Checkout</a></li>
				<li><i class="user"></i><a href="account.html">My Account</a></li>
				<li><i class="cart"></i><a href="#">Cart (3)</a></li>
			</ul>
		</div>
		</div>
		<div class="header">
		<div class="header-top">
			<div class="container">
				<div class="logo">
					<a href="index.html"><img src="images/logo.png" alt="" /></a>
				</div>
				<div class="top-menu">
				 <span class="menu"> </span>
					<ul class="cl-effect-15">
						<li><a href="index.html" data-hover="HOME">HOME</a></li>
						<li><a href="404.html" data-hover="NEWS">NEWS</a></li>
						<li><a href="products.html" data-hover="PRODUCTS">PRODUCTS</a></li>
						<li><a href="404.html" data-hover="FEATURES">FEATURES</a></li>
						<li><a href="contact.html" data-hover="CONTACT">CONTACT</a></li>
					</ul>
				</div>
				<!--script-nav-->
				<script>
				$("span.menu").click(function(){
				$(".top-menu ul").slideToggle("slow" , function(){
				});
				});
				</script>
				<!--script-nav-->
				<div class="clearfix"></div>
			</div>
		</div>
		</div>
<!-- header-section-ends -->
<!-- content-section-starts -->
	<!-- start registration -->
	<div class="container">
		<div class="registration">
		<div class="registration_left">
		<h2>new user? <span> create An account </span></h2>
		<a href="#"><div class="reg_fb"><img src="images/facebook.png" alt=""><i>register using Facebook</i><div class="clearfix"></div></div></a>
		<!-- [if IE] 
		    < link rel='stylesheet' type='text/css' href='ie.css'/>  
		 [endif] -->  
		  
		<!-- [if lt IE 7]>  
		    < link rel='stylesheet' type='text/css' href='ie6.css'/>  
		<! [endif] -->  
		<script>
			(function() {
		
			// Create input element for testing
			var inputs = document.createElement('input');
			
			// Create the supports object
			var supports = {};
			
			supports.autofocus   = 'autofocus' in inputs;
			supports.required    = 'required' in inputs;
			supports.placeholder = 'placeholder' in inputs;
		
			// Fallback for autofocus attribute
			if(!supports.autofocus) {
				
			}
			
			// Fallback for required attribute
			if(!supports.required) {
				
			}
		
			// Fallback for placeholder attribute
			if(!supports.placeholder) {
				
			}
			
			// Change text inside send button on submit
			var send = document.getElementById('register-submit');
			if(send) {
				send.onclick = function () {
					this.innerHTML = '...Sending';
				}
			}
		
		})();
		</script>
		 <div class="registration_form">
		 <!-- Form -->
			<form id="registration_form" action="contact.php" method="post">
				<div>
					<label>
						<input placeholder="first name:" type="text" tabindex="1" required autofocus>
					</label>
				</div>
				<div>
					<label>
						<input placeholder="last name:" type="text" tabindex="2" required autofocus>
					</label>
				</div>
				<div>
					<label>
						<input placeholder="email address:" type="email" tabindex="3" required>
					</label>
				</div>
				<div class="sky-form">
					<div class="sky_form1">
						<ul>
							<li><label class="radio left"><input type="radio" name="radio" checked=""><i></i>Male</label></li>
							<li><label class="radio"><input type="radio" name="radio"><i></i>Female</label></li>
							<div class="clearfix"></div>
						</ul>
					</div>
				</div>
				<div>
					<label>
						<input placeholder="password" type="password" tabindex="4" required>
					</label>
				</div>						
				<div>
					<label>
						<input placeholder="retype password" type="password" tabindex="4" required>
					</label>
				</div>	
				<div>
					<input type="submit" value="create an account" id="register-submit">
				</div>
				<div class="sky-form">
					<label class="checkbox"><input type="checkbox" name="checkbox" ><i></i>i agree to shoppe.com &nbsp;<a class="terms" href="#"> terms of service</a> </label>
				</div>
			</form>
			<!-- /Form -->
		</div>
	</div>
	<div class="registration_left">
		<h2>existing user</h2>
		<a href="#"><div class="reg_fb"><img src="images/facebook.png" alt=""><i>sign in using Facebook</i><div class="clear"></div></div></a>
		 <div class="registration_form">
		 <!-- Form -->
			<form id="registration_form" action="contact.php" method="post">
				<div>
					<label>
						<input placeholder="email:" type="email" tabindex="3" required>
					</label>
				</div>
				<div>
					<label>
						<input placeholder="password" type="password" tabindex="4" required>
					</label>
				</div>						
				<div>
					<input type="submit" value="sign in" id="register-submit">
				</div>
				<div class="forget">
					<a href="#">forgot your password</a>
				</div>
			</form>
			<!-- /Form -->
			</div>
		</div>
		<div class="clearfix"></div>
		</div>
		</div>
	</div>
</div>
   <!-- content-section-ends -->	
   <!-- contact-section-starts -->
	<div class="content-section">
		<div class="container">
			<div class="col-md-3 about-us">
				<h4>LITTLE ABOUT US</h4>
				<p><span>Sed posuere</span> consectetur  est at. Nulla vitae elit libero, a pharetra. Lorem ipsum <span>dolor sit</span> amet, consectetuer adipiscing elit.</p>
				<h4>FOLLOW US</h4>
				<div class="social-icons">
					<i class="facebook"></i>
					<i class="twitter"></i>
					<i class="rss"></i>
					<i class="vimeo"></i>
					<i class="dribble"></i>
					<i class="msn"></i>
				</div>
			</div>
			<div class="col-md-3 archives">
				<h4>ARCHIVES</h4>
				<ul>
					<li><a href="#">March 2012</a></li>
					<li><a href="#">February 2012</a></li>
					<li><a href="#">January 2012</a></li>
					<li><a href="#">December 2011</a></li>
				</ul>
			</div>
			<div class="col-md-3 contact-us">
				<h4>CONTACT US</h4>
				<ul>
					<li><i class="message"></i></li>
					<li><a href="mail-to:info@premiumcoding.com">info@premiumcoding.com</a></li>
				</ul>
				<ul>
					<li><i class="land-phone"></i></li>
					<li>800 756 156</li>
				</ul>
				<ul>
					<li><i class="smart-phone"></i></li>
					<li>+386408007561</li>
				</ul>
			</div>
			<div class="col-md-3 about-us">
				<h4>SIGN TO NEWSLETTER</h4>
				<input type="text" class="text" value="Name" onfocus="this.value = '';" onblur="if (this.value == '') {this.value = 'Name';}">
				<input type="text" class="text" value="Email" onfocus="this.value = '';" onblur="if (this.value == '') {this.value = 'Email';}">
				<input type="submit" value="subscribe">
			</div>	
			<div class="clearfix"></div>
		</div>
	</div>
	<!-- contact-section-ends -->
	<!-- footer-section-starts -->
	<div class="footer">
		<div class="container">
			<div class="col-md-6 bottom-menu">
				<ul>
					<li><a href="index.html">HOME</a></li>
					<li><a href="#">PORTFOLIO</a></li>
					<li><a href="#">SITEMAP</a></li>
					<li><a href="contact.html"> CONTACT</a></li>
				</ul>
			</div>
			<div class="col-md-6 copy-rights">
				<p>Copyright &copy; 2015.Company name All rights reserved.More Templates <a href="http://www.cssmoban.com/" target="_blank" title="模板之家">模板之家</a> - Collect from <a href="http://www.cssmoban.com/" title="网页模板" target="_blank">网页模板</a></p>
			</div>
			<div class="clearfix"></div>
		</div>
	</div>
	<!-- footer-section-ends -->

</body>
</html>
