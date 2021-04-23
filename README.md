# UI_Layer

}<!DOCTYPE html>

<html>

<head>
	<title>Responsive Web Design</title>

	<style>
		* {
            box-sizing: border-box;
		}
        

		.navbar {
			display: flex;
			align-items: center;
			justify-content: center;
			position: sticky;
			top: 0;
			cursor: pointer;
		}

		.background {
			background: rgb(142, 213, 247);
			background-blend-mode: darken;
			background-size: cover;
		}

		.nav-list {
			width: 70%;
			display: flex;
			align-items: center;
		}

		.logo {
			display: flex;
			justify-content: center;
			align-items: center;
		}

		.logo img {
			width: 180px;
			border-radius: 50px;
		}

		.nav-list li {
			list-style: none;
			padding: 26px 30px;
		}

		.nav-list li a {
			text-decoration: none;
			color: rgb(20, 19, 19);
		}

		.nav-list li a:hover {
			color: grey;
		}

		.rightnav {
			width: 30%;
			text-align: right;
		}

	
           .column {
  float: left;
  width: 50%;
  padding: 10px;
  height: 500px; 
}


.row:after {
  content: "";
  display: table;
  clear: both;
	
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
		
       
	
		

		


		.text-footer {
			text-align: center;
			padding: 20px 0;
			font-family: 'Ubuntu', sans-serif;
			display: flex;
			justify-content: center;
			color: rgb(12, 12, 12);
		}
	</style>
</head>

<body>
	<nav class="navbar background">
		<ul class="nav-list">
			<div class="logo">
				<img src= "Mastek_Logo.png">
			</div>
			<li><a href="#Home">Home</a></li>
			<li><a href="#News">News</a></li>
			<li><a href="#contact">Contact Us</a></li>
		</ul>

		
	</nav>

	
   <div class="row">
  <div class="column" style="background-color:#aaa;">
    <h2>Column 1</h2>
    <p>Some text..</p>
  </div>
  <div class="column" style="background-color:#bbb;">
    <h2>Column 2</h2>
    <p>Some text..</p>
  </div>
</div>
       
	<footer class="background">
		<p class="text-footer">
			Copyright ©-All rights are reserved
		</p>
	</footer>
</body>

</html>
