# pagina.1php

<?php 

session_start();

$_SESSION['nombre']="Miguel";
$_SESSION['apellido']="alvarez";

echo "<a href='pagina2.html'>ir a pagina 2</a>";
