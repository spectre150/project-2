<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bulma@0.9.2/css/bulma.min.css">
</head>
<body>
    <section class="hero is-primary is-fullheight">
        <div class="hero-body">
            <div class="container">
                <h1 class="title">Welcome to My Website</h1>
                <p class="subtitle">feel free to check my website.</p>
            </div>
        </div>
    </section>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Biography</title>
	<style>
		body {
			background-color: #f5f5f5;
			font-family: 'Roboto', sans-serif;
			margin: 0;
			padding: 0;
		}
		header {
			background-image: url('background.jpg');
			background-size: cover;
			background-position: center;
			height: 100vh;
			display: flex;
			align-items: center;
			justify-content: center;
			color: #fff;
			text-align: center;
		}
		header h1 {
			font-size: 4rem;
			margin: 0;
		}
		.profile {
			background-color: #fff;
			border-radius: 50%;
			height: 200px;
			margin: 50px auto;
			overflow: hidden;
			width: 200px;
		}
		.profile img {
			height: 100%;
			object-fit: cover;
			width: 100%;
		}
		.biography {
			background-color: hsl(0, 0%, 100%);
			border-radius: 5px;
			box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
			margin: 50px auto;
			max-width: 800px;
			padding: 30px;
			text-align: left;
		}
		.biography h2 {
			font-size: 2.5rem;
			margin-top: 0;
		}
		.biography p {
			font-size: 1.2rem;
			line-height: 1.5;
			margin-bottom: 20px;
		}
		.biography ul {
			list-style: none;
			margin: 0;
			padding: 0;
		}
		.biography li {
			font-size: 1.2rem;
			margin-bottom: 10px;
		}
		.social-media {
			display: flex;
			justify-content: center;
			margin-top: 30px;
		}
		.social-media a {
			color: #333;
			font-size: 2rem;
			margin: 0 10px;
			text-decoration: none;
		}
		.cta-button {
			background-color: hsl(258, 96%, 51%);
			border: none;
			border-radius: 5px;
			color: #fff;
			font-size: 1.5rem;
			padding: 15px 30px;
			text-transform: uppercase;
			margin: 50px auto;
			display: block;
		}
	</style>
</head>
<body>
	<header>
		<h1>My Biography</h1>
	</header>
	<div class="profile">
		<img src="tantan0.jpg" alt="Profile Picture">
	</div>
	<div class="biography">
		<h2>About Me</h2>
		<p>I was born at Surabaya, 15 March 2006. Since child I have everything 
			I need even I never ask. My elementary school is at SDK Santa Angela 
			I always love here. After finish my elementary school I go to 
			SMPK Karitas 3 to begin my junior high school at this age I know 
			my first love and first time I ever study code and experiment.
            The last is Senior high school that I learn and dedicated to more at IT</p>
		<ul>
			<li>Age: 18</li>
			<li>Location: Surabaya</li>
			<li>Occupation: Students</li>
		</ul>
		<h2>Skills</h2>
		<p>Social genius and easy adaptation in new environment 
			also I can make a story in instant time just with a pen
			and write the story in my laptop</p>
        <h2>Language That I Master At :</h2>
	    <ul>
			<li>HTML/CSS</li>
			<li>JavaScript</li>
			<li>Photoshop</li>
		</ul>
		<h2>here is my project :</h2>
		<a href="tantan2.html"> click here </a>
</body>
</html>
