
<a href='s10_rendimiento_del_trafico.md'>Atrás</a>

## Costo de las operaciones

* **SELECT:** Las consultas `SELECT` sin `WHERE` o con `WHERE` en columnas no indexadas se volverán muy lentas. Las consultas con `WHERE` en columnas indexadas serán rápidas hasta cierto punto, pero incluso la navegación del índice puede llevar más tiempo si el índice es enorme.
* **INSERT:** Las inserciones pueden volverse más lentas porque MySQL no solo tiene que escribir el nuevo registro, sino también actualizar todos los índices asociados con la tabla.
* **UPDATE/DELETE:** Similar a `INSERT`, estas operaciones requieren encontrar el registro (potencialmente usando un índice) y luego modificar o eliminar los datos, actualizando también los índices.

<a href='s10_rendimiento_del_trafico.md'>Atrás</a>
