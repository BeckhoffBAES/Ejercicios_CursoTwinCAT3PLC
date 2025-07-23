
Markdown	HTML	Rendered Output
# **Ejercicios Curso TC3 TwinCAT PLC**
## 1. Primer proyecto paso a paso 
1. ¿Cómo debo tener configurado el adaptador de red de mí PC para conectar vía ADS con una CPU Beckhoff configurada de fábrica? 
2. ¿Qué se necesita crear para disponer de una comunicación ADS entre máquinas?
3. ¿Qué usuario y contraseña lleva configurada una CPU Beckhoff de fábrica?
4. ¿Qué puertos usa la comunicación ADS segura y no segura?
5. ¿En qué modo debe estar el runtime de TwinCAT para escanear periferia?
6. ¿Para qué sirve el *freerun*?
7. ¿Qué es el process data de un esclavo EtherCAT?
8. ¿En qué color se representan las entradas y salidas de un esclavo EtherCAT respectivamente?
9. ¿Dónde puedo cambiar el adaptador físico que usa el Master EtherCAT?
10. ¿Qué tiempo de ciclo trabaja la tarea PlcTask que genera la plantilla de Standard PLC Project?
11.	¿Qué programa llama la tarea PlcTask que genera la plantilla de *Standard PLC Project*?
12.	¿En qué lenguaje se implementa el MAIN program?
13.	¿Cómo debo declarar una variable para poderla vincular a una entrada de la EL1014?
14.	¿Cómo debo declara una variable para poderla vincular a una salida de la EL2008?
15.	¿Cómo debo declarar una variable para poderla vincular a una entrada de la EL3255?
16.	¿Cómo debo declara una variable para poderla vincular a una salida de la EL4004?
17.	¿Cómo relaciono las variables de los puntos 13, 14, 15 y 16 con el *process data* de los eslavos EtherCAT?
18.	¿Qué pasos debo seguir para activar el proyecto de TwinCAT al *runtime*? ¿Qué diferencia hay entre activar configuración y hacer login?
19.	Crea un proyecto de cero, escanea la periferia y implementa un proyecto de PLC con un listado de variables globales que contenga todo el *process data* de los 5 esclavos EtherCAT conectados a la EK1100 del kit de formación. 

## 2. Texto Estructurado (ST) ##
1. ¿Qué estándar sigue el lenguaje ST de PLC?
2. ¿Qué sintaxis tiene el operador de asignación?
3. ¿Qué sintaxis tienen los operadores aritméticos de suma, resta, multiplicación, división, módulo y exponente?
4. ¿Qué sintaxis tienen los operadores de comparación mayor, menor, mayor o igual, menor i igual y diferente?
5. ¿Qué sintaxis tienen los operadores lógicos AND, OR y negación? 
6. Escribe la sintaxis del condicional IF completa
7. Escribe la sintaxis del condicional CASE completa
8. Escribe la sintaxis del condicional FOR completa
9. ¿Cómo obtendrías el número de bytes que ocupa un INT?
10.	¿Cómo harías una conversión de un BOOL a un INT?
11.	¿Cómo implementarías una intermitencia de un BOOL que cambia cada 1s?
 
## 3.  Tipos de datos ##
1. ¿Qué tipo de variable debo usar para representar el estado de una entrada digital?
2. ¿Qué tipo de dato debo usar para leer un canal de un terminal EL3255?
3. ¿Qué tipo de dato debo usar para representar un contador de valores únicamente positivos que pueda llegar hasta un máximo 65539?
4. ¿Qué tipo de dato debo usar para representar la edad de una persona?
5. ¿Qué tipo de dato debo usar para representar el peso de una persona?
6. ¿Qué tipo de dato debo usar para representar el nombre de una persona?
7. ¿Cuántos bytes ocupa un *LREAL*, *INT* y *BOOL* respectivamente?
8. ¿Qué tipo de dato debo usar para definir un tiempo?
9. ¿Qué tipo de dato debo usar para representar las coordenadas X, Y, Z?
10.	¿Cómo debo definir una variable para que se guarde a fichero persistente?
11.	¿Cómo puedo definir un valor que no se pueda modificar en tiempo de ejecución?
12.	¿Cómo puedo crear de forma automática la vinculación de una variable con un esclavo EtherCAT y forzar su refresco con la PlcTask?
13.	¿Qué tipo de dato de usuario permite definir en un solo tipo diferentes tipos de datos primitivos?
14.	¿Qué tipo de dato de usuario permite establecer una relación entre una etiqueta y un valor numérico?

