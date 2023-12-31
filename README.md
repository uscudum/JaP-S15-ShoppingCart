# JaP-S15-ShoppingCart

Propuesta:

La empresa "Barraca Ladrillos SRL" solicita al equipo de Jóvenes a Programar un software para control de stock de mercaderías y un carrito. Necesitan que el software tenga las siguientes funcionalidades:

- Consumir de un API una lista de productos, mínimo deberán poseer los campos: identificación (debe ser único), nombre, descripción, cantidad en stock, costo asociado al producto (en pesos). Pueden inventar un JSON, minimo 20 productos.
  
- Añadir al carrito. Se debe poder elegir/seleccionar los productos que deseo comprar a un carrito.

- El carrito deberá mostrar en todo momento el costo del total de la compra: Si paga en efectivo hay 10% de descuento. Si paga con
crédito hay un 7% de aumento. Con débito se mantiene el precio.

- Los datos ingresados deben ser consistentes (si se genera un movimiento de
stock, el mismo debe verse reflejado en el stock del producto).

- Debe funcionar adecuadamente en celulares.

Desafíense:
- En el carrito, por cada producto crear un botón "ELIMINAR" para quitar dicho producto.
- Crear un botón "COMPRAR" que nos muestre el total de la compra realizada. (Pueden utilizar un
prompt o un alert por ejemplo)

Puede que les sea útil la siguiente documentación:
https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelector
https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelectorAll
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/stringify
https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/parseInt
https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/parseFloat
https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/change_event
