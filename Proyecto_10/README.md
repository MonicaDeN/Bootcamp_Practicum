# Datos:

En el conjunto de datos se observarán columnas nombradas de la manera `[stage].[parameter_type].[parameter_name]` donde `[stage]` indica la etapa del proceso, las opciones son:

* `rougher` - flotación.
* `primary_cleaner` - purificación primaria.
* `secondary_cleaner` - purificación secundaria.
* `final` - características finales.

`[parameter_type]` indica los parámetros de la materia antes, durante o después de la etapa correspondiente, así como el cálculo de las características. Las opciones que puede tener son:

* `input` - parámetros de la materia prima (antes de la etapa).
* `output` - parámetros del producto (al termino de la etapa).
* `state` - parámetros que caracterizan el estado actual de la etapa.
* `calculation` - características de cálculo.

Y `[parameter_name]` indica el nombre del parámetro, las opciones que puede tener son:

* `concentrate` - concentrado de un metal (Ag, Pb, Au).
* `tail` - residuos del producto.
* `sulfate`, `depressant`, `xanthate` - reactivos de flotación.
* `feed_size` - tamaño de las partículas de la alimentación (es un parámetro de la etapa).
* `floatbank` - instalación de flotación.
* `recovery`- cálculo de la recuperación.

# Objetivo:

Construir y entrenar un modelo para optimizar la producción de oro y eliminar los parámetros no rentables.

# Librerías usadas:

pandas | numpy | matplotlib | sklearn