## 4. Tipos de POU y lenguajes de PLC ##
1. ¿Qué 7 tipos de lenguajes permite el estándar IEC 61131-3?
2. ¿Qué 3 tipos de POU existen?
3. ¿Un programa (PRG) tiene instancias?
4. ¿Un function block (FB) puede llamar un programa?
5. ¿Un FB puede llamar otro FB?
6. ¿Un PRG puede llamar otro PRG?
7. ¿Qué tipo de POU puede llamar una tarea?
8. ¿Una función hay que definir antes de ser llamada?
9. ¿Con que tipo de POU sería la mejor forma de programar un contador?
10.	¿Para usar un FB hay que definirlo previamente?
11.	¿Con que tipo de POU sería la mejor forma de programar un escalado?

## 5. Gestión de tareas ##
1. ¿Qué el tiempo base y el tiempo de ciclo?
2. ¿Qué el *Exceed counter*?
3. ¿Puedo configura un tiempo de ciclo menor al tiempo base?
4. ¿Cuál es el tiempo mínimo de ciclo que puedo configurar en TwinCAT?
5. ¿Qué criterio sigue el Automatic Priority Managment?
6. ¿Qué es un núcleo aislado?
7. ¿Dónde puedo cambiar el tiempo de ciclo de la PlcTask?
8. ¿Cómo puedo crear una segunda tarea de PLC para llamar a un programa con un tiempo de ciclo de 1 ms?
 
## 6. Gestión de código de PLC ##
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

## 7. Datos remanentes ##
1. ¿Qué opción tenemos de guardar persistentes en el C6030 de formación?

## 8. Programación orientada a objetos ##
1. ¿Qué concepto de POO representa un FB?
2. ¿Qué representa la instancia de un FB en POO?
3. ¿Se deben usar las variables de entrada y salida de un FB en POO?
4. ¿Qué permite una propiedad?
5. ¿Para qué se usan los métodos?

## 9. Versiones de TC3 ##
1. ¿Dónde puedo ver la versión del proyecto de TwinCAT antes de abrirlo?
2. ¿Qué permite el *pineado* de proyecto?
3. ¿Qué permite la opción de *Set to Effective Version* de las librerías de PLC?
4. ¿Qué debo instalar para poder abrir proyectos de TwinCAT realizados con versiones de TwinCAT antiguas si no queremos migrar el proyecto?

## 10. Licencias ##
1. ¿El TwinCAT XAE requiere licencia?
2. ¿Dónde puedo encontrar el Performance Level (*PL*) de la CPU Beckhoff en el proyecto de TwinCAT?
3. ¿Una licencia de *dongle* para PL50 me sirve para un PL60?
4. ¿Qué es el system ID?
5. ¿Puedo probar funciones de TwinCAT en un PLC sin licencias?
6. ¿Qué número necesito para activar una licencia de forma manual?
7. ¿Cómo debo tener activadas las licencias si no quiero migrar las licencias en caso de avería de la CPU?

## 11. Presentación EtherCAT ##
1. ¿El EtherCAT es un bus propietario?
2. ¿El EtherCAT requiere direccionamiento físico de los dispositivos conectados a ella?
3. ¿Para qué se usan los *Distributed Clocks* (*DC*)?
4. ¿Se puede mezclar red Ethernet estándar TCP-IP con una red EtherCAT?
5. ¿En qué consiste la tecnología Hot-Connect de EtherCAT?
6. ¿Se pueden master EtherCAT contra master EtherCAT?
7. ¿Se puede combinar la redundancia y el Hot-Connect?
8. ¿Qué tecnología debería usar para alimentar esclavos EtherCAT por el mismo cable de comunicación EtherCAT?
9. ¿Qué tecnología debería usar para obtener 100 muestras para cada ciclo de scan de EtherCAT?
10.	¿Qué tecnología debería usar para obtener el tiempo exacto en que se activó una entrada digital?
11.	¿Cómo se llama el protocolo que permite comunicación segura sobre el bus EtherCAT?

