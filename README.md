
1)
<form name='form' method='post' action=' '>
digite um valor <br>
<input type='number' name='valor' /><br>
digite um valor <br>
<input type='number' name='valor1' />
<br>
<input type="submit" value="enviar" />
</form>

<?php
$valor = $_POST['valor'];
$valor1 = $_POST['valor1'];

$soma = $valor+$valor1;

if($soma>20){
$resp = $soma+8;
echo $resp ;

}else if($soma<=20){
$resp = $soma-5;
echo $resp ;

}
?>

===================================================

2)
<form name='form' method='post' action=' '>
digite um valor <br>
<input type='number' name='valor' /><br>
<br>
<input type="submit" value="enviar" />
</form>

<?php
$valor = $_POST['valor'];

if($valor % 10 == 0){
echo "o valor e divisivel por 10";
}else if($valor % 5 == 0){
echo "o valor e divisivel por 5";
}else if($valor % 2 == 0){
echo "o valor e divisivel por 2";
}else{
echo "O valor nao e divisivel por 10, 5, 2";
}
?>

==================================================

3) pequeno erro 

<form name='form' method='post' action=' '>
digite seu nome<br>
<input type="text" name="nome" /><br>
digite sua idade <br>
<input type='number' name='valor' /><br>
masculino
<input type='radio' name="sexo" value="Masculino"><br>
feminino
<input type=radio name="sexo" value="Feminino">


<br>
<input type="submit" value="enviar" />
</form>

<?php
$valor = $_POST['valor'];
$nome = $POST['nome'];
$sexo = $POST['sexo'];

if ($sexo == feminino && idade < 25){
echo "Aceita";
}else {
echo "Nao aceita";
}
?> 

==================================================

4)

<form name='form' method='post' action=' '>
digite tres valores  <br>
primeiro valor  <br>
<input type='number' name='valor' /><br>
segundo valor  <br>
<input type='number' name='valorum' /><br>
terceiro valor  <br>
<input type='number' name='valordois' /><br>
<input type="submit" value="enviar" />
</form>

<?php
$valor = $_POST['valor'];
$valorum = $_POST['valorum'];
$valordois = $_POST['valordois'];

echo "$valordois <br>";
echo "$valorum <br>";
echo "$valor <br> ";
?>
===================================================
5)
<form name='form' method='post' action=' '>
digite tres valores  <br>
primeiro valor  <br>
<input type='number' name='valor' /><br>
segundo valor  <br>
<input type='number' name='valorum' /><br>
terceiro valor  <br>
<input type='number' name='valordois' /><br>
<input type="submit" value="enviar" />
</form>

<?php
$valor = $_POST['valor'];
$valorum = $_POST['valorum'];
$valordois = $_POST['valordois'];

if (valor == valorum && valorum == valordois){
echo "triangulo equilatero";
}
?>
