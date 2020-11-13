# Amazon IoT Device Defender.

AWS IoT Device Defender es un servicio completamente administrado que le ayuda a proteger su flota de dispositivos IoT. AWS IoT Device Defender audita continuamente sus configuraciones de IoT para garantizar que no se aparten de las prácticas recomendadas de seguridad. Una configuración es un conjunto de controles técnicos que usted define para proteger su información cuando los dispositivos se comunican entre sí y con la nube. 

AWS IoT Device Defender facilita el mantenimiento y el cumplimiento de las configuraciones de IoT, como garantizar la identidad del dispositivo, la autenticación y autorización de dispositivos y el cifrado de los datos del dispositivo. AWS IoT Device Defender audita continuamente las configuraciones de IoT de sus dispositivos de acuerdo con un conjunto de prácticas recomendadas de seguridad previamente definidas. 

AWS IoT Device Defender le envía una alerta si encuentra deficiencias en su configuración de IoT que puedan crear riesgos de seguridad, como certificados de identidad compartidos por varios dispositivos o un dispositivo con un certificado de identidad rechazado que intenta conectarse a AWS IoT Core.

AWS IoT Device Defender también le permite monitorizar continuamente métricas de seguridad de los dispositivos y de AWS IoT Core a fin de detectar desviaciones de los valores que haya definido como comportamiento apropiado para cada dispositivo. Si encuentra algo que no está en orden, AWS IoT Device Defender le envía un alerta para que pueda tomar medidas y solucionar el problema. Por ejemplo, los picos en el tráfico saliente pueden indicar que un dispositivo está participando en un ataque DDoS. AWS IoT Greengrass y FreeRTOS se integran automáticamente a AWS IoT Device Defender a fin de proporcionar métricas de seguridad de los dispositivos para su evaluación.

AWS IoT Device Defender puede enviar alertas a la consola de AWS IoT, a Amazon CloudWatch y a Amazon SNS. Si determina que debe tomar una medida basada en una alerta, puede utilizar AWS IoT Device Management para llevar a cabo acciones de mitigación, p. ej., instalar correcciones de seguridad.

¿Por qué es importante la seguridad de IoT?
Los dispositivos conectados se comunican constantemente entre ellos y con la nube utilizando diferentes tipos de protocolos de comunicación inalámbrica. Si bien la comunicación crea aplicaciones de IoT con capacidad de respuesta, también puede exponer las vulnerabilidades de seguridad de IoT y abrir canales para los actores malintencionados o para filtraciones de datos accidentales. Para proteger a los usuarios, los dispositivos y las empresas, los dispositivos IoT deben estar seguros y protegidos. La base de la seguridad de IoT se encuentra en el control, la administración y el establecimiento de conexiones entre los dispositivos. Una protección adecuada ayuda a mantener la privacidad de los datos, restringe el acceso a los dispositivos y a los recursos de la nube, ofrece formas seguras de conectarse a la nube y audita el uso de los dispositivos. Una estrategia de seguridad de IoT reduce las vulnerabilidades mediante políticas como la administración de identidades de dispositivos, el cifrado y el control de acceso.

¿Cómo funciona AWS IoT Device Defender?
AWS IoT Core proporciona los componentes básicos de seguridad para que pueda conectar dispositivos de forma segura con la nube y con otros dispositivos. Estos componentes básicos permiten aplicar controles de seguridad como autenticación, autorización, registro de auditoría y cifrado de extremo a extremo. Sin embargo, los errores humanos o del sistema y las personas autorizadas con malas intenciones pueden introducir configuraciones que afecten negativamente a la seguridad.

![](https://d1.awsstatic.com/IoT/How%20it%20Works%20AWS%20IoT%20Device%20Defender.1839e9f3b9630f6db29cd5b4c63984c1bfdd5ebb.png)


**Por:** 

 - Castillo Aguado Oscar Eduardo.
 - Lopez Godoy Ariadna Guadalupe.
 - Argaez Galindo Jesus Alexis.