## 12. Diagnóstico EtherCAT ##
1. ¿Se puede crear una arquitectura EtherCAT offline en TwinCAT?
2. ¿Qué debo instalar si al hacer un SCAN de EtherCAT no reconoce ningún esclavo?
3. ¿Al comparar la configuración Offline respecto el Online, que significan los colores verde, azul y rojo?
4. ¿Qué es y cómo puedo verificar el consumo del E-Bus?
5. ¿Qué diferencia hay entre los *frames* cíclicos y los acíclicos?
6. ¿Dónde puedo encontrar el estado de todos les esclavos de una red EtherCAT?
7. ¿En qué estado debe estar el esclavo EtherCAT para tener comunicación cíclica y acíclica activa?
8. ¿Cómo puedo solucionar un error de *VPRS*?
9. ¿Qué indica el LNK_ADD Port?
10.	¿Cómo máximo, cuantos puertos puede tener un esclavo EtherCAT?
11.	¿Qué significa el primer número la columna de CRC de la pestaña Online del master EtherCAT?
12.	¿Qué debo revisar si tengo errores Tx/Rx en mí red EtherCAT?
13.	¿Qué debo revisar si tengo todos los esclavos de una red EtherCAT en INIT NO_COMM?
14.	¿Qué significan los comandos LWR, LRD, LRW y BRD de EtherCAT?
15.	¿Qué significa un 10 a la columna de WC del comando BRD?
16.	¿Puedo leer por process data el estado de un esclavo EtherCAT?
17.	¿Puedo leer por process data el estado del WC de un esclavo EtherCAT?
18.	Dispongo de una red EtherCAT con una EK1100, EL1014, EL1004 y EL2008. ¿Se va perder comunicación con la EL1014 si desconecto la EL1004?
19.	¿Qué condición del state y WcState del infoData de un esclavo EtherCAT debería mirar para asegurar que la comunicación es OK?
20.	¿Cómo podría cambiar el comportamiento del punto 18?
21.	¿Qué librería de PLC permite hacer diagnóstico de EtherCAT?
22.	¿Qué es el CoE de un esclavo EtherCAT?
23.	¿En qué pestaña de un esclavo EtherCAT puedo añadir parámetros cíclicos? 
24.	¿Qué debería configurar para que cambie un esclavo EtherCAT se cargue de forma automática su configuración cuando inicie la red EtherCAT?
25.	¿Qué fichero necesito para integrar un esclavo de terceros en TwinCAT?

## 13. Scope View ##
1. ¿Cómo puedo añadir una variable de PLC directamente a un proyecto de Scope?
2. ¿Cómo se llama el FB que me permite controlar un proyecto de Scope desde PLC?

## 14. PLC HMI ##
1. ¿Qué diferencia hay entre el TF1800 y TF1810?
2. ¿El proyecto de PLC HMI se integra en el mismo proyecto de PLC de TwinCAT?

## 15. Instalación de software TwinCAT 4026 (Anexo) ##
1. ¿Qué necesito instalar previamente para instalar paquetes software 4026?
2. ¿Qué workflow debo instalar para disponer del XAE?
3. ¿Qué dos opciones de instalación tengo para simular proyectos de TwinCAT en mí PC de ingeniería?
4. ¿Qué necesito instalar en mí PC y en la CPU Beckhoff para inicializar un servidor OPC-UA?
5. ¿Si tengo la versión 4024 en mi PC de ingeniería puedo instalar directamente la versión 4026?

## 16. Opciones de comunicación (Anexo) ##
1. ¿La comunicación ADS usa Ethernet TCP-IP?
2. ¿Qué es la AMSNetID?
3. ¿Si quiero comunicar dos CPU’s Beckhoff en tiempo real vía Ethernet TCP-IP, qué protocolo debo usar?
4. ¿La CPU Beckhoff permite comunicación IoT mediante MQTT?
5. ¿La CPU Beckhoff permite comunicación con bases de datos?

## Gestión de sistema operativo (Anexo) ##
1. ¿Cómo puedo cambiar la IP de una CPU Beckhoff si no dispongo de pantalla ni escritorio remoto?
2. ¿En qué ruta de la CPU Beckhoff se guarda el proyecto compilado y las persistentes en 4026?
3. ¿En qué ruta de la CPU Beckhoff se guardan las licencias activadas en 4026?
4. ¿Los logs de TwinCAT se integran en el log de Windows?
5. ¿Qué necesito para hacer un backup total de la CPU Beckhoff si trabaja con Windows IoT 2022 como sistema operativo?

## Gestión de errores ##
1. ¿Qué significa un error 1804 de ADS?
2. ¿Qué instrucción de PLC permite prevenir una excepción de PLC?
3. ¿Qué permite las funciones de comprobaciones implícitas?
4. ¿Qué herramienta permite contabilizar los tiempos de ejecución de los distintos POU’s de un proyecto de PLC?

<!--
`This is one line code`

``` 
This is multiline Code
K
K
  ```

![Instalación TwinCAT](/images/image.png "TwinCAT")

[This is a comment that will be hidden.]: # ""
-->

 



