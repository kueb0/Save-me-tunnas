# Save-me-tunnas

## Integrantes:

- Ricardo Juan Jesús Gloria Gloria

- Sandra Karina Álvarez González


## Objetivo general:

El proyecto pretende diseñar un dispositivo que sea capaz de enviar la ubicación y una señal de alerta con opción de complementar con un mensaje de audio. Para ello se tendrán contactos de emergencia predeterminados. Se piensa que pueda ser utilizado en situaciones riesgosas donde exista poco tiempo de reacción o acción. 

### Objetivos específicos:

-Enviar pos sms a un contacto predefinido la ubicación más sonido de alerta.

-Enviar mensaje de audio a contacto predefinido a través de correo electrónico.

-Generar una posibilidad de encontrar o rescatar personas en situaciones de peligro.


# Tabla de software utilizado

## Tabla de Software utilizado
| Id | Software | Version | Tipo |
|----|----------|---------|------|
| 1   |   Arduino IDE       |    2.0     |Código abierto y su código fuente estará alojado en GitHub.      |
|    |          |         |      |
|    |          |         |      |


# Tabla de hardware utilizado

| Id | Componente | Descripción | Imagen | Cantidad | Costo total |
|----|------------|-------------|--------|----------|-------------|
|  1  | ESP32           |   Familia de chips SoC de bajo costo y consumo de energía, con tecnología Wi-Fi y Bluetooth de modo dual integrada.  |   ![image](https://user-images.githubusercontent.com/108686186/192938880-9c3dabf7-60b4-434b-a5d0-bb5decc23522.png)     |    1      |    $150         |
|    |            |             |        |          |             |
|    |            |             |        |          |             |


2. Sensor de voz arduino

1 módulo de sensor de detección de sonido por voz KY-037.

![image](https://user-images.githubusercontent.com/108686186/192939769-1b47820a-244a-43fa-8dad-267fc87def2b.png)

Cantidad: 1

Costo total: $156

3. Módulo GPS neo-6m Ublox con antena

El módulo GPS GY-NEO6MV2 puede ser utilizado en la construcción de cuadricópteros o drones, así como botes de radio control o en sistemas de seguridad en automóviles o en toda aplicación que requiera de geolocalización.
Cuenta con una antena de gran potencia así como una memoria EEPROM para guardar datos y una batería para hacer el respaldo de la configuración del módulo.

![image](https://user-images.githubusercontent.com/108686186/192941199-2c2f48bf-fde8-4b26-bf55-6ffba48f65b9.png)

Cantidad: 1

Costo total: $260

4. SIM 800L

Conecta tus proyectos a la red celular y enviar mensajes de texto, datos y llamadas. El módulo SIM800L es un dispositivo GSM y GPRS con la capacidad de hacer, recibir y enviar servicios de banda cuádruple, como llamadas de voz, envío de SMS e intercambio de datos a través de Internet. Cuenta con un zócalo para conectar un Micro SIM y pinos de comunicación UART, conexión de auriculares y micrófono lo que lo convierte en un excelente medio de comunicación portátil

![image](https://user-images.githubusercontent.com/108686186/192941609-ea4e6d84-d110-4851-a5a6-b2496d360114.png)

Cantidad: 1

Costo total: $160


# Épicas del proyecto


-Mensaje de alerta:

  Módulo GPS

  Actuador: Sonido de alerta más envió de ubicación

  Formma de comunicación: Envío de SMS


-Mensaje de voz:

  Sensor de voz

  Actuador: Led que indica grabación.

  Forma de comunicación: Envió de correo.


# Tablas de usuario

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


# Prototipo

![image](https://user-images.githubusercontent.com/108686186/192945350-bf0dc77e-894d-42a0-8622-a9abd3ac8869.png)



