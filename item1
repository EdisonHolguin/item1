item1
=====
<htlm>
<head> <title>DEBER DE WEB</title>
</head>
<body  text = white background ="assassins creed ac brotherhood logo trademark symbol wallpaper background ubisoft action.jpg">
 <form></p>
<center> 
 </p>
 
 <td>
 
 <center><h1>VALIDACION BINARIA<h1></center>
 <center> <input type="text"   name="nota1"   onChange = "validar(this.value)" > 
  <input type ="button" style="background:white" value="Validar" onClick="resultado()" > </center> 
</form>
</body>
<script type="text/JavaScript">
/* funcion de validacion binaria */

     function validar(x){
         a=0
         y= x.length
     for(i=0; i<y; i++){
         z= x.substring(i,i+1);
         if((z=="0") || (z=="1" ) ){
             a=a+1
                                    }  
                        }  
            if (a == y){

              alert("si es binario")}
                    else{
                  alert("No es binario")
                         } 

                             }     
							 
						 
 </script>
 

 <html>

<head>

<title>Números primos</title>
<SCRIPT LANGUAGE="JavaScript">
/* funcion de validacion de primos */
function esprimo(primos) {
with(Math) num=eval(primos.numero.value);
divi=-1;
primo=1;
num2=parseInt(num);
if (num != num2) {
primos.resultado.value=(num + " ingrese un valor correcto.");
divi=0;
}
if (isNaN(num) || num < 1) {
primos.resultado.value=(num + "ingrese un valor correcto.");
divi=0;
}
if (num == 1) {
primos.resultado.value=(num + " no es ni primo ni compuesto.");
divi=0;
}
if (num == 2 || num == 3 || num == 5 || num == 7) {
primos.resultado.value=(num + " es primo.");
divi=0;
}
if (num%2 == 0 && num>2) {
divi=1;
primo=0;
primos.resultado.value=(num + " no es primo. Es divisible por 2.");
}
if (divi == -1) {
tope=Math.pow(num,0.5);
for (var i=3;i<=tope;i=i+2) {
if (num % i == 0) {
var primo=0;
primos.resultado.value=(num + " es divisible por " + i + ". No es primo.");
break;
}
}
if (primo == 1) {
primos.resultado.value=(num + " es primo.");
divi=(i-1)/2;
}
else divi=(i+1)/2;
}
primos.divisiones.value = " "+divi;
} 

</SCRIPT>
</head>

<body>

<center>
<form name="primos">
<h1>MOSTRAR PRIMO</h1> 
        <p><font size="4">introducir numero</font>:&nbsp;
          <input type=text name=numero >  </p>  
<input type=button value="Comprobar si es primo" onClick="esprimo(this.form)">     
        <p>resultado:<input type="text" name="resultado" size="45"</br>
		</center>
</body>
</html>
<html>
	<head>
		<center>
		<h1>Validacion de cedulas</h1></p>
	</head>

	<body>
	<input type="text" id="textocedula" ></p>
	<input type="button" value="Validar Cedula" onClick="validarcedula()">
	</body>
		</center>
		

</html>

<script type="text/javascript">
function validarcedula()
{
	var i;
	var cedula;
	var contenedor;
	cedula=document.getElementById('textocedula').value;
	var instancia;
	contenedor=0;
	for (i=1;i<=9;i++)
	{
		if (i%2!=0)
		{
			instancia=cedula.substring(i-1,i)*2;
			if (instancia>9) instancia-=9;
		}
		else instancia=cedula.substring(i-1,i);
		contenedor+=parseInt(instancia);
	}
	while (contenedor>0)
		contenedor-=10;
	if (cedula.substring(9,10)!=(contenedor*-1))
	{
		alert("Cedula no valida!!");
	}
	else
	{
		alert("Cedula Correcta");
	}
}
</script>
