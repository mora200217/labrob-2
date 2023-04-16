# Laboratorio #2 Robótica 
Segundo laboratorio de la asignatura de Robótica de la Universidad Nacional de Colombia 2023-i. 

<p align="center">
<img marigin="auto" src="https://github.com/mora200217/labrob-1/blob/master/assets/funcional.gif" width="60%"/> 
</p>

**Integrantes**: 
* Nelson David Ramírez Marín
* Andrés Zuleta 
* Andrés Morales Martínez 

## Planteamiento del Problema 
La rutinas definidas desde RobotStudio, por facilidad e interactividad en algunas aplicaciones son activadas por una operario externo por medio de un tablero de control. El controlador debe asignar las subrutinas en funcion de la interacción con el tablero. 
 
## Desarrollo 
En RobotStudio se agrega el componente de I/O al controlador, para definir los puntos de conexión. Se conectan los botones / indicadores a las entradas / salidas respectivamente, acorde con lo definido en el programa. 


### Aplicación de secuencia 
Se usaron dos botones (entrada) y un indicador (salida); ambos digitales

Se definieron dos entradas digitales. 
-  La primera (DI_01) espera a ser activada para ejecutar la subrutina de escritura. 
-  La segunda (DI_02) posterior a la ejecución de escritura, provoca un giro de 90º en la primera articulacion (J1). 

Solo se usó una salida digital. 
- DO_01 se usó como indicador de funcionamiento del robot. Activado con la primera entrada (DI_01) y desactivado al finalizar la segunda subrutina (Activada por DI_02)


__Implementación de la práctica en el laboratorio:__ https://youtu.be/Z5ZqPjXJmZI

__Simulación en RobotStudio:__ https://youtu.be/4mG4dATRGfc


## Conclusiones 
1. Un tablero de control permite realizar un seguimiento de la rutina, para revisión de intervención / mantenimiento, o instantes que requieran un tiempo de espera entre subrutinas del proceso.
2. El uso de botones / indicadores facilita la aplicación de la rutina permitiendo un uso intuitivo que no requiera de conocimiento técnicos profundos para su uso.
3. Los indicadores permiten vizualizar el inicio / final del proceso industrial.  

