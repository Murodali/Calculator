<HTML>
<html>
<head>
<script type="text/javascript">
function displaynum(n1)
{
calcform.txt1.value=calcform.txt1.value+n1;
}
</script>
</head>
<body>
<h1> Murodali </h1>
<form name=calcform>
<input type=text name=txt1 style="text-align:right"><br>
<input type=button name=btn9 value=9 onclick="displaynum(btn9.value)">
<input type=button name=btn8 value=8 onclick="displaynum(btn8.value)">
<input type=button name=btn7 value=7 onclick="displaynum(btn7.value)">
<input type=button name=addbtn value=+ onclick="displaynum(addbtn.value)"><br>
<input type=button name=btn6 value=6 onclick="displaynum(btn6.value)">
<input type=button name=btn5 value=5 onclick="displaynum(btn5.value)">
<input type=button name=btn4 value=4 onclick="displaynum(btn4.value)">
<input type=button name=subbtn value=- onclick="displaynum(subbtn.value)"><br>
<input type=button name=btn3 value=3 onclick="displaynum(btn3.value)">
<input type=button name=btn2 value=2 onclick="displaynum(btn2.value)">
<input type=button name=btn1 value=1 onclick="displaynum(btn1.value)">
<input type=button name=btnmul value=* onclick="displaynum(btnmul.value)"><br>
<input type=button name=btn0 value=0 onclick="displaynum(btn0.value)">
<input type=button name=potbtn value=. onclick="displaynum(potbtn.value)">
<input type=button name=eqlbtn value== onclick="txt1.value=eval(txt1.value)">
<input type=button name=divbtn value=/ onclick="displaynum(divbtn.value)"><br>
</body>
</html>
