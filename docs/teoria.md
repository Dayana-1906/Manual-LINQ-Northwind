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

***Componentes de una consulta LINQ***

1 Origen

2 Consulta

3 Ejecución

**Ejemplo:**

var resultado=

clientes

.Where(x=>x.Ciudad=="Quito");

**Ejecución diferida**

Deferred Execution

**Ejemplo:**

var consulta=

clientes.Where(x=>x.Activo);

**Ejecución inmediata**

.ToList()

.First()

.Count()

**Lambda Expressions**

x=>x.Nombre

**Expresiones Lambda vs Query Syntax**

Comparar:

from c in clientes

select c

vs

clientes.Select()

[← Introducción](introduccion.md)

[🏠 Inicio](index.md)

[Siguiente → Arquitectura](arquitectura.md)


