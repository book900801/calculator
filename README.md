<!DOCTYPE html>
<html lang="en">
<style type="text/css">
button{
	width:80px;font-weight:bold;font-size:48px;font-family:"Times New Roman";
}


</style>
<script type="text/javascrip">

</script>
<head>
<meta charset="UTF-8">
<title>計算機</title>
<script type="text/javascript">
var x = "";
var y = "";
var z = "";
function zero(){
	var print = window.document.getElementById("table1")
	if(x!=0){
		x = x+"0"
	}else{
		x = x
	}
	print.innerHTML=x
}
function one(){
	var print = window.document.getElementById("table1")
	x = x+"1"
	print.innerHTML=x
	}
	function two(){
	var print = window.document.getElementById("table1")
	x = x+"2"
	print.innerHTML=x
}
function three(){
	var print = window.document.getElementById("table1")
	x = x+"3"
	print.innerHTML=x
	}
	function four(){
	var print = window.document.getElementById("table1")
	x = x+"4"
	print.innerHTML=x
}
function five(){
	var print = window.document.getElementById("table1")
	x = x+"5"
	print.innerHTML=x
	}
	function six(){
	var print = window.document.getElementById("table1")
	x = x+"6"
	print.innerHTML=x
}
function seven(){
	var print = window.document.getElementById("table1")
	x = x+"7"
	print.innerHTML=x
	}
	function eight(){
	var print = window.document.getElementById("table1")
	x = x+"8"
	print.innerHTML=x
}
function nine(){
	var print = window.document.getElementById("table1")
	x = x+"9"
	print.innerHTML=x
}

function add(){
	var print = window.document.getElementById("table1")
	print.innerHTML=""
	z = "+"
	y = x
	x = ""
}
function sub(){
	var print = window.document.getElementById("table1")
	print.innerHTML=""
	z = "-"
	y = x
	x = ""
}
function mul(){
	var print = window.document.getElementById("table1")
	print.innerHTML=""
	z = "*"
	y = x
	x = ""
}
function div(){
	var print = window.document.getElementById("table1")
	print.innerHTML=""
	z = "/"
	y = x
	x = ""
}
function ac(){
	var print = window.document.getElementById("table1")
	print.innerHTML=""
	x =""
	y =""
	z =""
}
function equal(){
	var print = window.document.getElementById("table1")
	y = Number(y)
	x = Number(x)
	if(z=="+"){
		print.innerHTML=y+x
		x = y+x
	}	
	if(z=="-"){
		print.innerHTML=y-x
		x = y-x
	}
	if(z=="*"){
		print.innerHTML=y*x
		x = y*x
	}
	if(z=="/"){
		print.innerHTML=y/x
		x = y/x
	}
}

</script>
</head>
<body>
	<table border = "1">
		<tr>
			<td style = width:329px;padding:5px;font-size:56px;height:70px><span id="table1"></span></td>
		</tr>
	</table>
	<table border = "1">
		<tr>
			<td><button onclick="seven();">7</button></td>
			<td><button onclick="eight();">8</button></td>
			<td><button onclick="nine();">9</button></td>
			<td><button onclick="add();">+</button></td>
		</tr>
		<tr>
			<td><button onclick="four();">4</button></td>
			<td><button onclick="five();">5</button></td>
			<td><button onclick="six();">6</button></td>
			<td><button onclick="sub();">-</button></td>
		</tr>
		<tr>
			<td><button onclick="one()">1</button></td>
			<td><button onclick="two();">2</button></td>
			<td><button onclick="three();">3</button></td>
			<td><button onclick="mul()">*</button></td>
		</tr>
		<tr>
			<td><button onclick="zero();">0</button></td>
			<td><button onclick="ac();">ac</button></td>
			<td><button onclick="equal();">=</button></td>
			<td><button onclick="div();">/</button></td>
		</tr>
	</table>
</body>
</html>
