<!DOCTYPE html>
<html>
<head>
	<title>Examen Melany</title>

<link rel="stylesheet" type="text/css" href="dcss/sol.css">
	<script>
		function compruebeclave(){
			clave1 = document.f1.clave1.value
			clave2 = document.f1.clave2.value
			if (clave1== "melany" && clave2== "guerra"){
				alert("Los datos son correctos...\n Welcome");
				var href= "pagina.html";
				window.location=href;
			}
			else{
				alert("Los datos son erroneos...\n intente de nuevo.");
				var href = "examen.html";
			};
		}
	</script>
</head>

<body background="imagen/tabla.jpg">

<h1><b><tt><center><span id="mainPoint1">INGRESE CONTRASEÑA Y SU REPETICIÓN</span></center></tt></b></h1><br>
<hr>
<p>para poder ingresar a nuestra página ingrese la contraseña dos veces para verificar si son iguales</p>
<br>

<form action="" name="f1">
	contraseña:<br> <input type="password" name="clave1" size="20">
	<br>
	repite contraseña:<br> <input type="password" name="clave2" size="20">
	<br>
	<input type="button" value="verificar" onclick="compruebeclave()">
</form>
</body>
</html>
