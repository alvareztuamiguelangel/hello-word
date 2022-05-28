# pagina1.php

<?php 

session_start();

$_SESSION['nombre']="Miguel";
$_SESSION['apellido']="alvarez";

echo "<a href='pagina2.html'>ir a pagina 2</a>";

pagina2.html
<html>
    <head></head>
    <body>
        Se almacenaron dos variables de sesion<br>
        <a href="pagina3.php">ir a pagina 3</a>
    </body>
</html>

pagina3.php

<?php
session_start();

$nom=$_SESSION['nombre'];
$ape=$_SESSION['apellido'];

echo "variables de sesion:<br>";
echo "el nombre es : $nom<br> El apellido es : $ape<br>";

?>
