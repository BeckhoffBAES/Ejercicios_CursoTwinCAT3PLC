

## 4. Tipos de POU y lenguajes de PLC ##
### Cuestionario ###
1. ¿Qué 7 tipos de lenguajes permite el estándar IEC 61131-3?
2. ¿Qué 3 tipos de POU existen?
3. ¿Un programa (PRG) tiene instancias?
4. ¿Un function block (FB) puede llamar un programa?
5. ¿Un FB puede llamar otro FB?
6. ¿Un PRG puede llamar otro PRG?
7. ¿Qué tipo de POU puede llamar una tarea?
8. ¿Una función, hay que definir antes de ser llamada?
9. ¿Con que tipo de POU sería la mejor forma de programar un contador?
10.	¿Para usar un FB hay que definirlo previamente?
11.	¿Con que tipo de POU sería la mejor forma de programar un escalado?

### Práctico ###
*** 
**Programas (PRG)**
1.	Crea 2 POU's tipo programa con un contador ascendente en cada ciclo de PLC en cada uno implementado en ST. 
2.	Llama a todos los programas anteriores desde el programa MAIN.
3.	Haz uso de las regiones (region) por tabulación y por pragma. 

***
**Function Blocks (FB)**
1. Crea un FB contador en ST de valores enteros positivos y negativos que pueda contador hasta un máximo de 35000 con 3 entradas: counter up, counter down, reset y una salida que indique el valor actual del contador. Las entradas de contaje deben trabajar por flanco de subida. 
2. Usa 4 instancias del FB contador en el programa MAIN. Utiliza el input assistant para disponer de todas la entradas y salidas en la propia llamada del FB.

***
**Funciones**
1.	Crea una función que reciba dos números y devuelva su suma.
2.	Crea una función que reciba un array de números y devuelva el mayor de ellos.
3.	Crea una función que reciba un string y devuelva el número de vocales que contiene.
4.	Crea una función que reciba un array de *strings* y devuelva un nuevo array con las *strings* en mayúsculas.
5.	Crea una función que reciba un número y devuelva true si es primo, y false en caso contrario.
6.	Crea una función que reciba dos arrays y devuelva un nuevo array que contenga los elementos comunes entre ambos.
7.	Crea una función que reciba un array de números y devuelva la suma de todos los números pares.
8.	Crea una función que reciba un array de números y devuelva un nuevo array con cada número elevado al cuadrado.
9.	Crea una función que reciba una cadena de texto y devuelva la misma cadena con las palabras en orden inverso.
