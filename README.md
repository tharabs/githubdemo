

<html> 
<head>
<title> Registration Form</title>
<script>
function passvalues()
{
var name = document.getElementById("name:").value;
var email = document.getElementById("email:").value;
var address = document.getElementById("address:").value;
localStorage.setItem("name:",name);
localStorage.setItem("email:",email);
localStorage.setItem("address:",address);
return;
 }
</script>
</head>
 <body>
 <h2>Registrtion Form</h2>
 <form action="Details.html">
<fieldset>
 <legend>Registration</legend>
<label> Name </label>
 <input type="text" id="name"/><br><br> 
<label> Email ID </label>
 <input type="email" id="email"/><br><br>
<label> Address </label>
 <input type="address" id="address"/><br><br>
<input type="submit" value="submit" onClick="passvalues()"/>
 </fieldset> 
 </form>
 </body>
</html>

