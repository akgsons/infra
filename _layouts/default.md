<!DOCTYPE html>
	<html>
		<head>
			<title>{{ page.title }}</title>
			<link rel="stylesheet" type="text/css" href="/css/main.css">
		</head>
		<body>
			<nav>
	    		<ul>
	        		<li><a href="/">Home</a></li>
					<li><a href="/project">Projects</a></li>
					<li><a href="/blog">Blogs</a></li>
		        	<li><a href="/contact">Contact Us</a></li>
	    		</ul>
			</nav>
			<div class="container">		
				<h2>{{ page.title }}</h2>	
				<hr/>											
				{{ content }}						
			</div>
			<footer>
	    		<ul>
	        		<li><a href="https://github.com/akgsons/infra">Github</a></li>
				</ul>
			</footer>
		</body>
	</html>
