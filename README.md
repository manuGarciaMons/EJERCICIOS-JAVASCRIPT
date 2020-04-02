# EJERCICIOS-JAVASCRIPT

# Objetivo: Permitir realizar tareas mucho más sorprendentes conociendo los fundamentos de los objetos, funciones, métodos, y eventos en JavaScript.

# Conceptos Previos:	
1.	Conceptos de Programación Orientada a Objetos
2.	Conceptos sobre funciones
3.	Conceptos sobre Métodos

## 1. Ejercicios sobre funciones:
1.1- Diseñar una función a la cual le envíe tres enteros y retorne el mayor de ellos. 

1.2- Elaborar una función a la cual le envíe el valor del lado de un cuadrado y me retorne su perímetro. 

1.3 - Desarrollar una función que retorne la cantidad de dígitos que tiene una variable entera positiva. 

1.4 - Elaborar una función que reciba tres enteros y retorne el promedio. 

1.5 - Diseñar una función que solicite la captura de 5 valores por teclado y retorne su suma.

# 2. Ejercicios sobre la clase String
2.1– Ingresar una serie de nombres por teclado hasta que se digite la palabra Fin, y mostrar cuántos nombres se ingresaron.
2.2– Igual al anterior, pero que termine la aplicación sin contemplar mayúsculas ni minúsculas. Es decir que para salir se pueda teclear fin, Fin o FIN. 
2.3 – Realizar la búsqueda de un string clave en un string fuente. Se deberá ingresar una frase o texto (fuente) y luego la clave a buscar. En caso de encontrarla, imprimir la posición, de lo contrario una leyenda.
2.4 – Ingresar una palabra o texto por teclado y determinar si es o no una palabra palíndromo. (Palabra que se lee de igual manera de adelante hacia atrás, que de atrás hacia delante). 
2.5 – Realizar un programa que permita capturar una dirección de mail e implementar una función que verifique si el String tiene cargado el caracter @. 
2.6 - Capturar un String por teclado e implementar los siguientes métodos:
a) Imprimir la primera mitad de los caracteres de la cadena.
b) Imprimir el último caracter.
c) Imprimirlo en forma inversa.
d) Imprimir cada caracter del String separado con un guión.
e) Imprimir la cantidad de vocales almacenadas.
2.7 – Codifique un programa que permita capturar una oración por teclado, luego mostrar cada palabra ingresada en una línea distinta.
Por ejemplo si cargo:
La mañana está fría.
Debe aparecer:
La
mañana
está
fría.


# 3.	Ejercicios sobre formularios y eventos
3.1	Crear un formulario con tres botones con las leyendas "1", "2" y "3". Mostrar un mensaje indicando qué botón se presionó. 

# 4.	Ejercicios sobre controles FORM, BUTTON Y TEXT
4.1 - Crear un programa que permita capturar un entero en un text y al presionar un botón nos muestre dicho valor elevado al cubo (emplear la función alert).

4.2 - Capturar dos números en objetos de tipo text y al presionar un botón, mostrar el mayor.

4.3 - Capturar un nombre y un apellido en dos text. Al presionar un botón, concatenarlos y mostrarlos en un tercer text (Tener en cuenta que podemos modificar la propiedad value de un objeto TEXT cuando ocurre un evento).
# 5.	Ejercicios sobre el control PASSWORD
5.1 - Disponer dos campos de texto tipo password. Cuando se presione un botón mostrar si las dos claves ingresadas son iguales o no (es muy común solicitar al operador el ingreso de dos veces de su clave para validar si la tecleó correctamente, esto se hace cuando se crea una password para el ingreso a un sitio o para el cambio de una existente). Tener en cuenta que podemos emplear el operador == para ver si dos string son iguales.
5.2- Solicitar que se ingrese el nombre y la clave de un usuario. Mostrar una ventana de alerta si en la clave se ingresan menos de 7 caracteres o más de 20.

# 6.	Eventos onMouseOver y onMouseOut 

De acuerdo a la guía en el numeral sobre Eventos, tomar como referencia el ejemplo y modificar el segundo problema resuelto (las casillas de la tabla que cambian el color cuando ingresamos con el mouse) para permitir llamar mediante hipervínculos a distintos programas que administran Web-mail (gmail, hotmail y yahoo).

# 7.	Evento OnLoad
7.1	Diseñar una función que mueva la ventana a la coordenada (20,20) cuando se cargue la página (la función que desplaza la ventana del navegador a una determinada coordenada se llama moveTo y tiene dos parámetros que indican la columna y la fila en pixeles.

# 8.	El Objeto Window
8.1	Diseñar una página que permita abrir otra ventana cuando se presiona un botón. Dicha ventana debe tener como ancho 600 pixeles y alto 300 pixeles, y debe mostrar el menú y su barra de herramientas.

# 9.	Propiedad location del objeto Windows 

9.1	Diseñar una página que tenga un hipervínculo. Cuando se presione dicho hipervínculo generar un valor aleatorio entre 0 y 2. Si se genera el 0 llamar al webmail de hotmail, si se genera un 1 llamar a gmail en caso de generarse un 2 llamar a yahoo.
Para generar un valor aleatorio utilizar la función random del objeto Math.



# 10.	Propiedad history del objeto Windows 
10.1-	Diseñar tres páginas. Disponer tres hipervínculos, uno en cada página. Configurar el primer hipervínculo con la dirección de la segunda página, el hipervínculo de la segunda página debe cargar la tercera página y por último, la tercera página debe retroceder a la primera página mediante el método go del objeto history (pasándole un número negativo como parámetro).

# 11.	Propiedad screen del objeto Windows 
11.1 - Diseñar un programa que agrande el tamaño de la ventana del navegador y ocupe toda la pantalla.
Ayuda: Diseñar una función que se dispare para el evento onLoad de la marca Body: 
<body onLoad="redimensionar()">
La función redimensionar debe llamar a la función resizeTo del objeto window: 
window.resizeTo(640,480);
Si ejecutamos esto, el tamaño de la ventana del navegador se redimensionará tomando como ancho el valor 640 y como alto 480.

11.2 - Diseñar un programa que cuando muestre la página, redimensione la ventana del navegador y la centre en la pantalla dejando 50 pixeles arriba, abajo, izquierda y derecha.
Aca también tenemos que utilizar otra función del objeto window llamada moveTo (desplaza la ventana del navegador a una determinada fila y columna de la pantalla): 
function redimensionar()
  {
  window.moveTo(50,50);
  window.resizeTo(window.screen.width - ? ,window.screen.height - ?);
}
Qué valor debemos disponer en los signos de interrogación ? 


