<html>
<head>
<body background="https://th.bing.com/th/id/OIP.eHq3x7HcUgitlALHD2HalAHaHa?w=155&h=180&c=7&r=0&o=5&pid=1.7">
<title>Validar si la contraseña y la repetición de la contraseña son iguales</title>
<link rel="stylesheet" href="estilo.css">
<script>
   function comprobarClave(){
    clave1 = document.f1.clave1.value
    clave2 = document.f1.clave2.value
     
    if (clave1 == "admin" && clave2 == "conejo"){
       alert("Los Datos Coinciden...\n Bienvenido");
        var href =  "principal.html";
        window.location=href;
         }
       
    else{
       alert("Las dos claves son distintas...\nIntentelo nuevamente.");
        var href ="index.html";
        window.location=href;
    };
       
}  
</script>
</head>
<hr color="pink">
<h1>Bienvenido a tu contraseña</h1>
<p>para poder ingresar necesitas colocar tu contraseña correctamente.</p>
</hr>
<form action="" name="f1">
Contraseña:<input type="password" name="clave1" size="20">
<br>
Repite contraseña:<input type="password" name="clave2" size="20">
<br>
<input type="button" value="Comprobar si son iguales" onClick="comprobarClave()">
<hr color="blue">
<center><img src="cochinito.jpg" height="200px" width="200px"></center>
</form>
</body>
</html>
