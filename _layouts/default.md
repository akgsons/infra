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
					<li><a href="/info">Info</a></li>
		        	        <li><a href="/contact">Contact Us</a></li>
                                        <li><a href="/careers">Careers</a></li>
					<li>
						<span class="logo">
							akgsons<span style="font-weight:400;">Infra</span>
						</span>
					</li>					
	    		</ul>
			</nav>
			<p/>
			<div class="container">		
				<h2>{{ page.title }}</h2>	
				<hr/>											
				{{ content }}						
			</div>
			<br/>
			<footer>
				<ul>
					<li><a href="https://github.com/akgsons/infra">Github</a></li>
				<ul>
			</footer>
		</body>
	</html>
