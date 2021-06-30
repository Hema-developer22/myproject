# myproject
<html>
<head>
	<title>e-voting system</title>
</head>
<body>
	<div id="form">
		<fieldset>
			<legend><h1>Voting Management System</h1></legend>
			<label>Name:</label>&nbsp;&nbsp;
			<input type="text"name="name"placeholder="Enter your name"required><br><br>
			<label>Father's Name:</label>&nbsp;&nbsp;
			<input type="text"name="fname"placeholder="Enter your Father's name"required><br><br>
			<label>DOB:</label>&nbsp;&nbsp;
			<input type="date"name="dob"required><br><br>
			<label>Gender:</label>&nbsp;&nbsp;
			<input type="radio"name="gender"class="g"value="male">Male
			<input type="radio"name="gender"class="g"value="female">Female<br><br>
			<label>CNIC:</label>&nbsp;&nbsp;
			<input type="number"name="cnic"placeholder="Enter your CNICnumber"maxlength="15"required><br><br>
			<label>Political Parties:</label>&nbsp;&nbsp;
			<select name="political">
				<option value="NULL">Choose political party</option>
				<option value="NTK">NTK</option>
				<option value="DMK">DMK</option>
				<option value="ADMK">ADMK</option>
				<option value="INC">INC</option>
				<option value="IJK">IJK</option>
				<option value="DMDK">DMDK</option>
				<option value="BJP">BJP</option><br><br>
			</select>
		</fieldset><br>
           <a href="#aligncenter"> <input type="submit" name="submit"value="submit"></a>
	</div><br><br><br><br><br><br><br><br><br><br>
	<style>
	#form{
		width: 45%;
		margin=auto;
		display: block;
		text-align: center;
		font-size: 20px;
		font-family: lato-sans sans-serif;
		padding-left: 25%;
	}
	h1{
		text-align: center;
		font-size: 24px;
        font-weight: bold;
        cursor: pointer;
	}
	fieldset{
		border-radius: 15px 15px 15px 15px;
	}
	label{
		font-weight: bold;
		display: inline-block;
		margin: 5px;
	}
	input[type=data],[type=number],[type=text],select{
		background: #FFF;
		border: 1px solid #000;
		border-radius: 2px;
		border-width: 1px;
		color: 36454b;
		font-size: 15px;
		margin: 5px;
		padding: 12px 12px;
        display: inline-block;
	}
	input[type=radio].g{
		margin-left: 35px;
	}
	input[type=submit]{
		color: #FFF;
		padding: 15px 50px;
		text-align: center;
		font-size: 24px;
		margin: 12px 14px;
		cursor: pointer;
		border: 1px solid #000;
		border-radius: 4px;
		background-color: #000;
	}
</style>
<p id="aligncenter">
<img src="G:\photos\thankyou.png"height=20%,width=20px>
</p>
<style>
	#aligncenter{
        text-align: center;
	}
</style>
</body>
</html>
