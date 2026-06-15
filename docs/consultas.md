## ***Tipos de Operadores mas usados***

| Operador | Tipo de Operador | Descripción |
|-----------|-----------------|-------------|
| `Where()` | Filtrado | Filtra elementos según una condición. |
| `Select()` | Proyección | Selecciona o transforma datos de una colección. |
| `Join()` | Combinación | Une datos de dos colecciones relacionadas. |
| `GroupBy()` | Agrupación | Agrupa elementos según una clave común. |
| `Count()` | Agregación | Cuenta la cantidad de elementos. |
| `Sum()` | Agregación | Calcula la suma de valores numéricos. |
| `Average()` | Agregación | Calcula el promedio de valores numéricos. |
| `Distinct()` | Conjunto | Elimina elementos duplicados. |
| `Take()` | Particionamiento | Obtiene una cantidad específica de elementos. |
| `Skip()` | Particionamiento | Omite una cantidad específica de elementos. |


***INTEGRACIÓN ENTRE CAPAS***

Presentación

↓

Negocio

↓

Acceso Datos

↓

Northwind

***Flujo:***

Usuario → Negocio → LINQ → Datos → Resultado

***BUENAS PRÁCTICAS***

No consultar desde UI.

Evitar consultas repetidas.

Usar DTO.

Documentar repositorios.

Aplicar principio SOLID.

[← Implementación](implementacion.md)

[🏠 Inicio](index.md)

[Siguiente → Conclusiones](conclusiones.md)
