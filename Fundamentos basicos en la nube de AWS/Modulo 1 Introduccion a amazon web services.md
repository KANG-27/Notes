<!-- by kevin niño 
Esto realmente es lo mismo que esta en el curso de aws pero yo lo 
vuelvo a escribir para que la información sea mas clara para mi.
-->

Fundamentos basicos de la nube de AWS

Este curso lo estoy haciendo en aws skillbuilder si quieres saber mas del curso esta en este enlace
https://explore.skillbuilder.aws/learn/course/1420/play/97910/fundamentos-de-la-nube-de-aws-para-profesionales-espanol-latam-aws-cloud-practitioner-essentials-latam-spanish-na

---------------- Modulo 1 Introducción a AMAZON WEB SERVICES ----------------

Que es un modelo cliente servidor 


Cliente                             Servidor
+-----------+                       ---------
|           |                       | ----- |
|           |   ------------->      | ----- |
+-----------+                       | ----- |
+-----------+   <------------       |       |
|      -----|                       |       |
+-----------+                       ---------


Cliente:
    En pocas palabras el cliente es un pc desde un navegador o una aplicación donde este hace petciones a dicho servidor 

Servidor:
    Puede ser un servicio el ejemplo que ponen es Aazon Elastic Compute Cloud (Amazon EC2), este es un servidor virtual

Un ejemplo puede ser un cliente solicita saber que precio tiene un articulo dentro de amazon entonces busca en la pagina y el servidor es el que cumple en evaluar los detalles de la petición y la cumple devolviendole la información al cliente 

Pago por uso  
Esto aparece en el video a lo que se refiere es que solo se paga por lo que se necesita o usa algo que enfatizaban eran las instancias a lo que se refiern de instancias era hacia el espacio o capacidad de consulta de peticiones esto puede ayudar a no tener que pagar mucho dinero si no tiene que usar mucho nivel de computo como lo puede ser en el lado del servidor si una empresa tiene un servidor fisicio tendria que ampliar las capacidades de este servidor en cambio en aws solamente tendria que decir que tanto más necesita y amazon se encargaria de generar dichos recursos y se cobra como dije anteriormente por lo que se usa


Computo en la nube
Entrega de recursos bajo recursos como lo hablaba anteriormente se utiliza lo que se necesita.

Modelo de implementación para el computo en la nube

Si una empresa decide escoger una estrategia en la bube debe tener en cuenta varios factores los cuales son:

Componentes necesarios de las aplicaciones en la nube: Esto se refiere a los distintos servicios y recursos que necesitan para iniciar la implementación en la nube. Esto podria incluir servicios de almacenamiento como bases de datos, servicios de computo, redes, entre otros.

Herramientas de administración de recursos preferidos: en el video hablaban que aws tiene diversos servicios de tal manera que dan una amplia seleccion de los mismos.

Requisitos de infraestructura de TI heredadas: En el caso de que exista infraestructura heredada se debe llevar a una migrar o hacer una integracón exitossa de la nube. Esto puede ser aspectos de compatibilidad en sistemas existentes y otros factores que deben ser considerados al trasladar la infraestructura heredada a la nube.


Hay tres modelos de implementación de computo en la nube las cuales son:

Implementacion basada en la nube

El modelo de implemantacion basado en la nube lo que hace es migrar las aplicaciones existentes a la nube o diseñar y crear nuevas aplicaciones en la nube. Hay dos opciones de hacer esto uno de estas es de bajo nivel la cual requiere que el personal de TI las administre, y el otro es crearlas por medio de servicios de nivel superior los cuales reducen los requisitos de administración, arquitectura y escalado de la infraestructura principal.

Implementación en las instalaciones


