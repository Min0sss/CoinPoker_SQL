# Caso de Estudio: Análisis de Abandono en CoinPoker

Este repositorio contiene el diseño y la estructura de la base de datos relacional utilizada para el análisis de retención de usuarios en la sala de poker.

## Enlace al Caso de Estudio Completo
El análisis profundo, las métricas de negocio analizadas y el dashboard interactivo final se encuentran documentados en Notion:
 **[Ver Caso de Estudio Completo en Notion](https://vast-century-459.notion.site/Guillermo-Contreras-Portafolio-de-Anal-tica-de-Datos-368b566267a4807ba2a8c4d0e07c6bdf?source=copy_link)**

## Estructura del Proyecto
* `/sql/database_structure.sql`: Script definitivo con la creación del esquema de base de datos en SQL Server (Tablas de Hechos y Dimensiones).

## Arquitectura de Datos
El proyecto implementa un **Modelo Estrella (Data Warehouse)** optimizado para analítica y Business Intelligence:
* **Tablas de Hechos:** `fact_table_activity`, `fact_cashier_transactions`, `fact_support_tickets`, `fact_rake_finance`.
* **Tablas de Dimensiones:** `dim_users`, `dim_tables`, `dim_support_types`.

---
*Proyecto de práctica analítica - Mayo 2026.*