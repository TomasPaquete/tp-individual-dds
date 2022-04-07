# Notas

## Primer Entrega 08/04/2022

### Requerimientos

+ Se debe saber el tipo de una prenda y su precio.
+ Poder calcular el precio en base al estado de la prenda (nueva, promocion, liquidacion).
+ Conocer las ganancias de un dia determinado.
+ Tener en cuenta el medio de pago para una venta determinada.

### Notas

+ La venta tiene asociadas multiples prendas, con sus cantidades y precios.
+ Pueden ser en efectivo o tarjeta, esto modifica el recargo que se aplica al total de la venta.
+ Para la clase Prenda se opto usar composicion, pero una alternativa es usar herencia para modelar la modificacion a su precio.
+ En el caso de Venta se opto usar herencia, podria usarse composcion pero podria traer problemas 
+ Ej: En el caso de una venta en efectivo el parametro que se le pasaria al metodo que calcula el recargo no tendria uso.
+ En el caso de la clase Venta se podria agregar un nroFactura ya que tiene sentido en el dominio a trabajar, pero al no ser requerido por el ejercicio se ignoro.
+ Para cumplir el requisito de poder calcular el total de ventas por dia utilizamos la clase VentasDia para lograrlo, pero se podria obviar o implementar de una forma distinta
+ Una forma diferente seria delegando a la BD o usando otras tecnicas que no vienen al caso para el ejercicio.
