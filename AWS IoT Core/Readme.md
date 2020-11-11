

# AWS IoT Core
by Giezy Martínez De La Cruz

![iot](https://d1.awsstatic.com/IoT/diagrams/AWS%20IoT%20Core%20-%20Connect%20and%20Manage.edb43e92d542f4053727eaeda267e3776382fd06.png)

Es un servicio en la nube administrado que permite a los dispositivos conectados interactuar de manera fácil y segura con las aplicaciones en la nube y otros dispositivos. AWS IoT Core admite miles de millones de dispositivos y billones de mensajes, y es capaz de procesarlos y direccionarlos a puntos de enlace de AWS y a otros dispositivos de manera fiable y segura.

Este servicio proporciona una gran cantidad de funcionalidades, como se muestra a continuación.

### Conexión y administración de dispositivos.
Admite HTTP, WebSockets y MQTT, un protocolo de comunicación ligero, especialmente diseñado para tolerar conexiones intermitentes, minimizar la huella de código en los dispositivos y reducir los requisitos de ancho de banda de la red. Además, AWS IoT Core es compatible con otros protocolos personalizados y propios del sector, y los dispositivos pueden comunicarse entre sí aunque utilicen protocolos distintos.

### Lectura y definición de estados de dispositivos en cualquier momento.
Almacena el último estado de un dispositivo conectado para que pueda leerse o definirse en cualquier momento, lo que hace que el dispositivo aparezca en las aplicaciones como si estuviera conectado en todo momento. Esto supone que las aplicaciones pueden leer el estado de un dispositivo incluso si está desconectado; también permite definir el estado de un dispositivo e implementarlo cuando se vuelve a conectar.

### Protección de datos y conexiones de dispositivos.
Proporciona configuración y autenticación automatizadas en la primera conexión de un dispositivo a AWS IoT Core, así como el cifrado de extremo a extremo en todos los puntos de conexión, de modo que los datos nunca se intercambian entre dispositivos y AWS IoT Core sin identidad comprobada. 

### Escalable de manera rentable a cientos de millones de dispositivos con Alexa integrado.
La integración de Alexa Voice Service (AVS) para AWS IoT Core introduce un nuevo dispositivo virtual con Alexa integrado en la nube. Para utilizar la integración de AVS, los clientes utilizan un nuevo conjunto de temas MQTT reservados a AWS IoT para transferir mensajes de audio basados en MQTT entre dispositivos conectados a AWS IoT Core y el nuevo dispositivo virtual con Alexa integrado. Esto permite a los clientes enviar y recibir mensajes de audio sobre los temas de MQTT reservados, interactuar con el micrófono y el altavoz del dispositivo, y administrar el estado del lado del dispositivo mientras se usa la misma conexión segura de IoT Core.

### Procesamiento y utilizacion de datos de dispositivos.
puede filtrar, transformar y utilizar datos de dispositivos sobre la marcha según las reglas empresariales que haya establecido. Puede actualizar las reglas para implementar nuevas características de dispositivos y aplicaciones cuando lo desee. AWS IoT Core facilita la utilización de servicios de AWS, como AWS Lambda, Amazon Kinesis, Amazon S3, Amazon DynamoDB, Amazon CloudWatch y Amazon Elasticsearch Service para lograr aplicaciones de IoT incluso más eficientes.

![funcionalidad](https://d1.awsstatic.com/IoT/diagrams/AWS%20IoT%20Core%20-%20Process%20and%20Act.2b1f03813fbd3b4416e45c096336497f22954520.png)

