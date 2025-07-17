<!Doctype html>
<html lang ="en">
<head>
<meta charset ="UTF -8">
<title> Event Registration form ,/title>
<style>
body 
{
font -Family: arial,sans -serif;
background: #f2f2f2;
display :flex;
justify-content:center;
padding:50 px;
}
from
{
background: white;
padding : 20px30px;
box-shadow:0010px rgba (0,0,0,0,1);
width: 300px;
}
input,select,textarea 
{
width:100%
padding: 10px;
margin-top:10px;
margin-button:15px;
border: 1px solid #ccc;
border - radius; 5px;
}
button
{
background:#UCAF50;
color:white;
padding :10px;
border : none;
border - radius : 5px;
Cursor:pointer;
width:100%;
}
button : hover
{
background :#459049;
}
h2
{
text-aligh:center;
}
text-aligh:center;
}
</style>
</head>
<body>
<form action ="/submit" method ="POST">
<h2>Event REgistration</h2>
<laber for ="name"> full name </label>
<input type ="text" id="name" name="name" required>
<laber for ="email"> email address </label>
<input type ="email" id="email" name="email" required>
<laber for ="phone"> phone number </label>
<input type ="tel" id="phone" name="phone" required>
<laber for ="event"> choose event </label>
<select id ="event" name ="event">
<option value ="coding"> coding context </option>
<option value ="debate"> debate </option>
<option value ="music"> music show </option>
</select>
<button type ="submit"> Register </button>
</form>
</body>
</html>

