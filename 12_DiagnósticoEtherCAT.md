


## 12. Diagnóstico EtherCAT ##
### Cuestionario ###
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

### Práctico ###
1. Vincula el state y WCstate de todos los esclavos EtherCAT presentes en el proyecto del curso TwinCAT 3 PLC a dos arrays (una para el state y otra para el WcState).
2. Crea un programa (PRG) de diagnóstico EtherCAT que compruebe si la comunicación EtherCAT con todos los esclavos está correcta haciendo uso de la información del punto anterior.
3. Desconecta el último esclavo EtherCAT y revisa el diagnóstico realizado. 