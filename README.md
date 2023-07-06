# holbertonschool-system_engineering-devops
holbertonschool-system_engineering-devops


##
# Conceptos básicos de red

Este repositorio contiene ejemplos y scripts básicos relacionados con los conceptos fundamentales de redes.

## Servidor

Un servidor es un dispositivo o programa informático que proporciona servicios a otros dispositivos llamados clientes. En el contexto de redes, un servidor puede ofrecer diversos servicios como almacenamiento de archivos, acceso remoto, impresión, correo electrónico, etc.

## Servidor web

Un servidor web es un tipo de servidor que responde a las solicitudes realizadas por los clientes a través del protocolo HTTP (Hypertext Transfer Protocol). Su función principal es entregar páginas web y otros recursos estáticos o dinámicos a los clientes que las solicitan.

## DNS

DNS (Domain Name System) es un sistema de nomenclatura jerárquica utilizado para traducir nombres de dominio legibles por humanos en direcciones IP numéricas que las computadoras pueden entender. Actúa como una guía telefónica de Internet, permitiendo que los usuarios accedan a sitios web y servicios utilizando nombres de dominio en lugar de tener que recordar las direcciones IP correspondientes.

## Balanceador de carga

Un balanceador de carga es un dispositivo o software que distribuye el tráfico de red entrante entre varios servidores o recursos para optimizar el rendimiento y garantizar la disponibilidad de los servicios. Su objetivo es equilibrar la carga de trabajo de manera eficiente, asegurando que ningún servidor se sobrecargue y manteniendo el sistema en funcionamiento incluso si uno o varios servidores fallan.

## Supervisión

La supervisión en el contexto de redes se refiere al monitoreo y seguimiento constante de los componentes y el rendimiento de una red. Esto implica la recopilación de datos, el análisis de métricas y la generación de alertas para identificar problemas, mejorar la seguridad y optimizar el rendimiento de la red.



# Conceptos básicos de red

Este repositorio contiene ejemplos y scripts relacionados con los conceptos fundamentales de redes. A continuación, se explican en detalle algunos de los conceptos clave abordados en este repositorio:

## Concepto de servidor

Un servidor es un dispositivo o programa informático que proporciona servicios a otros dispositivos llamados clientes. Actúa como una entidad centralizada que responde a las solicitudes de los clientes y les brinda acceso a recursos compartidos, como archivos, datos o servicios.

## Concepto de servidor web

Un servidor web es un tipo de servidor que responde a las solicitudes realizadas por los clientes a través del protocolo HTTP (Hypertext Transfer Protocol). Su función principal es entregar páginas web y otros recursos estáticos o dinámicos a los clientes que las solicitan. Los servidores web son fundamentales para el funcionamiento de sitios web y aplicaciones basadas en la web.

## Concepto de DNS

DNS (Domain Name System) es un sistema de nomenclatura jerárquica utilizado para traducir nombres de dominio legibles por humanos en direcciones IP numéricas que las computadoras pueden entender. Actúa como una guía telefónica de Internet, permitiendo que los usuarios accedan a sitios web y servicios utilizando nombres de dominio en lugar de tener que recordar las direcciones IP correspondientes. El DNS juega un papel crucial en la resolución de nombres y enrutamiento eficiente en la red.

## Concepto de equilibrador de carga

Un equilibrador de carga (load balancer) es un dispositivo o software que distribuye el tráfico de red entrante entre varios servidores o recursos para optimizar el rendimiento y garantizar la disponibilidad de los servicios. Su objetivo es equilibrar la carga de trabajo de manera eficiente, asegurando que ningún servidor se sobrecargue y manteniendo el sistema en funcionamiento incluso si uno o varios servidores fallan. Los equilibradores de carga son comúnmente utilizados en entornos de alta demanda y aplicaciones web escalables.

## Concepto de monitorización

La monitorización en el contexto de redes se refiere al monitoreo y seguimiento constante de los componentes y el rendimiento de una red. Esto implica la recopilación de datos, el análisis de métricas y la generación de alertas para identificar problemas, mejorar la seguridad y optimizar el rendimiento de la red. La monitorización permite detectar y solucionar problemas de red de manera proactiva, asegurando un funcionamiento eficiente y confiable.

## ¿Qué es una base de datos?

Una base de datos es un sistema organizado de almacenamiento de datos que permite gestionar, organizar y recuperar información de manera eficiente. Proporciona una estructura y un mecanismo para almacenar y recuperar datos de manera confiable y segura. Las bases de datos se utilizan ampliamente en aplicaciones y sistemas para almacenar y gestionar datos estructurados, como registros de clientes, inventarios, transacciones, etc.

## ¿Cuál es la diferencia entre un servidor web y un servidor de aplicaciones?

Un servidor web se encarga de responder a las solicitudes de los clientes para entregar páginas web y otros recursos web. Sirve principalmente contenido estático y utiliza protocolos como HTTP para la comunicación. Por otro lado, un servidor de aplicaciones es un entorno en el que se ejecutan aplicaciones web complejas. Proporciona un entorno en tiempo de ejecución para ejecutar aplicaciones y ofrece servicios adicionales como gestión de transacciones, seguridad, conectividad con bases de datos, etc. Los servidores de aplicaciones son utilizados en aplicaciones empresariales y sistemas que requieren lógica de negocios compleja.

## Tipos de registros DNS

Los registros DNS son elementos de información almacenados en una zona DNS que proporcionan diferentes tipos de datos sobre un nombre de dominio específico. Algunos ejemplos de registros DNS comunes incluyen:

