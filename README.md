# evidencia_de_la_semana
Valentina Huenchiñir, Fernanda Muñoz, María josé Powell
Desarrollo - Ud. junto a un compañer@:
1.)  Identifique las principales clases del contexto descrito.
   Clases : 
Cliente
Cuenta
Carrito de compras
Usuario web
Pedido
Producto
Estado de producto
Medio de pago
Familia de productos 


2.) Identifique las clases que se relacionen entre sí, y el tipo de relación identificada.


Relaciones :  


El cliente está vinculado a una cuenta (ASOCIACIÓN )  
El carro de compras está asociado con una única cuenta (Dependencia) 
El usuario web tienen que estar vinculado a un carrito de compras (Dependencia) 
La cuenta tiene varios los pedidos (Dependencia) 
El cliente está vinculado a un usuario web (no todos los clientes necesariamente deben estar vincula a un usuario web) (ASOCIACIÓN) 
El pedido puede estar relacionado a varios medios de pagos o a ninguno (ASOCIACIÓN)  
Cada cuenta estás tiene  varios medio de pago (ASOCIACIÓN) 
El pedido tiene varios productos (ASOCIACIÓN) 
El carrito de compras está relacionado con los productos (ASOCIACIÓN) 
Cada producto puede estar asociado a una familia de productos (ASOCIACIÓN) 
Cada pedido tiene un estado (ASOCIACIÓN) 
Cada usuario tiene un estado (ASOCIACIÓN)
Familia de productos está relacionada exactamente a productos (ASOCIACIÓN)  


3.) Para las relaciones que se requiera, identifique las multiplicidades asociadas.
Multiplicidades
Cliente a cuenta: 1 - 1
Carro de compras a cuenta: 1 - 1
Usuario web a carrito de compras: 1 - 1
Cuenta a pedidos: 0 - muchos
Cliente a usuario web: 0 - 1
Pedido a medio de pago: 0 - muchos
Cuenta a vario de pagos: 0 - muchos
Carrito de compra a productos: 0 - muchos
Producto a familia de productos: 0 - muchos
Pedido a productos: 0 - muchos
Familia de productos a productos: 1 - muchos  
Pedido a estado: 1 - 1
Usuario web a estado: 1 - 1

evidencia del UML
![image](https://github.com/mjosepc/evidencia_de_la_semana/assets/142420543/9e7a9dcb-03c8-46b4-9ded-2c6ed18dd23a)
codigo generado
![image](https://github.com/mjosepc/evidencia_de_la_semana/assets/142420543/9ed2d2a0-4bfb-4b46-a729-37f17740041e)

