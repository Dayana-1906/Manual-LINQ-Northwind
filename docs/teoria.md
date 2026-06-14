***3.1 LINQ***

LINQ (Language Integrated Query) permite consultar estructuras de datos mediante sintaxis integrada.

Tipos:

- LINQ to Objects

Consulta listas en memoria.

- LINQ to SQL

Consulta bases relacionales.

- LINQ to Entities

Consulta mediante Entity Framework.

- LINQ to XML

Procesamiento XML.

***3.2 Componentes de LINQ***

Origen → Consulta → Ejecución

**Ejemplo:**

var clientes =

db.Customers

.Where(c=>c.Country=="USA")

.OrderBy(c=>c.CompanyName);

[← Introducción](introduccion.md)

[🏠 Inicio](indice.md)

[Siguiente → Arquitectura](arquitectura.md)


