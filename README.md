# Save-me-tunnas

## Integrantes:

- Ricardo Juan Jesús Gloria Gloria

- Sandra Karina Álvarez González


## Objetivo general:

El proyecto pretende diseñar un dispositivo que sea capaz de enviar la ubicación y una señal de alerta con opción de complementar con una lámina solar; pero no solo eso, también se incluirá una caja fuerte para que las personas se sientan seguras: esto es “sálvame tunas” 
Para ello se tendrán contactos de emergencia predeterminados. Se piensa que pueda ser utilizado en situaciones riesgosas donde exista poco tiempo de reacción o acción.
 

### Objetivos específicos:

- Analizar la problemática de seguridad a la que se enfrentan personas desde su oficina, casa o espacio de trabajo.
- Se diseñará una solución que pueda tener otras utilidades. Todas en función de la seguridad.
-- Enviar por SMS a un contacto predefinido la ubicación y un mensaje de alerta.
-- Intentar tener un objeto protegido con la caja fuerte.
-- Generar una posibilidad de encontrar o rescatar personas en situaciones de peligro.
- Se planeará el desarrollo y los pasos a seguir.
- Se codificará.
- Por último se probará el circuito y el código. Así como el funcionamiento general del dispositivo.


## Tabla de Software utilizado

| Id | Software | Version | Tipo |
|----|----------|---------|------|
| 1   |   Arduino IDE       |    2.0     |Código abierto y su código fuente estará alojado en GitHub.      |



## Tabla de hardware utilizado

| Id | Componente | Descripción | Imagen | Cantidad | Costo total |
|----|------------|-------------|--------|----------|-------------|
|  1  | ESP32           |   Familia de chips SoC de bajo costo y consumo de energía, con tecnología Wi-Fi y Bluetooth de modo dual integrada.  |   ![image](https://user-images.githubusercontent.com/108686186/192938880-9c3dabf7-60b4-434b-a5d0-bb5decc23522.png)     |    1      |    $150         |
|   2 | Modulo GPS neo – 6m Ublox con antena.           |  Módulo que utiliza la tecnología de Ublox para brindar una excelente información de posicionamiento. También incluye una antena GPS de 25 x 25 mm, con conector UFL. Posee una pequeña batería y una memoria EEPROM que permite guardar los últimos datos de posicionamiento y así lograr una detección más rápida.           |     ![image](https://user-images.githubusercontent.com/108686186/193502087-7dd43126-fa1b-4a8d-b5d3-b8fc6f9c30e3.png)
   |   1       | $160            |
|  3  |  Modulo LCD Shield 16×2 I2C          |  Esta pantalla tiene un tamaño de 16×2, y esto hace referencia a que cuenta con 2 filas y cada fila tiene la capacidad de mostrar 16 caracteres o símbolos, por lo general alfanuméricos, los cuales se pueden definir desde programación utilizando un microcontrolador o tarjeta de desarrollo.           |    ![image](https://user-images.githubusercontent.com/108686186/193502135-adca6654-861b-4d50-a5f7-60cf220d5f29.png)
    |     1     |        $270     |
| 4 | Push Button | Un push button es un sensor digital de entrada, es decir, su funcionamiento consiste en entregar la información correspondiente si es presionado o no a través del voltaje en su pin de señal. | ![image](https://user-images.githubusercontent.com/108686186/193502188-640a571a-960f-4730-b21f-23e1de30a98d.png) | 10 | $50 |
| 5 | Teclado numérico matricial 4×4 | Un teclado matricial 4×4 es un dispositivo que agrupa varios pulsadores y permite controlarlos empleando un número de conductores inferior al que necesitaríamos al usarlos de forma individual.  | ![image](https://user-images.githubusercontent.com/108686186/193502245-9db3cfad-12f2-4be0-a4db-cfd7dab41788.png) | 1 | $50 |
| 6 | Servo motor Micro SG90 | Un servomotor es un actuador rotativo o motor que permite un control preciso en términos de posición angular, aceleración y velocidad, con capacidades que un motor normal no tiene. En definitiva, utiliza un motor normal y lo combina con un sensor para la retroalimentación de posición. | ![image](https://user-images.githubusercontent.com/108686186/193502361-abf416d9-0391-488d-ae30-fc4ed5e1cde0.png) | 1 | $70 | 
| 7 | Celda solar 6v 100ma Panel solar 56×80mm | Las celdas solares, o células solares fotovoltaicas, se definen como los dispositivos capaces de convertir la radiación solar en energía eléctrica mediante el efecto fotovoltaico. Las celdas solares se constituyen de materiales semiconductores, generalmente de silicio. | ![image](https://user-images.githubusercontent.com/108686186/193502462-d7fb39bc-ce33-4508-a8a2-c9b7739c8b79.png) | 1 | $100 |

## Épicas del proyecto


-Mensaje de alerta:

  Módulo GPS

  Actuador: Sonido de alerta más envió de ubicación

  Formma de comunicación: Envío de SMS


-Mensaje de voz:

  Sensor de voz

  Actuador: Led que indica grabación.

  Forma de comunicación: Envió de correo.


## Tablas de usuario

1. Enviar ubicación. 

Prioridad: Máxima

Estimación: Un mes de trabajo.

Cómo probarlo: Presionar botón y revisar el mensaje que se le envió al contacto.

Responsables: Ricardo Juan Jesús y Sandra Karina.


2. Enviar audio.

Prioridad: De alta a media.

Estimación: Un mes de trabajo.

Cómo probarlo: Presionar el mismo botón dos veces para iniciar grabación y revisar que se haya enviado al contacto.

Responsables: Ricardo Juan Jesús y Sandra Karina.

3. Tomar temperatura.

Prioridad: Nula.


## Prototipo

![image](https://user-images.githubusercontent.com/108686186/193501059-364350fa-e4e0-454c-bf93-ec89e7b91eb9.png)



