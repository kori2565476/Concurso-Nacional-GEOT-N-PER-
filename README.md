# Tablero Relacional de Alertas Tempranas: Gestión de Brechas en Infraestructura

## Descripción del Proyecto
Este proyecto es un **Sistema de Inteligencia Territorial** desarrollado para la Región Amazonas, diseñado para transformar datos censales y sectoriales en herramientas de soporte para la toma de decisiones públicas. La solución permite auditar, medir y jerarquizar de forma automatizada las brechas de acceso a servicios básicos (Salud y Educación) a nivel distrital.

El sistema supera las limitaciones de los reportes estáticos tradicionales, permitiendo a los gestores públicos identificar "puntos ciegos" territoriales mediante un enfoque de datos relacionales y análisis preventivo.

## Arquitectura Técnica
Hemos implementado un flujo completo de **Ingeniería de Datos (End-to-End)**:

* **Extracción y Procesamiento (ETL):** Scripts en **Python** para el tratamiento de grandes volúmenes de datos demográficos, garantizando limpieza, normalización y estandarización de variables territoriales.
* **Persistencia de Datos:** Arquitectura relacional en **PostgreSQL (Neon Serverless)**, permitiendo consultas complejas (JOINs) entre variables poblacionales y oferta de infraestructura.
* **Visualización Inteligente:** Entorno de **Power BI** conectado vía Direct Query para la exploración dinámica de indicadores de saturación.
* **Control de Versiones:** Repositorio en **GitHub** para asegurar la reproducibilidad, transparencia y escalabilidad del código.

## Principales Capacidades
* **Modelo de Alertas Tempranas:** Cálculo algorítmico de ratios de saturación que categorizan los distritos según su nivel de estrés operativo.
* **Interoperabilidad:** Integración de fuentes oficiales (GEO Perú, MINSA, MINEDU e INEI) bajo una estructura normalizada.
* **Gestión Basada en Evidencia:** Transición de un modelo de gestión reactivo a uno preventivo, priorizando inversiones donde la presión demográfica sobre los servicios es más crítica.

## Objetivos del Sistema
1. **Estandarizar:** Convertir reportes tabulares complejos en bases de datos relacionales auditables.
2. **Visibilizar:** Identificar asimetrías microterritoriales que los indicadores macro regionales ocultan.
3. **Optimizar:** Facilitar la priorización de inversiones estatales basándose en la demanda real y no en aproximaciones intuitivas.

---

### ¿Cómo usar este repositorio?
1. **Datos:** Algunos scripts sobre el ETL se encuentran el rama main.

*Proyecto desarrollado en el marco de la Geotón Perú 2026.*