- Registro A: Mapea un nombre de dominio a una dirección IPv4.
- Registro AAAA: Mapea un nombre de dominio a una dirección IPv6.
- Registro MX: Especifica el servidor de correo responsable de recibir mensajes de correo electrónico destinados a un dominio.
- Registro CNAME: Crea un alias de un nombre de dominio a otro nombre de dominio.
- Registro TXT: Almacena texto arbitrario asociado con un nombre de dominio, utilizado para diversas finalidades como autenticación, configuración de SPF, etc.

## Punto único de fallo

Un punto único de fallo (single point of failure) es un componente o recurso en un sistema que, si falla, provoca la interrupción o el fallo completo del sistema. Cuando un sistema depende de un solo punto para su funcionamiento, cualquier falla en ese punto puede tener un impacto significativo en la disponibilidad y la continuidad del servicio. Para garantizar la alta disponibilidad y la tolerancia a fallos, es importante diseñar sistemas sin puntos únicos de fallo y utilizar estrategias de redundancia y recuperación ante desastres.

## Cómo evitar el tiempo de inactividad al desplegar código nuevo

Al desplegar código nuevo en un entorno de producción, es importante evitar o minimizar el tiempo de inactividad para garantizar una transición fluida y sin interrupciones. Algunas prácticas comunes para lograr esto incluyen:

- Utilizar estrategias de despliegue gradual, como el despliegue en etapas o la implementación canaria, donde se lanza el nuevo código de manera incremental y se monitorea su rendimiento antes de desplegarlo completamente.
- Utilizar entornos de desarrollo y pruebas adecuados para probar y validar el código antes de implementarlo en producción.
- Implementar mecanismos de reversión y respaldo para revertir rápidamente los cambios en caso de problemas inesperados.
- Automatizar el proceso de despliegue y utilizar herramientas de administración de configuración para garantizar la consistencia y reproducibilidad del entorno de producción.

## Clúster de alta disponibilidad (activo-activo/activo-pasivo)

Un clúster de alta disponibilidad es una configuración de sistema en la que múltiples nodos o servidores trabajan juntos para proporcionar un servicio continuo y resistente a fallos. Hay dos tipos principales de clústeres de alta disponibilidad:

- Activo-activo: Todos los nodos en el clúster están activos y comparten la carga de trabajo. Si uno de los nodos falla, otros nodos continúan proporcionando el servicio sin interrupción.
- Activo-pasivo: Un nodo se configura como activo y maneja toda la carga de trabajo, mientras que otros nodos están en espera (pasivo) y solo se activan si el nodo principal falla. Si el nodo activo falla, uno de los nodos pasivos toma su lugar y continúa proporcionando el servicio.

Estos clústeres garantizan una alta disponibilidad al permitir que el servicio se mantenga en funcionamiento incluso si uno o varios nodos fallan.

## Qué es HTTPS

HTTPS (Hypertext Transfer Protocol Secure) es una versión segura del protocolo HTTP que utiliza criptografía para garantizar la seguridad de las comunicaciones en línea. Utiliza un certificado SSL/TLS (Secure Sockets Layer/Transport Layer Security) para establecer una conexión segura entre el cliente y el servidor. HTTPS protege los datos confidenciales, como contraseñas, información personal y datos de transacciones, de posibles ataques y robos de información durante la transferencia.

## Qué es un cortafuegos

Un cortafuegos (firewall) es una barrera de seguridad que controla y filtra el tráfico de red entre una red privada y una red externa, como Internet. Su objetivo principal es proteger la red y los sistemas contra amenazas y ataques no autorizados. Un cortafuegos puede configurarse para permitir o bloquear ciertos tipos de tráfico, según reglas predefinidas, y actúa como una capa de defensa adicional para prevenir accesos no autorizados y proteger la integridad y confidencialidad de los datos.






## Diagrama de la pila web

A continuación se muestra un diagrama que representa la pila web utilizada en los proyectos de seguimiento de sysadmin/devops:

```
+-----------------------+
|                       |
|    Load Balancer      |
|                       |
+-----------|-----------+
            |
            |       +-----------------------+
            +------>|                       |
            |       |    Web Servers        |
            +------>|                       |
            |       +-----------|-----------+
            |                   |
            |                   |     +-----------------------+
            |                   +---->|                       |
            |                   |     |    Database Server    |
            |                   +---->|                       |
            |                   |     +-----------------------+
            |
            |       +-----------------------+
            +------>|                       |
            |       |    Cache Server       |
            +------>|                       |
            |       +-----------------------+
```

El diagrama muestra una configuración típica de una pila web que consta de los siguientes componentes:

- **Load Balancer**: El equilibrador de carga distribuye el tráfico entrante de los clientes entre varios servidores web para mejorar la escalabilidad y la disponibilidad del sistema.

- **Web Servers**: Los servidores web almacenan y sirven las páginas web solicitadas por los clientes. Pueden ejecutar aplicaciones web y manejar solicitudes HTTP.

- **Database Server**: El servidor de bases de datos almacena y gestiona los datos utilizados por la aplicación. Proporciona un entorno seguro y eficiente para el almacenamiento y la recuperación de datos.

- **Cache Server**: El servidor de caché almacena en caché datos frecuentemente accedidos para acelerar la

 entrega de contenido y mejorar el rendimiento general del sistema.

## Acrónimos mencionados

- **LAMP**: Acronimo que representa una pila de tecnología web compuesta por Linux (sistema operativo), Apache (servidor web), MySQL (sistema de gestión de bases de datos) y PHP (lenguaje de programación).

- **SPOF**: Acrónimo de "Single Point of Failure", que se refiere a un componente o punto en un sistema que, si falla, provocará la interrupción o la pérdida total del sistema.

- **QPS**: Acrónimo de "Queries Per Second", que representa la cantidad de consultas realizadas a un sistema de bases de datos por segundo. Es una métrica utilizada para medir el rendimiento y la capacidad de respuesta de un sistema.



