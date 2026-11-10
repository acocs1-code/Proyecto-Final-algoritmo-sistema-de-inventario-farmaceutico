sistema de incentario y ventas para una casa medica y sus clientes, que en este caso son farmacias afiliadas a la casa medica
Proyecto final de Algoritmos, echo con C++
Alan Styven Coc Sunuc
carne: 0910-25-19645

DE QUE TRATA EL PROYECTO
este proyecto consta de dos partes un un mismo sistema, por un lado se encuentra la casa medica que es la principal distribuidora
esta esta encargada de poder llevar el inventario por lote, tambien recibe los pedidos de las farmacias, genera un presupuesto para dichas farmacias
y asi mismo al finalizar el presupuesto esta listo para poder hacer el despacho y el envio, en donde el area de paqueteria hay tres repartidores 
encargados de poder llevar los pedidos a los destinos correspondientes, dandoles un cierto tiempo de entrega y  asi mismo poder confirmar cuando
el repartidor esta libre y cuando esta en una entrega.

Por el otro lado esta la FARMACIA, que consta del mismo sistema unicamente que no tiene la parte de paqueteria, en donde la farmacia de la misma manera, 
puede ingresar sus productos, hacer la separacion por lotes, fecha de venciminento y codigo de barra, tambien puede generar presupuestos para el despacho
hacia los clientes, puede generar presupuesto para poder pedir a casa medica y asi mismo vender al publico


Algunas cosas importantes que pude poner son los siguientes:
el producto siempre saldra el primero del lote que esta a punto de vencer o que la fecha sea proxima
se puede cancelar un pedido, envio o venta y el stock regresa nuvamente al lote donde salio y a la misma cantidad que hay en existencia
Todos lo que el usuario valla a generar se valida, para que el programa no se caiga por un dato malo
tambien se le puso un anti tontos en donde al momento de colocar algo mal no se arruina el programa si no que avisa que se equivoco
los datos se guardan en archivos de texto, asi que no se pierde al cerrar el programa

COMO CORRER EL PROGRAMA

para entrar la primera vez: en usuario: admin, contraseña: 1234, desde ahi se puede ingresar al sistema de la casa medica en donde se puede
crear el sistema de la casa medica y los usuarios quien va a controlar y asi mismo ingresar a los usuario que estaran utilizando en el sistema 
de la farmacia
