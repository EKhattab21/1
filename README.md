<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
	<script src="Scripts/jquery-3.1.1.js"></script>
	<script src="Scripts/materialize/materialize.js"></script>
	<link href="content/materialize/css/materialize.css" rel="stylesheet" />
	<link href="css/StyleSheet1.css" rel="stylesheet" />
	<link href="css/Account Stylesheet.css" rel="stylesheet" />
	<link href="http://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
	<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet">
    <title></title>
</head>
<body>
	<!-- Dropdown Structure -->
	<ul id="dropdown1" class="dropdown-content">
		<li><a href="#!">Healing Tarvel</a></li>
		<li><a href="#!">Torusim</a></li>
		<li class="divider"></li>
		<li><a href="#!">Islamic Tarvels</a></li>
	</ul>
	<!--Header-->
	<nav>
		<div class="nav-wrapper navbar">
			<a href="Main Page.html" class="brand-logo right logo"><img src="IMAGES/Travel-Agency-Logo-6.png" width="200" /></a>
			<ul id="nav-mobile" class="left hide-on-med-and-down">
				<li><a href="Main Page.html">Home</a></li>
				<li><a href="badges.html">Account</a></li>
				<li><a class="dropdown-button" href="#!" data-activates="dropdown1"><i class="material-icons right">arrow_drop_down</i>Fligths</a></li>
			</ul>
		</div>
	</nav>

	<!--End of Header-->
	<br />
	<br />
	<!--Main-->
	
		<div class="row" id="form">
			<div class="col s4"></div>
			<form class="col s10">
				<div class="row">
					
					<div class="input-field col s4">
						<i class="material-icons prefix">account_circle</i>
						<input id="icon_prefix first_name" type="text" class="validate">
						<label for="first_name">First Name</label>
					</div>
					<div class="input-field col s4">
						<i class="material-icons prefix">account_circle</i>
						<input id="icon_prefix last_name" type="text" class="validate">
						<label for="last_name">Last Name</label>
					</div>
				</div>
				<div class="row">
					<div class="input-field col s4">
						<input id="email" type="email" class="validate">
						<label for="email">Email</label>
					</div>

					<div class="input-field col s4">
						<input id="password" type="password" class="validate">
						<label for="password">Password</label>
					</div>
				</div>
				<div class="row">
					<div class="col s6">
						
						<div class="input-field inline">
							<input type="date" class="datepicker" placeholder="BirthDate">
							<label for="email" data-error="wrong" data-success="right"></label>
						</div>


						<button class="btn waves-effect waves-light right" type="submit" name="action">
							Sign Up
							<i class="material-icons right">send</i>
						</button>

					</div>
				</div>
			</form>
		</div>


	<!--Footer-->
	<footer class="page-footer footer">
		<div class="container">
			<div class="row">
				<div class="col l6 s12">
					<h5 class="white-text">Footer Content</h5>
					<p class="grey-text text-lighten-4">You can use rows and columns here to organize your footer content.</p>
				</div>
				<div class="col l4 offset-l2 s12">
					<h5 class="white-text">Links</h5>
					<ul>
						<li><a class="grey-text text-lighten-3" href="#!">Link 1</a></li>
						<li><a class="grey-text text-lighten-3" href="#!">Link 2</a></li>
						<li><a class="grey-text text-lighten-3" href="#!">Link 3</a></li>
						<li><a class="grey-text text-lighten-3" href="#!">Link 4</a></li>
					</ul>
				</div>
			</div>
		</div>
		<div class="footer-copyright">
			<div class="container">
				© 2014 Copyright Text
				<a class="grey-text text-lighten-4 right" href="#!">More Links</a>
			</div>
		</div>
	</footer>
	<!--End Of Footer-->
</body>
</html>
<script type="text/javascript">
	$(document).ready(function () {
		Materialize.updateTextFields();
	});

	$('.datepicker').pickadate({
		selectMonths: true, // Creates a dropdown to control month
		selectYears: 15 // Creates a dropdown of 15 years to control year
	});

</script>
