

## 6. Gestión de código de PLC ##
### Cuestionario ###
1. ¿Qué debo configurar para que el TwinCAT arranque en modo RUN e inicie el proyecto de PLC por defecto?
2. ¿Qué tipo de Login permite aplicar cambios sin para el proyecto de PLC?
3. ¿Qué permite el *breakpoint*?
4. ¿Cómo puedo cambiar el valor de una variable Online desde TwinCAT?
5. ¿Cómo puedo saber todos los puntos del proyecto de PLC que se usa una variable y el tipo de acceso que se hace?
6. ¿Cómo puedo visualizar en una lista única los valores online de distintas variables de distintos POU’s?
7. ¿Cómo puedo desactivar la descarga del código fuente del proyecto de PLC?
8. ¿Qué herramienta me permite comprar proyectos de TwinCAT?
9. ¿Qué librería contiene FB’s para detectar flancos?
10. ¿Qué librería contiene FB para generar números aleatorios?
11. ¿Qué FB de la librería Tc2_Utilities permite obtener la hora del sistema operativo?

### Práctico ###
***
**Excepciones**
1. Provoca una división por 0. ¿En qué estado se queda la CPU Beckhoff?
2. ¿Como puedo identificar la línea de código que provoca una división por 0 en el código de PLC?
3. Haz uso de un *breakpoint*
4. Haz uso de un *watchlist* para visualizar variables de distintos programas. 
5. Añade un variable a un proyecto de Scope mediante la opción Add To Scope. 
6. Crea un *breakpoint* dentro de un FB y haz uso del call stack para verificar la pila de llamadas. 
7. Usa el *corss reference list* para identificar el uso de una variable en el proyecto de TwinCAT. 

***
**Librerías**
1. Añade la librería y FB necesario para generar un número aleatorio. 
2. Añade la librería y FB necesario para obtener la fecha y hora del sistema.
3. Crea un FB que implemente la escritura de un fichero .txt a modo de log. Ayúdate de la librería Tc2_System. Crea una entrada para indicar el mensaje a escribir (STRING) y un BOOL para dar la orden de escribir en cada flanco de subida. Indica también con una salida de BOOL que la operación se ha completado correctamente. Crea el fichero en la ruta C:\logger\log.txt
4. Haz uso del FB del punto 3 en un programa en ST. 
5. Añade en la implementación del FB del punto 3, la concatenación de la fecha y hora del sistema operativo juntamente con el mensaje. 
