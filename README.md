# Core-Code_Eve
Core - Code Bootcamp | Eve Workspace

<h1>CONTENIDO </h1>

<h2>Week 01</h2>

[1. Pizza](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#pizza)

[2. Hot N Cold](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#hot-n-cold)

[3. Some Geometry](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#some-geometry)

[4. Numbers](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#numbers)

[5. Date of Birth](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#date-of-birth)

[6. Treasures](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#treasure)

----------------------------------------------

<h2>Week 02</h2>

[1. Logic problem](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#logic-problem)

[2. Cereal vs Milk](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#que-va-primero-el-cereal-o-la-leche)

[3. Print my name](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#print-my-name)

[4. Print my name & age](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#print-my-name--age)

[5. Algorithm game](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#algorithm-game)

[6. Mod](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#mod)

[7. Register form](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#register-form)

[8. Truth Tables](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#truth-tables)

[9. Boolean results](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#boolean-results)

[10. Identify odd and even numbers](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#identify-odd-and-even-numbers)

-------------------------------------------------

<h2>Week 03</h2>

[1. Simple Calculator](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#simple-calculator)

[2. Special Number](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#special-number)

[3. Simple calculator with Switch](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#calculator-switch)

[4. Multi Option](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#multi-option-program)

[5. Multiplication Tables](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#multiplication-tables)

[6. Simple calculator with Do While](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#simple-calculator-with-do-while)

[7. Multiplication Tables with For](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#multiplication-tables-with-for)

[8. Ascending and Descending Numbers](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#ascending-and-descending-numbers)

[9. Greetings](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#greetings)

<h2>Week 04</h2>

[1. Average Sales and Commission](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#average-sales-and-commission)

[2. Even or Odd](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#even-or-odd)

[3. Predefined functions](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#predefined-functions)

[4. Full name](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#full-name)

[5. Throw dice](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#-throw-dice-)

[6. Distance to zero](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#-distance-to-zero-)

[7. Toss coin](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#-toss-coin-)

[8. Structure of a function](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#-structure-of-a-function-)

[9. Total price](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#-total-price-)

[10. Reverse direction and size](https://github.com/ecruz1794/Core-Code_Eve/blob/main/README.md#-reverse-direction-and-size-)

----------------------------------------------

<h1>Semana 01</h1>

----------------------------------------------

<h3>Pizza</h3>

>// Declaraci??n de variables//


| Declarar Ingredientes Masa | Tama??o Pizza | Ingredientes Especiales |
| -------------------------- | ------------- |------------------------|
| Harina | Individual | Pepperonni |
| Aceite | Peque??a | Hongos |
| Agua | Grande | Albahaca |
| Levadura | Familiar | Cebolla |
| Sal | #Slides | Jam??n |
| Az??car | - | Queso|
 
>*** Crear clase pizza, est?? va a contener los ingredientes de la pizza, est?? va a heredar a las pizzas seg??n su tama??o para que contengan la cantidad especifica de ingredientes para crear la masa y agregar ingredientes ***
 
>// Ingreso de datos //
 
>*** Si el tama??o de la pizza es personalizado se va a v??lidar, se va a crear la clase pizza ajustandose a la personalizaci??n, no lo agregue porque se extender??a ***

Input int tamPizza: "Bienvenido a Pizza a su gusto. Favor ingrese el tama??o de la pizza que desea:" | Individual | Peque??a | Grande | Personalizado |

Input lista ingEspecial: "Por favor, seleccione los ingredientes que desea en su pizza:" | Pepperonni | Hongos | Albahaca | Cebolla | Jam??n | Queso |

>*** Hacer validaci??n que la cantidad de ingredientes no sean excesivos para no ablandar la masa, sino enviar mensaje y solicitar nuevamente los Ingredientes Especiales ***

Input direccion = "Favor ingrese su direcci??n"

>//Llamamiento funciones y proceso//

- Iniciar precalentado horno y molde
- Iniciar masa = creacionMasa(tamPizza)
- Iniciar pizza = crearPizza(masa, tamPizza, ingEspecial)
- Inciar pizzaHorneada = HornearPizza(pizza, tamPizza)
- Iniciar pizzaLista = cortarSlides (pizzaHorneada, tamPizza.getNumSlides())
- Print "Su pizza est?? en camino para entregar" + pizza + " en la direcci??n " + direccion 
- Hacer entrega = delivery.pizza(pizza, direccion)
- S?? entrega es igual a 1 imprimir "Entrega exitosa! Gracias por su compra, provecho!", sino imprimir "Fall?? entrega, favor comuniquese con el proveedor". 

>// Creaci??n de funciones//
>//Mezclar ingredientes y formar bola de masa, se devuelve la masa estirada//

creacionMasa(infoPizza){
 - Colocar taza
 - Poner ingredientes (Estos toman la cantidad seg??n su tama??o a partir de la clase heredada, harina, agua, aceite, levadura etc.)
 - Mezclar ingredientes
 - Amasar la masa
 - Hacer bola de masa y estirar
 - Cepillar la masa con el aceite
 - Agregar harina espolvoreada en la masa estirada
 - Dejar reposar la masa
 - Devolver masa estirada
 
}

>//Crear la pizza agregando los ingredientes especiales, desde las salsas, queso, hongos etc seg??n el usuario haya solicitado, ingredientesEspeciales es un array/lista //

crearPizza(masa, infoPizza, ingredientesEsp){
 - Tomar la masa estirada
 - Vertir ingredientes especiales, iniciando por la salsa, el queso (En caso que el usuario no solicitara alguno se omiten)
 - Agregar el resto de ingredientes especiales solicitados por el usuario seg??n la lista
 -  Regresar la pizza
 
}

>//Se va a hornear la pizza conforme la duraci??n y temperatura seg??n su clase dependiendo su tama??o, no va a ser el mismo tiempo de cocci??n para una pizza individual que para una pizza grande//

HornearPizza (pizza, tamPizza){
- Colocar la pizza en el horno precalentado
- Hornear pizza durante pizza.DuracionHorno(tamPizza) a la temperatura de pizza.Temperatura(tamPizza)
- Devolver pizza

}

>// Se va a cortar la pizza seg??n el n??mero de slides del tama??o de la pizza//

cortarSlides( pizza, numSlides){
- Cortar pizza en numSlides proporcionado
- Devolver pizza

}

>// Entrega de la pizza usando la direcci??n//

delivery.pizza(pizza, dir){
- Llevar la pizza a la direcci??n entregada en dir
- Tocar el timbre
- Devolver true si la pizza es recibida, sino false

}

-------------------------------------------------------------------

<h3>Hot N Cold</h3>

- Input opc = Buenas! Que tipo de conversi??n desea realizar:
	1. Celcius a Fahrenheit
	2. Fahrenheit a Celcius
- V??lidar que la opci??n ingresada sea correcta sino volver a solicitarlo
- Input numTemp = Ingrese el valor a convertir.
- resultado = convertirValor( opc, numTemp )
- Print "El valor " + numTemp + " convertido es de: " + resultado. 

>//Funci??n para conversi??n del valor//

convertirValor( numOpc, numTemp){

int temperatura = 0

If numOpc = 1 entonces {

-	temperatura = 	( numTemp * 9/5 ) + 32

else
-	temperatura = ( numTemp ??? 32) ?? 5/9 
	
return temperatura

}

-------------------------------------------------------------

<h3>Some Geometry</h3>

1. Solicitar el tipo de geometr??a que se desea calcular su volumen
	A. Cubo 
	B. Pir??mide 
	C. Esfera
	
2. V??lidar los datos ingresados sean v??lidos

4. Si la geometr??a es un cubo solicitar tama??o de los lados y devolver lado elevado a la 3

6. Si la geometr??a es una Pir??mide se solicita su altura, longitud de base, ancho de base y se devuelve 1/3 * longitudBase ?? anchoBase ?? altura

8. Si la geometr??a es una esfera se solicitan el radio y se devuelve (4/3)?? * radio elevado a la 3

-------------------------------------------------------------------

<h3>Numbers</h3>

>// Dise??ar algoritmo que identifique si el n??mero ingresado es par o impar

Input int num = "Ingrese el valor del n??mero que desea evaluar"

string parImpar = evaluarNum(num)

Print "El n??mero dado es" + parImpar

>// Funcion para evaluar el n??mero en par o impar //
evaluarNum(numEvaluar){

If ( numEvaluar/2 == 0 ){
-	return "Par"

else
-	return "Impar"

}

--------------------------------------------------------------------------------------

<h3>Date Of Birth</h3> 

1. dataBirth = "Ingrese el a??o de su nacimiento"
2. dataYear = "Ingrese el a??o al cual quiere averig??ar su edad"
3. edad = dataYear - dataBirth
4. Print "La edad que va a tener en el a??o " + dataYear + " es: " + edad
5. Fin

------------------------------------------------------------------------------------------

<h3>Treasure</h3> 

Estamos en una habitaci??n con tres cofres. Sabemos que al menos uno tiene un tesoro en ??l. Cada cofre tiene un mensaje, pero todos los mensajes son mentiras.

- Cofre izquierdo: El cofre del medio tiene un tesoro.
- Cofre medio: Todos estos cofres tienen tesoros en ellos
- Cofre derecho: Solo uno de estos cofres tiene tesoros.

??Qu?? cofres tienen tesoros?

R/ Hay tesoro en el cofre izquierdo y el derecho, porque el enunciado del primero da a conocer que hay un tesoro en el medio, pero este es mentira por la premisa. El cofre derecho que solo uno tiene un tesoro, al ser mentira podemos concluir que dos pueden tener tesoro y sabemos que al menos uno debe tener. Por lo tanto, solo el del medio no tiene tesoro.

-------------------------------------------------------------

<h1>Semana 02</h1>

<h3>Logic Problem</h3> 

> The teacher asks his 5 students if they studied mathematics yesterday.
> 
> Alice: "Nobody studied math yesterday".  
> Bob: "1 person studied math yesterday".  
> Charlie: "2 people studied math yesterday".  
> Dan: "3 people studied mathematics yesterday".  
> Eva: "4 people studied mathematics yesterday".
> 
> The teacher knows that only those who studied would be telling the truth and those who didn't would be lying. Who is telling the truth?

Soluci??n: Bob es qui??n esta diciendo la verdad, porque si alguno de los otros dice la verdad produce contradicci??n en las premisas y lo que cada uno esta diciendo.

<h3>Que va primero, El Cereal o la Leche?</h3>

** Soluci??n Pseudoc??digo **
```
- Inicio programa
- crear bowl
- Int firstAction = "Favor ingrese que desea primero. 1. Cereal  2. Leche"
	If( firAction == 1) {
   		1. Agregar Cereal al bowl;
		2. Agregar Leche al bowl;
	}else{
		if(firstAction == 2){
			1. Agregar leche al bowl;
			2. Agregar cereal al bowl;
		}else{
			Print "Ingreso de datos incorrecto"
			Volver a iniciar programa;
		}
	}
	return bowl;	
- Finalizar 
```
** Soluci??n Diagrama de Flujo **
![_Diagrama de flujo](https://user-images.githubusercontent.com/2061113/204888985-12099344-5758-4a64-9b69-61dbd1e6f0d8.png)

--------------------------------------------------------------

<h3>Print my name</h3>

![myName](https://user-images.githubusercontent.com/2061113/204913686-87a7804e-09fd-4e1d-a800-2d8e63fd5bde.JPG)

-----------------------------------------------------------------

<h3>Print my name & age</h3>

![image](https://user-images.githubusercontent.com/2061113/204913871-75611b05-6a5f-4e26-a736-41805117eca7.png)

-----------------------------------------------------------------

<h3>Algorithm game</h3>

![image](https://user-images.githubusercontent.com/2061113/204917754-a8d82399-22fe-4458-ae75-e3271272226c.png)

-----------------------------------------

<h3>Mod</h3>

![image](https://user-images.githubusercontent.com/2061113/204920562-0153e370-4592-4438-972b-72a4c42fa574.png)

----------------------------------------

<h3>Register form</h3>

![image](https://user-images.githubusercontent.com/2061113/204922846-040ac328-830c-4453-ab07-07fcfde32694.png)

-----------------------------------------

<h3>Truth tables</h3>

- Remember that AND can be represented by & 
- Remember that OR can be represented by | 
- Remember that NOT can be represented by ~| 

1. T & T = T ???
2. T & F = F ???
3. F & T = T ???
4. F & F = F ???
5. T | T = T ???
6. T | F = F ???
7. F | T = T ???
8. F | F = F ???
9. ~T = T ???
10. ~F = T ???
11. (T & F) | (~F) = T ???
12. (T | F ) & (F | F) = T ???
13. ~((T | F ) & (F | F)) & F = T ???
14. ~((T | F ) & (F | F)) & T = F ???

-----------------------------------------

<h3>Boolean results</h3>

```
Algoritmo boolean
	a <- 5 == 3		// output: False | Compara si '5' es igual a '3'
	b <- 4 <> 3		// output: True | Compara si '4' es diferente a '3'
	c <- 7 > 7		// output: False | Compara si '7' es mayor a '7'
	d <- 4 < 4		// output: False | Compara si '4' es menor a '4'
	e <- 100 <= 90		// output: False | Compara si '100' es menor o igual a '90'
	f <- 40 >= 40		// output: True | Compara si '40' es mayor o igual a '40'
FinAlgoritmo
```
-----------------------------------------

<h3>Identify odd and even numbers</h3>

```
Proceso IdentParImpar
	Definir num Como Entero
	Definir residuo Como Entero
	Imprimir "Bienvenido, Digite el valor a verificar:"
	Leer num
	Si num%2 == 0 Entonces
		Imprimir "El n??mero ",num," es Par."
	SiNo
		Imprimir "El n??mero ",num, " es Impar."
	Fin Si
FinProceso
```

----------------------------------------------

<h1>Semana 03</h1>

----------------------------------------------

<h3>Simple Calculator</h3>

```
Proceso calculadoraSimple
	Definir a Como Entero
	Definir b Como Entero
	Definir op Como Caracter
	Definir res Como Entero
	Imprimir "*************	 	Calculadora 	*************"
	Imprimir "Ingrese el primer n??mero: "
	Leer a
	Imprimir "Ingrese el segundo n??mero: "
	Leer b
	Imprimir "Ingrese el tipo de operaci??n a realizar +,-,*,/: "
	Leer op
	Si op == "+" Entonces
		res<-a+b
	SiNo
		Si op == "-" Entonces
			res<-a-b
		SiNo
			Si op == "*" Entonces
				res<-a*b
			SiNo
				Si op == "/" Entonces
					res<-a*b
				SiNo
					Imprimir "Operaci??n Inv??lida"
				Fin Si
			Fin Si
		Fin Si
	Fin Si
	Imprimir "El resultado de la operaci??n es: " res
FinProceso
```

-----------------------------------------

<h3>Special Number</h3>

```
Proceso specialNumber
	Definir n  Como Entero
	Imprimir "Please put the number to evaluate: "
	Leer n
	Si n == 100 Entonces
		Imprimir "This is a special number"
	SiNo
		Si (n < 1000) & (n % 10 == 0) Entonces
			Imprimir "Almost special number"
		SiNo
			Imprimir "Just a regular number"
		Fin Si
	Fin Si
FinProceso
```

-------------------------------------

<h3>Calculator Switch</h3>

```
Proceso CalculadoraSwitch
	Definir a Como Entero
	Definir b Como Entero
	Definir op Como Caracter
	Imprimir "--------- Calculator ----------"
	Imprimir "Ingrese un n??mero"
	Leer a
	Imprimir "Ingrese el segundo n??mero"
	Leer b
	Imprimir "Ingrese el tipo de operaci??n a realizar +,-,*,/: "
	Leer op
	Segun op Hacer
		"+":
			Imprimir "El resultado es " a+b
		"-":
			Imprimir "El resultado es " a-b
		"*":
			Imprimir "El resultado es " a*b
		"/":
			Imprimir "El resultado es " a/b
		De Otro Modo:
			Imprimir "Operaci??n inv??lida"
	Fin Segun
FinProceso
```

-------------------------------------

<h3>Multi Option Program</h3>

```
Proceso MultiOpc
	Definir opc Como Entero
	Definir a Como Entero
	Definir b Como Entero
	Definir var Como Caracter
	Imprimir "------------ Multi Opci??n -------------"
	Imprimir "Ingrese la opci??n que desea"
	Imprimir "1. Sumar 2 n??meros"
	Imprimir "2. Imprimir d??a de la semana"
	Imprimir "3. Calcular la longitud del texto"
	Leer opc
	Segun opc Hacer
		1:
			Imprimir "Digite el primer n??mero"
			Leer a
			Imprimir "Digite el segundo n??mero"
			leer b
			Imprimir a+b
		2:
			Imprimir "Ingrese el n??mero del d??a de la semana (1-7)"
			Leer a
			Segun a Hacer
				1:
					Imprimir "Lunes"
				2:
					Imprimir "Martes"
				3:
					Imprimir "Mi??rcoles"
				4:
					Imprimir "Jueves"
				5:
					Imprimir "Viernes"
				6:
					Imprimir "S??bado"
				7:
					Imprimir "Domingo"
				De Otro Modo:
					Imprimir "Opci??n inv??lida"
			Fin Segun
		3:
			Imprimir "Ingrese el texto"
			leer var
			Imprimir "La longitud del texto es " Longitud(var)
		De Otro Modo:
			Imprimir "Opci??n inv??lida"
	Fin Segun
FinProceso
```

-------------------------------------

<h3>Multiplication Tables</h3>

```
Proceso MultiplicationTables
	Definir tab Como Entero
	Definir i Como Entero
	Imprimir "*** Multiplication Tables ****"
	Imprimir "Ingrese la tabla que desea calcular: "
	Leer tab
	i<-1
	Mientras i <= 12 Hacer
		Imprimir " Tabla Multiplicar *** " tab " ***"
		Imprimir tab " x " i " = " tab*i
		i<-i+1
	FinMientras
FinProceso
```

-------------------------------------

<h3>Simple calculator with Do While</h3>

```
Proceso Calculadora
	Definir num1, num2 como Entero
	Definir i, op Como Caracter
	Imprimir "*** Calculadora Simple ****"
	i<-"Si"
	Mientras i = "Si" | i = "si" Hacer
		Imprimir "Favor digitar el primer valor: "
		Leer num1
		Imprimir "Favor digitar el segundo valor: "
		Leer num2
		Imprimir "Ingrese la operaci??n que desea: +, -, *, / "
		Leer op
		Segun op Hacer
			"+":
				Imprimir "Operaci??n: " num1 " + " num2 " = " num1+num2
			"-":
				Imprimir "Operaci??n: " num1 " - " num2 " = " num1-num2

			"*":
				Imprimir "Operaci??n: " num1 " * " num2 " = " num1*num2

			"/":
				Imprimir "Operaci??n: " num1 " / " num2 " = " num1/num2
			De Otro Modo:
				Imprimir "Operaci??n Inv??lida"
		Fin Segun
		Imprimir "Desea realizar otra operaci??n: Si/No"
		Leer i
	FinMientras
FinProceso
```

------------------------------------

<h3>Multiplication Tables with For</h3>

```
Proceso MultiplicationTablesFor
	Definir num, i Como Entero
	Imprimir ' ******** Tablas Multiplicar *******'
	Imprimir 'Ingrese la tabla a calcular:'
	Leer num
	Imprimir 'Tabla del ' + ConvertirATexto(num)
	Para i <- 1 Hasta 12 Con Paso 1 Hacer
		Imprimir ConvertirATexto(num) ' *  ' + ConvertirATexto(i) + ' = ' ConvertirATexto(num * i) 
	Fin Para
FinProceso
```

------------------------------------

<h3>Ascending and Descending Numbers</h3>

```
Proceso AscendingDescendingNumbers
	Definir num, n, i como Entero 
	Imprimir "********* Ascending and Descending Numbers **********"
	Imprimir "Ingrese un valor"
	Leer num
	Imprimir "Operaci??nes disponibles: "
	Imprimir "1. Imprimir en orden ascendente"
	Imprimir "2. Imprimir en orden descendente"
	Imprimir "Digite la operaci??n correspondiente"
	Leer i
	Segun i Hacer
		1:
			Para n <- 0 Hasta num Con Paso 1 Hacer
				Imprimir n
			Fin Para
		2:
			Para n <- 0 Hasta num Con Paso 1 Hacer
				Imprimir num-n
			Fin Para
		De Otro Modo:
			Imprimir "Operaci??n ingresada inv??lida"
	Fin Segun
FinProceso
```

------------------------------------

<h3>Greetings</h3>

```
Proceso Saludos
	Imprimir "******** Saludos ********"
		Definir continue Como Cadena
		Definir saludo, hora Como Entero
		saludo <- 0
		continue <- "Si"
		Mientras continue == "Si" | continue == "si" Hacer
			Imprimir "Ingrese la hora (0-23):"
			Leer hora
			Si hora <= 12 Entonces
				Imprimir "Buenas d??as!, Es temprano"
			SiNo 
				Si hora <= 18 Entonces
					Imprimir 'Buenas tardes!, Ya casi anochese'
				SiNo
					Imprimir 'Buenas noches!, Ya se ocult?? el sol'
				Fin Si
			Fin Si
			
			saludo <- saludo + 1
			Imprimir 'Desea continuar ? Si/No'
			Leer continue
		Fin Mientras
		Imprimir 'Conteo total de saludos: ' + ConvertirATexto(saludo)
FinProceso
```

----------------------------------------------

<h1>Semana 04</h1>

----------------------------------------------

<h3>Average Sales and Commission</h3>

```
Proceso SalesCommission
	Definir numV, venta, ventaTotal, i Como Entero
	Definir promedioVenta Como Real
	Imprimir "****** Calculadora Ventas ******"
	Imprimir "Ingrese el n??mero de ventas: "
	Leer numV
	ventaTotal = 0
	Para i<-1 Hasta numV Con Paso 1 Hacer
		Imprimir "Ingrese el costo de la venta n??mero " + ConvertirATexto(i)
		Leer venta
		ventaTotal<-ventaTotal+venta
	Fin Para
	promedioVenta <- ventaTotal/numV
	Imprimir "Venta total es de: " ventaTotal
	Imprimir "Promedio de venta es: " promedioVenta
	Si numV>5 Entonces
		Imprimir "Comisi??n recibida es de: " ventaTotal*0.15
	SiNo
		Imprimir "Comisi??n recibida es de: " ventaTotal*0.10
	Fin Si
FinProceso
```

------------------------------------

<h3>Even or Odd</h3>

```
Proceso EvenOddNumber
	Definir num, i Como Entero
	Definir nPar Como Real
	Repetir
			Imprimir "Ingrese el n??mero a evaluar: "
			Leer  num
			Si num < 1  | num > 50 Entonces
				Imprimir "Valor inv??lido"
			Fin Si
	Hasta Que num > 1  | num < 50
	
	nPar <- num%2
	Si nPar == 0 Entonces
		Para i<-1 Hasta num Con Paso 1 Hacer
			Si i%2 == 0 Entonces
				Imprimir i
			Fin Si
		Fin Para
	SiNo
		Para i<-1 Hasta num Con Paso 1 Hacer
			Si i%2 <> 0 Entonces
				Imprimir i
			Fin Si
		Fin Para
	Fin Si
FinProceso
```

------------------------------------------------

<h3>Predefined functions</h3>

```
Estudio de las funciones predefinidas en PSeint, como longitud() calor absoluto entre otras.

```

----------------------------------------------

<h3>Full name</h3>

```
Proceso NombreCompleto
	Definir nombre, apellido, nCorregido, aCorregido Como Caracter
	Escribir "Nombre:"
	leer nombre
	Escribir "Apellido:"
	leer apellido
	nCorregido = Mayusculas(Subcadena(nombre,0,0)) + Minusculas(Subcadena(nombre,1,Longitud(nombre)-1))
	aCorregido = Mayusculas(Subcadena(apellido,0,0)) + Minusculas(Subcadena(apellido,1,Longitud(apellido)-1))
	Imprimir nCorregido + " " + aCorregido
FinProceso
```

----------------------------------------------

<h3> Throw dice </h3>

```
Algoritmo AleatorioDados
	Definir dado1, dado2, i Como Entero
	Para i = 1 Hasta 10 Con Paso 1 Hacer
		dado1 = Aleatorio(1,6)
		dado2 = Aleatorio(1,6)
		SI dado1 = dado2 Entonces
			Imprimir "Dado 1 " + ConvertirATexto(dado1) + " Dado 2: " + ConvertirATexto(dado2) + " Son iguales"
		SiNo
			Imprimir "Dado 1 " + ConvertirATexto(dado1) + " Dado 2: " + ConvertirATexto(dado2)
		FinSi
	FinPara
FinAlgoritmo
```

----------------------------------------------

<h3> Distance to zero </h3>

```
Algoritmo lejanoCero
	Definir masGrande, i, num Como Real
	Escribir "Ingrese un valor"
	leer masGrande
	Para i=1 Hasta 4 Con Paso 1 Hacer
		Escribir "Ingrese un valor"
		leer num
		SI Abs(num) > Abs(masGrande) Entonces
			masGrande = num
		FinSi
	FinPara
	Imprimir "El valor m??s lejano a 0 ingresado es: " + ConvertirATexto(Trunc(masGrande))
FinAlgoritmo
```



----------------------------------------------

<h3> Toss coin </h3>

```
Algoritmo azarDinero
	Definir jugador1, jugador2 Como Caracter
	Definir cantidad1, cantidad2 Como Real
	Imprimir "Ingrese el primer jugador: "
	leer jugador1
	Imprimir "Ingrese la cantidad que va a usar el primer jugador:"
	leer cantidad1
	Imprimir  "Ingrese el segundo jugador: "
	leer jugador2
	Imprimir "Ingrese la cantidad que va a usar el segundo jugador:"
	leer cantidad2
	
	SI cantidad1<=0 | cantidad2 <=0 Entonces
		SI cantidad1<=0 & cantidad2 <=0 Entonces
			Imprimir "Valores ingresados por ambos jugadores es inv??lido,se cancela el juego"
		SiNo
			SI cantidad1<=0 Entonces
				Imprimir "Monto Ingresado por el jugador " + jugador1 + " Es inv??lido, gana autom??ticamente: " + Mayusculas(jugador2) + " 0."
			SiNo
				Imprimir "Monto Ingresado por el jugador " + jugador2 + " Es inv??lido, gana autom??ticamente: " + Mayusculas(jugador1) + " 0."
			FinSi
		FinSi
	SiNo
		SI Aleatorio(1,2) = 1 Entonces
			Imprimir "Gana el jugador " + Mayusculas(jugador1) + " la cantidad: " + ConvertirATexto(cantidad2)
		SiNo
			Imprimir "Gana el jugador " + Mayusculas(jugador2) + " la cantidad: " + ConvertirATexto(cantidad1)
		FinSi
	FinSi
FinAlgoritmo
```

----------------------------------------------

<h3> Structure of a function </h3>

```
Se estudi?? las formas y estructuras de la funciones, como ingresan variables y sus retornos, llamados, etc.
```

----------------------------------------------

<h3> Total price </h3>

```


```

----------------------------------------------

<h3> Reverse direction and size </h3>

```


```

----------------------------------------------

<h3> </h3>

```


```

----------------------------------------------

<h3> </h3>

```


```
