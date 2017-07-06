<!--# Some-beginning-projects
My beginner projects-->
<!DOCTYPE html>
<html>
<head>
	<title>Registration</title>
</head>
<body>

<h1>Register</h1>
<form>
	<label for="firs">First Name:</label>
	<input  name="first" id="first" type="text" placeholder="ex.John" required >
	<label name="last">Last Name:</label>
	<input name="last"id="lastName" type="text" placeholder="ex.Smith" required>
	
	<div>
		<label for="male">Male</label>
		<input id="male" name="gender" type="radio" value="male" required>
		<label for="female">Female</label>
		<input id="female" name="gender" type="radio" value="female" required>	
		<label for="other">Other</label>
		<input id="other" name="gender" type="radio" value="other" required>	
	</div>
	<div>
		<label for="userEmail">Email:</label>
		<input id="userEmail" type="email" required placeholder="your email">
		<label>Password:</label>
		<input type="Password" minlength="5" maxlength="10" size="10" required >
	</div>
	<div>
		<label>Birthday:</label>
		<select name="month" required>
			<option>Month</option>
			<option>Jan</option>
			<option>Feb</option>
			<option>Mar</option>
			<option>Apr</option>
			<option>May</option>
			<option>Jun</option>
			
		</select>
		<select name="day" required>
			<option>Day</option>
			<option>01</option>
			<option>02</option>
			<option>03</option>
			<option>04</option>
			<option>05</option>
			<option>06</option>
			<option>07</option>
			<option>08</option>
			<option>09</option>
			<option>10</option>
			<option>11</option>
			
		</select>
		<select name="year" required>
			<option>Year</option>
			<option>1999</option>
			<option>2000</option>
			<option>2001</option>
			<option>2002</option>
			<option>2003</option>
			<option>2004</option>
			<option>2005</option>
			<option>2006</option>
			<option>2007</option>
			<option>2008</option>
			<option>2009</option>
			<option>2010</option>
			<option>2011</option>
			<option>2012</option>
			<option>2013</option>
			<option>2014</option>
			<option>2015</option>
			<option>2016</option>
			<option>2017</option>
		</select>
	</div>

	<p>I agree to the trems and conditions
		<input type="checkbox" required>
	</p>	
	<button>Submit</button>

</form>

</body>
</html>
