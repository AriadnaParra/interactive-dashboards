# Dashboard ejecutivo inmobiliario — Andes Capital Real Estate

Proyecto del bootcamp de Análisis de Datos de TripleTen (Sprint 11). Dashboard interactivo para apoyar decisiones estratégicas en el sector inmobiliario.

## Objetivo

Construir un dashboard ejecutivo para Andes Capital Real Estate que permita evaluar su desempeño comercial —ventas, clientes y propiedades— y comprender crecimiento, rentabilidad y comportamiento de clientes para apoyar decisiones estratégicas basadas en datos.

## Qué se hizo

- **Modelado de datos**: diseño de un modelo dimensional con tabla de hechos (`hecho_ventas_propiedades`: transacciones de venta, precio, cliente, canal, fecha) y tablas de dimensión (`dim_clientes`, `dim_propiedades`, `dim_fecha` construida como parte del modelado).
- **Relaciones del modelo**: definición de las relaciones entre tablas de hechos y dimensiones para permitir análisis cruzado (ventas por tipo de cliente, por tipo de propiedad, por periodo).
- **Dashboard interactivo**: construcción de visualizaciones y filtros que permiten explorar ventas, rentabilidad y comportamiento de clientes desde múltiples ángulos.
- **Enfoque estratégico**: diseño pensado para apoyar decisiones de negocio (priorización de segmentos de clientes, tipos de propiedad y canales con mejor desempeño).

## Herramientas

Power BI / Tableau (modelado dimensional y dashboard interactivo).

## Resultado

Proyecto evaluado y **aprobado** por el equipo de revisión de TripleTen.

## Archivo

`notebook.ipynb` — guía del proyecto con la descripción del modelo de datos y los requisitos del dashboard. El archivo del dashboard interactivo (.pbix) se entregó directamente a través de la plataforma del bootcamp.

---
*Proyecto desarrollado por Ariadna Parra como parte del programa Data Analyst de [TripleTen](https://tripleten.com).*
