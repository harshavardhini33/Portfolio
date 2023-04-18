# Portfolio using HTML and CSS
```
Register No: 212221240015
Name: Harshavardhini M
```
## Program
### Home.html
```
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<meta http-equiv="X-UA-Compatible" content="ie=edge">
	<title>My Portfolio</title>
	<link href="https://fonts.googleapis.com/css?family=Montserrat:400,700&display=swap" rel="stylesheet">
	<style>
		/* div {
    		width: 100px;
    		height: 100px;
    		background: #ffffff;
  		} */
		body {
			font-family: 'Montserrat', sans-serif;
			margin: 0;
			padding: px;
			background-color:rgb(54, 58, 46);
			color: #fff;
		}
		header {
			background-color: #1abc9c;
			color: #fff;
			padding: 20px;
		}
		/* h1 {
			font-size: 60px;
			margin: 0;
			position: center;
			text-transform: uppercase;
			
		} */
		h2 {
			font-size: 24px;
			margin: 0;
			text-align: left;
			display: inline;
		}
		h3{
			font-size: 22px;
			margin: 0;	
			font-weight: normal;
			display: inline;
		}
		p {
			font-size: 18px;
			margin-top: 20px;
		}
		nav {
			background-color: #1abc9c;
			/* background-color: #f1c40f; */
			padding: 20px;
		}
		nav ul {
			list-style: none;
			margin: 0;
			padding: 0;
			display: flex;
			justify-content: right;
		}
		nav li {
			margin: 0 10px;
		}
		nav a {
			color: #fff;
			text-decoration: none;
			font-size: 18px;
			text-transform: uppercase;
			letter-spacing: 2px;
			transition: color 0.3s ease-in-out;
		}
		nav a:hover {
			color: #333;
		}
		section {
			padding: 50px;
			text-align: center;
		}
		section h1{
			display: flex;
			justify-content: center;
			font-size: 100px;
			float: inline-start;
			vertical-align: middle;
		}
		section h3 {
			display: flex;
			justify-content: center;
			font-size: 22px;
			margin: 0;
		}
		section p {
			
			font-size: 18px;
			margin-top: 20px;
			line-height: 1.5;
			flex-direction: column;
		}
		section img {
			max-width: 520px;
			/* justify-content: left center; */
			margin-left: 200px;
			margin-top: 110px;
			/*height: 100px;
			
			
			position: left; */
		}
		.footer{
    		display: flex;
			justify-content: space-around;
    		text-align:left;
    		padding: 15px;
    		/* background-color: #abbaba; */
    		color: #ffffff;
			margin-top: 100px;

        }
		.footer_element{
			display: inline-flex;
			font-size: 18px;
			color: white;
			padding: 10px;
		}

		
	</style>
</head>
<body>
	<header>
		<a href="http://127.0.0.1:5500/Home.html" target="_self;" style ="text-decoration:none; color: #fff; " ><h2>Harshavardhini M</h2></a><h3>&nbsp; AI Aspirant</h3>
		
	</header>
	<nav>
		<ul>
			<li><a href="http://127.0.0.1:5500/Resume.html">Resume</a></li>
			<li><a href="#projects">Projects</a></li>
			<li><a href="http://127.0.0.1:5500/contact.html">Contact</a></li>
			<li><a href="#portfolio">Portfolio</a></li>
		</ul>
	</nav>
	<section id="image">
		<div class = "container">
			<img align = "left" src="https://www.pngkey.com/png/full/203-2037403_flat-faces-icons-circle-girl-flat-icon-png.png" alt="Profile photo">
			
		</div>
		
	</section>
	<section id="about">
		<h1>HEYYA!</h1><br>
		<h3><b>A Bit About Me</b></h3>
		<p align="center" style="margin-left: 250px;">I am ambitious and driven. I thrive on challenge and constantly set goals for myself, so I have something to strive towards. I am not comfortable with settling, and I am always looking for an opportunity to do better and achieve greatness.</p>
		
	</section>
<br><br><br><br><br><br><br><br>
<div style="border-top: 0.5px solid white; width: 2000px; position: absolute; transform: translate(6%);"></div>
<div class = "footer" style="padding-bottom: 100px;">
	<div class = "footer_element">
		Phone<br>+91 8189829969
	</div>
	<div class="footer_element">
		Email
		<br>
		beingharshaa@gmail.com
	</div>
	<div class="footer_element">Follow Me
	</div>
	<div class="footer_element">
		© 2035 By Harshavardhini.
	</div>
</div>
</body>
```
### Contact.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Contact Page</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
  font-family: Arial, Helvetica, sans-serif;
  background-color: rgb(0, 94, 255);
}
header {
	background-color:  rgb(0, 94, 255)c9c;
	color: #fff;
	padding: 20px;
		}


* {
  box-sizing: border-box;
}
h2 {
	font-size: 24px;
	margin: 0;
	text-align: left 20px;
	display: inline;
}
h3{
	font-size: 22px;
	margin: 0;	
	font-weight: normal;
	display: inline;
}

/* Style inputs */
input[type=text], select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
}

input[type=submit] {
  background-color: #005eff;
  color: rgb(54, 58, 46);
  padding: 12px 20px;
  border: none;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #000094;
}

/* Style the container/contact section */
.container {
  border-radius: 5px;
  background-color: white;
  padding: 10px;
}

/* Create two columns that float next to eachother */
.column {
  float: left;
  width: 50%;
  margin-top: 6px;
  padding: 20px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - when the screen is less than 600px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column, input[type=submit] {
    width: 100%;
    margin-top: 0;
  }
}
img{
    max-width: 600px;
    margin-left: 120px;
}
</style>
</head>
<body>
    <header>
		<a href="http://127.0.0.1:5500/Home.html" target="_self;" style ="text-decoration:none; color: #fff;" ><h2>Harshavardhini M</h2></a><h3>&nbsp; AI Aspirant</h3>
		
	</header>

<div class="container">
  <div style="text-align:center">
    <h1>Contact Me</h1>
    <h3
    >Leave a message here:</h3>
  </div>
  <div class="row">
    <div class="column">
      <img src="CONTPIC.jpg" style="width:100%">
    </div>
    <div class="column">
      <form action="/action_page.php">
        <label for="fname">First Name</label>
        <input type="text" id="fname" name="firstname" placeholder="Your name..">

        <label for="lname">Last Name</label>
        <input type="text" id="lname" name="lastname" placeholder="Your last name..">

        <label for="email">Email Id</label>
        <input type="text" id="email" name="mailid" placeholder="Your mail id...">

        <label for="country">Country</label>
        <select id="country" name="country">
          <option value="india">India</option>
          <option value="pakistan">Pakistan</option>
          <option value="usa">USA</option>
          <option value="china">China</option>
          <option value="japan">Japan</option>
        </select>
        <label for="subject">Subject</label>
        <textarea id="subject" name="subject" placeholder="Write something.." style="height:170px"></textarea>
        <input style="color: white;" type="submit" value="Submit">
      </form>
    </div>
  </div>
</div>

</body>
</html>
```
## Output
### Home.html
![Screenshot (49)](https://user-images.githubusercontent.com/93427208/232665230-9b1eaeba-d6b9-4c91-933e-1e993c6594c9.png)

### Contact.html
![Screenshot (65)](https://user-images.githubusercontent.com/93427208/232665267-5f40619b-3944-4ccd-9a74-7823aef9812f.png)

