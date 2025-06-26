
<a href='s10_rendimiento_del_trafico.md'>Atrás</a>

## Uso de índices

* Los índices son estructuras de datos que ayudan a MySQL a encontrar rápidamente filas sin tener que escanear toda la tabla.
* A medida que la tabla crece, los índices también crecen. Aunque los índices aceleran las búsquedas, insertar, actualizar y eliminar registros en una tabla con muchos índices puede ser más lento porque MySQL también tiene que actualizar esas estructuras de índice.
* Si no usas índices adecuados para tus consultas, MySQL tendrá que realizar "escaneos completos de tabla" (table scans), lo que se vuelve extremadamente lento con millones de registros.

<a href='s10_rendimiento_del_trafico.md'>Atrás</a>
