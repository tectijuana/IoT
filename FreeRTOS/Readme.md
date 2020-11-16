# FreeRTOS

![](https://d1.awsstatic.com/diagrams/Updated%20FreeRTOS%20how%20it%20works.fe61439aeb67580604f20cc89dba2bf1c89c1dc0.png)

By Giezy Martínez De La Cruz

Es un sistema operativo en tiempo real de código abierto para microcontroladores que facilita la programación, la implementación, la protección, la conexión y la administración de los dispositivos de borde pequeños y de bajo consumo. FreeRTOS, distribuido de forma gratuita con la licencia de código abierto MIT, incluye un kernel y un conjunto de bibliotecas de software en crecimiento apto para su uso en todos los sectores y aplicaciones del sector. Esto incluye una conexión de forma segura de sus dispositivos pequeños de bajo consumo con los servicios en la nube de AWS, como AWS IoT Core, o bien, con otros dispositivos de borde más potentes en los que se ejecute AWS IoT Greengrass. FreeRTOS se crea con un especial énfasis en la fiabilidad y facilidad de uso.

Los microcontroladores constan de un solo procesador con recursos limitados y están presentes en muchos dispositivos, incluidos electrodomésticos, sensores, monitores de actividad, sistemas de automatización industriales y automóviles. Muchos de estos pequeños dispositivos pueden beneficiarse de la conexión a la nube o a otros dispositivos de forma local. Sin embargo, cuentan con una potencia de cómputo y una capacidad de memoria limitada, y generalmente, ejecutan tareas simples y funcionales. A menudo, los microcontroladores funcionan con sistemas operativos que no tienen integrada ninguna funcionalidad para conectarse a redes locales o a la nube, lo que convierte a las aplicaciones de IoT en un verdadero desafío. FreeRTOS ayuda a solucionar este problema proporcionando tanto el kernel para ejecutar dispositivos de bajo consumo, así como también las bibliotecas de software que facilitan la conexión segura a la nube o a otros dispositivos de borde a fin de que pueda recopilar datos de los dispositivos para las aplicaciones de IoT y tomar las medidas pertinentes.

### Beneficios
- Código abierto.
- Kernel fiable.
- Incluye integraciones de referencia de IoT.
- Incluye soporte para Transport Layer Security (TLS v1.2).
- Amplio soporte para ecosistema.
- Puede usar AWS IoT Device Tester para verificar con confianza si sus dispositivos ejecutarán FreeRTOS e interactuarán con los servicios de AWS IoT.

AWS proporciona una lista de 54 dispostivos que han sido probados para ejecutar FreeRTOS sin ningún problema, se encuentran microcontroladores de varias marcas y modelos. El siguiente dispositivo que se muestra a continuación presenta el precio más acequible y proporciona todas características necesarias para poder crear una solución IoT.

| Nombre | img | Características | Precio(USD) |
| --- | ---- | ------------ | --- |
| ESP32-WROOM-32 DevKitC | ![](https://devices.amazonaws.com/device_images/a3G0L00000AANtjUAH/main_image_108c5db4-8fc0-4008-b5da-90860d97f208.jpeg) | $ 13.00

