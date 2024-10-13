# MQTT

![MQTT](MQTT.png) {width="700"}

## Descripción

MQTT es un protocolo de mensajería basado en estándares. Los sensores inteligentes, los dispositivos portátiles y otros dispositivos de Internet de las cosas (IoT) generalmente tienen que transmitir y recibir datos a través de una red con recursos restringidos y un ancho de banda limitado. Estos dispositivos IoT utilizan MQTT para la transmisión de datos, ya que resulta fácil de implementar y puede comunicar datos IoT de manera eficiente.

MQTT fue creado originalmente por el Dr. Andy Stanford-Clark y Arlen Nipper en 1999. El propósito original de este método de comunicación era permitir que los dispositivos de monitoreo utilizados en la industria del petróleo y el gas enviaran sus datos a servidores remotos. Con miles de sensores en el campo, la industria necesitaba una forma de comunicación que pudiera proporcionar datos de manera suficientemente fiable para su uso, mientras empleaba un ancho de banda mínimo.

En 2010, IBM lanzó MQTT 3.1 como un protocolo gratuito y abierto para que cualquiera pudiera implementarlo, que después, en 2013, se envió al organismo de especificación de la Organización para el Avance de Estándares de Información Estructurada (OASIS) para su mantenimiento. En 2019, OASIS lanzó una versión 5 de MQTT actualizada. Ahora MQTT ya no es un acrónimo sino que se considera el nombre oficial del protocolo.

MQTT se ejecuta sobre TCP/IP utilizando una topología PUSH/SUBSCRIBE. En la arquitectura MQTT, existen dos tipos de sistemas: clientes y brókeres. Un bróker es el servidor con el que se comunican los clientes: recibe comunicaciones de unos y se las envía a otros. Los clientes no se comunican directamente entre sí, sino que se conectan con el bróker. Cada cliente puede ser un editor, un suscriptor o ambos.

MQTT es un protocolo controlado por eventos, donde no hay transmisión de datos periódica o continua. Así se mantiene el volumen de transmisión al mínimo. Un cliente sólo publica cuando hay información para enviar, y un bróker sólo envía información a los suscriptores cuando llegan nuevos datos.

