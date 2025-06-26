
<a href='s10_rendimiento_del_trafico.md'>Atrás</a>

## Gestión de la memoria (Buffer Pool/Key Buffer)

* MySQL utiliza memoria (como el `InnoDB Buffer Pool` para tablas InnoDB o el `Key Buffer` para MyISAM) para almacenar en caché datos y bloques de índice usados frecuentemente.
* Con una tabla muy grande, es menos probable que todos los datos y índices relevantes quepan en la memoria caché. Esto significa que MySQL tendrá que ir al disco con más frecuencia, lo que ralentiza las operaciones.

<a href='s10_rendimiento_del_trafico.md'>Atrás</a>
