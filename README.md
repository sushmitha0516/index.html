# index.html
<!DOCTYPE html>
<html>
<head>
<title> Registration </title>
</head>
<style>
fieldset{
 width:300px;
height:auto;
margin:10px auto;
}
legend{
text-align:center;
}
</style>
<body>
<fieldset>
<legend>Registration </legend>
<form>
<label>username:</label>
<input type="username" placeholder="enter username"><br><br>
<label>password:</label>
<input type="password" placeholder="enter password"><br><br>
<label>Email</label>
<input type="email" placeholder="enter your mail"><br><br>
<label>gender:</label>
<input type="radio" name="gender">Male
<input type="radio" name="gender">female
<input type="radio" name="gender">other
<br><br>
<label>Date of birth</label>
<input type="date"><br><br>
<label>Locations</label>
<select>
<option value="select your location">select</option>
<option value="hyd">Hyderabad </option>
<option value ="war">warangal</option>
<option value="kham">khammam</option >
</select><br><br>
<label>hobbies</label>
<input type="checkbox" >listening music<br><br>
<input type="checkbox">playing games<br><br>
<input type="checkbox">reading books<br><br>
<label>upload</label>
<input type="file"><br><br>
<label>address</label>
<input type="textarea" rows="10px" cols="10px"><br><br>
<input type="submit" value="submit">
<input type="button" value="Reset">
</form >
</fieldset>
</body>
</html>











