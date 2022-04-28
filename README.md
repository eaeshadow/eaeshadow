**<?php 
$nome=$_POST ["nome "]
$genero=$_POST ["genero "]
$estado =$_POST ["estado "]

  echo "seu nome é $nome ";
  echo "<br>";
  echo "<br>";
 
     echo "seu genero é $genero";
     echo "<br>";
     echo "<br>";

        echo "seu estado civil é $estado";
        echo "<br>";
        echo "<br>";

if  (isset($_POST["esporte"])) {
    for ($i= 0; $i < count($_POST["esporte"]); $i ++)
     echo "você pratica:". $_POST ["esporte"] [$i]. "como esportes";
      echo "<br>"   
}
else 
{
   echo "$nome, não prqatica nenhum esporte"; 
}**
