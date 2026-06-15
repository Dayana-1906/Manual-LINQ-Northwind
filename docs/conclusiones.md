## ***Conclusiones***

LINQ constituye una herramienta eficiente para gestionar consultas dentro de arquitecturas multicapa.

Su integración con Northwind permite implementar sistemas mantenibles y alineados con prácticas modernas de ingeniería de software.

<img src="assets/img/github_pages.png" width="450">

## ***Resultados obtenidos***

La implementación de LINQ dentro de una arquitectura multicapa utilizando C# y la base de datos Northwind permitió optimizar el acceso y procesamiento de datos mediante consultas más claras, reutilizables y mantenibles. Se evidenció una reducción en la cantidad de código repetitivo respecto a enfoques tradicionales.

## ***Limitaciones***

El presente manual se centra en consultas desarrolladas con LINQ sobre un entorno académico utilizando Northwind, por lo que no contempla escenarios empresariales de alta concurrencia, grandes volúmenes de datos o técnicas avanzadas de optimización y consultas distribuidas.

## ***Trabajo futuro***

Como trabajo futuro se propone extender la implementación mediante el uso de Entity Framework Core, patrones Repository y Unit of Work, así como incorporar pruebas unitarias y métricas de rendimiento para evaluar el comportamiento de LINQ en aplicaciones de mayor escala.

## ***Recomendaciones***

Se recomienda utilizar LINQ principalmente dentro de la capa de negocio y acceso a datos para mantener una adecuada separación de responsabilidades. Además, es aconsejable documentar las consultas implementadas y evitar operaciones innecesarias sobre colecciones extensas.

## ***Aprendizajes***

Durante el desarrollo del manual se comprendió el funcionamiento de LINQ como mecanismo de integración de consultas dentro de C#, permitiendo aplicar conceptos de filtrado, proyección, agrupación y transformación de datos dentro de una arquitectura multicapa.

## Referencias 

1. Microsoft Learn. **Language Integrated Query (LINQ)**. https://learn.microsoft.com/es-es/dotnet/csharp/linq/

2. Microsoft Learn. **Entity Framework (EF)**. https://learn.microsoft.com/es-es/ef/
   
[← Consultas](consultas.md)

[🏠 Inicio](index.md)
