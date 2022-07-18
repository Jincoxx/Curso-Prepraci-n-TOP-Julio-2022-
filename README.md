# Curso-Prepraci-n-TOP-Julio-2022-
ejersicios preparatorios desde el Día 1 al Día 5 de make it real

Ejercicio 1
Evaluar las expresiones, guardar su valor en una variable y mostrar el resultado

// Se debe guardar la expresion en una variable llamada operation
(13 - 27 ) * 43 - 12 * 8 + (78 - 56) - (-338 * 2)
// Se debe guardar la expresion en una variable llamada secondOperation
23 + 5 * (2 - 3) > 5 * 10 y T o F o 10 mayor o igual a 3

Ejercicio 2

Teniendo en cuenta que se tiene claro cómo definir/asignar una variable; imprima en consola como devolver su tipo para el caso de una cadena de texto, valor numérico y booleano (valor primitivo).

Ejercicio 3

Crear una función llamada isAlive que reciba dos argumentos llamados playerName y points

isAlive debe retornar verdadero si playerName es igual a "ikk" y points es mayor a 30, o si playerName es igual a "gut" y points es mayor a 10. De lo contrario, debe retornar falso.

isAlive("ikk", 50) //=> true
isAlive("gut", 50) //=> true
isAlive("ikk", 20) //=> false
isAlive("gut", 5) //=> false
isAlive("trek", 50) //=> false

Ejercicio 4

Escribir una función llamada factorial que retorne el factorial de un número, que es la multiplicación de los números (positivos) menores o iguales a ese número.

Por ejemplo, el factorial de 5 (se escribe 5!) es 120:

factorial(0) // => 1
factorial(1) // => 1
factorial(3) // => 6
factorial(5) // => 120

Ejercicio 5

Crear una función longitud que encuentre la longitud de una cadena (string)

longitud("") //=> 0
longitud("Hola") //=> 4
longitud("You Rock") //=> 8 (contando el espacio)

Ejercicio 6

Crear una función getBMI que le pida al usuario su peso y su altura para calcular su BMI e imprima la frase "Tu BMI es X". P.D BMI por sus siglas en inglés, es un valor que determina la cantidad de grasa de una persona y se calcula con peso / altura^2

getBMI(65, 1.8) // => "Tu BMI es 20.061728395061728"

Ejercicio 7

Crear una función sum que devuelva la suma de todos sus argumentos

sum(1, 2, 3) // => 6
sum(8, 2) // => 10
sum(1, 2, 3, 4, 5) // => 15

Ejercicio 8

El siguiente código no funciona de manera correcta, intente encontrar el error

function multiply(a, b){
  a * b
}

multiply(2, 2) // => 4

Ejercicio 9

Escriba la definición de la función "say" usando el siguiente formato(Debe retornar el string "Hello World"):

say("Hello")("World") // => "Hello World"

Ejercicio 10

Crear una función llamada order que reciba dos argumentos, el primero será un arreglo de números y el segundo un booleano que llamaremos reverse que es opcional.

Si el valor de reverse es verdadero la función debe retornar el arreglo de mayor a menor, de lo contrario lo deberá organizar de menor a mayor

order([1, 2, 3], true) //=> [3, 2, 1]
order([5, 2, 1, 3, 4]) //=> [1, 2, 3, 4, 5]

Ejercicio 11

Crea una función llamada max que reciba un arreglo de números como argumento y retorne el número mayor.

Nota: No utilices el método Math.max de JavaScript.

max([1, 2, 3, 4]) // => 4
max([63, 85, 39, 24, 3]) // => 85

Ejercicio 12

Escribir una función pattern que genere el siguiente patron hasta n numero de filas. Si el argumento es 0 o es un numero negativo entonces debe devolver un string vacío e.g ""

pattern(4)

1234
234
34
4
pattern(6)

123456
23456
3456
456
56
6
Nota: no hay espacios en blanco y puedes usar \n en la cadena de texto para saltar a la siguiente linea

Ejercicio 13

Crear una función transformToString que convierta un numero a cadena de texto

transformToString(123) // => "123"
transformToString(999) // => "999"

Ejercicio 14

Escribe una funcion llamada palindrome que recibe una cadena de texto. Determina si la cadena es palindrome considerando sólo caracteres alphanuméricos e ignorando si es mayúscula o minúscula.

palindrome("Atar a la rata") // => true
palindrome("vamos makers!") // => false

Ejercicio 15

Para este ejercicio vas a crear un método llamado flatten el cual va a recibir cualquier tipo de argumento (string, numero, array) y debe devolver todos los parámetros en un arreglo simple Nota: Cualquier matriz anidada sin importar su profundidad debe ser simplificada para poder devolver un arreglo simple

flatten(1, [2, 3], 4, 5, [6, [7]]) // => [1, 2, 3, 4, 5, 6, 7]
flatten('a', ['b', 2], 3, null, [[4], ['c']]) // = > // returns ['a', 'b', 2, 3, null, 4, 'c']
