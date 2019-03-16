<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    
	<title>thaoanhie</title>
	<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
	<link href="https://fonts.googleapis.com/css?family=Righteous" rel="stylesheet" type="text/css" href="style.css">
	<link href="https://fonts.googleapis.com/css?family=Teko" rel="stylesheet">
	<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.2.0/css/all.css" integrity="sha384-hWVjflwFxL6sNzntih27bfxkr27PmbbK/iSvJ+a4+0owXq79v+lsFkW54bOGbiDQ" crossorigin="anonymous">
	<link rel='icon' href='img/logo3.png' type='image/x-icon'>
	
	<link rel="stylesheet" type="text/css" href="style.css">

</head>
<body>
	
	

	<nav class="navbar">
		
		<span class="open-slide">
			<a href="#" onclick="openSlideMenu()">
				<svg width="30" height="30">
					<path d="M0,5 30,5" stroke="#000" stroke-width="5"/>
					<path d="M0,14 30,14" stroke="#000" stroke-width="5"/>
					<path d="M0,23 30,23" stroke="#000" stroke-width="5"/>
				</svg>
			</a>
		</span>

		<div class="name">
			<span class="navbar-text">
				<a href="index.html">
			    thaoanhie
				</a>
			</span>
		</div>

		<a class="navbar-brand pos" href="index.html">
		    <img src="img/logo.png" width="40" height="40" alt="logo">
		</a>
					
	</nav>
	

	<div id="side-menu" class="side-nav">
		
			<a href="#" class="btn-close" onclick="closeSlideMenu()">&times;</a>
			
			<div class="category">
				<a href="work.html">Work</a>
				<a href="about.html">About</a>
				<a href="contact.html">Contact</a>
			</div>			
	</div>

	<div class="background">
		<img class="top img-gif" src="img/b.jpg">	
		<div class="image-container">		
			<img class="bottom " src="img/d.jpg">
		</div>
	</div>

	<script>
		function openSlideMenu(){
			document.getElementById('side-menu').style.width="100%";
		}
		
		function closeSlideMenu(){
			document.getElementById('side-menu').style.width="0px";
		}
	</script>

	
	<footer class="py-4 my-md-5 pt-md-5">
		<div class="container">
			<div class="row">
				<div class="text-center col-12 col-md-12 col-lg-12 col-xl-12">
					<p id="copy"><i class="far fa-copyright"></i> 2018 by Thaoanhie. All rights reserved.</p>
					<div class="link">
						<a href="https://www.facebook.com/thaoanhie"><i class="fab fa-facebook fa-2x "></i></a>
						<a href="https://www.instagram.com/thaoanhie"><i class="fab fa-instagram fa-2x"></i></a>
						<a href="https://twitter.com/thaoanhie"><i class="fab fa-twitter fa-2x"></i></a>
					</div>
				</div>
				
			</div>
		</div>

	</footer>



	<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
	<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>

	
</body>
</html>
