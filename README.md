# self_balancing_bike

## _Digital controller design_
Objetivo: Construir una moto auto balanceada a partir de un sistema de controladores digitales para demostrar utilizando microcontroladores y un sistema de control PID.

## Materials
- Gyro sensor MPU-60505
- Arduino Uno
- Bluetooth module HC-06
- Servo motor sg-90
- 2 geared motors
- Breadboard
- Dupont wires
-	Wooden structure

## Control system
_Explanation of the control system_

Automatic control PID: El controlador PID es un algoritmo de control ampliamente utilizado en de control de procesos. Consiste en tres componentes principales: la ganancia proporcional (P), la ganancia integral (I) y la ganancia derivativa (D).

- Kp = Ganancia proporcional: es la diferencia entre la posición deseada y la posición medida del robot.
- Ki = Tiempo integral: es la suma acumulativa de los errores pasados.
- Kd = Tiempo derivado: es la tasa de cambio actual del error

Los valores de Kp, Ti y Td deben ajustarse experimentalmente para obtener un rendimiento óptimo del controlador en función de las características específicas del robot y del entorno.

## Values ​​used for PID control
- Setpoint = 173
- Proportional Gain = 450
- Derivative Gain = 3.0
- Integral Gain = 1.2

## Conexion Diagram
diagrama de conexion de los componentes
[![schematic.png](https://i.postimg.cc/KcNvSL5y/schematic.png)](https://postimg.cc/F1YQ0YqP)

_esquematico de conexiones. (2023). imagen JPG. https://github.com/remrc/Self-Balancing-Bike_

## Structural design
El cuerpo de la moto autobalanceada se conforma de 4 secciones esenciales, siendo la base principal donde se alberga al controlador asi como el sensor giroscopico y el modulo de comunicacion bluetooth HC_05, las secciones delantera y trasera donde se colocaran los motores de movimiento en la seccion delantera se utilizara un servomotor SG-90 para controlar los giros de derecha a izquierda, en la seccion trasera se coloca un motorreductor para el movimiento hacia adelante y atras, como ultima seccion se colocar una base para el motor de control para la rueda volada, la cual permitira el control del balanceo de la moto.
- IMAGEN 1
- [![bike1.jpg](https://i.postimg.cc/DZYh0QpW/bike1.jpg)](https://postimg.cc/2bvMXWDm)

- IMAGEN 2
- [![Whats-App-Image-2023-08-23-at-2-15-45-PM.jpg](https://i.postimg.cc/sg9R7C0C/Whats-App-Image-2023-08-23-at-2-15-45-PM.jpg)](https://postimg.cc/G42NnVCX)
