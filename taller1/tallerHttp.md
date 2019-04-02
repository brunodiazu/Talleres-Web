# Glosario


---

* Request:


HTTP Request permite enviar todo tipo de petición HTTP a un 
URL específico y procesar la respuesta del servidor HTTP.

* Response:

HTTP Response es el mensaje que envía el servidor al cliente tras haber 
recibido una petición o HTTP request

* Status Code:

Los códigos de estado de respuesta HTTP indican si se ha completado 
satisfactoriamente una solicitud HTTP específica. Las respuestas se 
agrupan en cinco clases: respuestas informativas, respuestas 
satisfactorias, redirecciones, errores de los clientes y errores de los 
servidores. 

* Methods:

	* GET:El método GET  solicita una representación de un recurso 
específico. Las peticiones que usan el método GET sólo deben recuperar 
datos.

	* POST: El método POST se utiliza para enviar una entidad a un 
recurso en específico, causando a menudo un cambio en el estado o 
efectos secundarios en el servidor.

	* HEAD: El método HEAD pide una respuesta idéntica a la de una 
petición GET, pero sin el cuerpo de la respuesta.

	* OPTIONS: El método OPTIONS es utilizado para describir las 
opciones de comunicación para el recurso de destino.

	* PUT: El modo PUT reemplaza todas las representaciones actuales 
del recurso de destino con la carga útil de la petición.

	* DELETE: 
El método DELETE borra un recurso en específico.

* Header:

 HTTP headers son la parte central de los HTTP requests y responses, y 
transmiten información acerca del navegador del cliente, de la página 
solicitada, del servidor, etc


* Headers:

	** Accept, Accept-Charset, Accept-Encoding

	Accept

	La cabecera de pedido Accept anuncia que tipo de contenido el 
cliente puede procesar, expresado como un tipo MIME. Usando negociación 
de contenido, el servidor selecciona una de las propuestas , la utiliza 
e informa al cliente de la elección a través de  la cabecera de 
respuesta Content-Type .

	Accept-Charset

	La cabecera de pedido Accept-Charset anuncia que tipo de 
caracteres el cliente puede procesar.

	Accept-Encoding

	La cabecera Accept-Encoding anuncia que tipo de compresión el 
cliente puede procesar. Usualmente un algoritmo.

	** Cache-Control

	El  Cache-Controlcampo de encabezado general se utiliza para 
especificar directivas para los mecanismos de almacenamiento en caché 
tanto en las solicitudes como en las respuestas

	** Connection

	The Connection general header controls whether or not the 
network connection stays open after the current transaction finishes. If 
the value sent is keep-alive, the connection is persistent and not 
closed, allowing for subsequent requests to the same server to be done.

	** Cookie, Set-Cookie
	** Host
	** Origin
	** Referer
	** USer-Agent
	** Content-Encoding, Content-Length, Content-Type
	** Location
	** Upgrade


