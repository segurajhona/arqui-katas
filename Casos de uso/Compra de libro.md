# Caso: Un cliente desea comprar un libro en formato electronico
## Precondicion: el cliente esta logueado en el sistema con una sesion iniciada
## Pasos:
1. El cliente ingresa a la "tienda"
2. El sistema le muestra un listado de libros con precios acorde a su region
3. El cliente filtra la lista de libros segun el criterio que desee
4. El cliente agrega un libro en formato electronico al carrito
5. El cliente completa la compra 
6. El centro de cobros le solicita sus datos y el medio de pago
7. El centro de cobros realiza la operacion 
8. El modulo de notifiaciones envia una notificacion al cliente informando que la compra se realizo con exito
9. El cliente elige descargar el libro 
10. El visualizador de documentos proporciona el libro
    1. El generador de documentos revisa la cache de documentos mas solicitados
    2. [Fallo en cache] El generador de documentos solicita la plantilla del documento a la base de verdad 
    3. [Fallo en cache] El generador de documentos genera el archivo final


# Caso: Un cliente desea comprar un libro en formato arboles muertos
## Precondicion: el cliente esta logueado en el sistema con una sesion iniciada
## Pasos:
1. El cliente ingresa a la "tienda"
2. El sistema le muestra un listado de libros con precios acorde a su region
3. El cliente filtra la lista de libros segun el criterio que desee
4. El cliente agrega un libro en formato de arboles muertos al carrito
5. El cliente completa la compra 
6. El centro de cobros le solicita sus datos y el medio de pago
7. El centro de cobros realiza la operacion 
8. El modulo de notifiaciones envia una notificacion al cliente informando que la compra se realizo con exito
9. El sistema inicia el envio del libro al domicilio del cliente
10. El modulo de notificaciones notifica al cliente acerca del estado de envio del libro 