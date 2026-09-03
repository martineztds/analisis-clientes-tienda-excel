# Análisis de Clientes y Compras — Tienda Online (Excel)

Análisis de un dataset de 515 clientes de una tienda online que opera en el sur de Asia (Afganistán, Bangladesh, India, Nepal, Pakistán y Sri Lanka), con el objetivo de identificar patrones de compra por país, categoría de producto y periodo de tiempo, y proponer recomendaciones de negocio basadas en los hallazgos.

## Proceso

1. **Diagnóstico de calidad de datos** — identificación de duplicados, valores vacíos, inconsistencias de formato de texto y fechas mezcladas en distintos formatos regionales.
2. **Limpieza de datos con Power Query** — eliminación de duplicados, normalización de texto y fechas (incluyendo la resolución de ambigüedades entre formatos día/mes/año), y tratamiento de valores negativos y vacíos según el contexto de cada columna.
3. **Análisis con fórmulas y tablas dinámicas** — 10 preguntas de negocio resueltas sobre compras, clientes y satisfacción.
4. **Dashboard** — panel visual con gráficos de barras, líneas y pastel, más una versión interactiva con filtros (segmentación de datos) y tarjetas de KPI dinámicas.
5. **Conclusiones** — hallazgos clave y una recomendación de negocio.

## Herramientas usadas

Excel (fórmulas, tablas dinámicas, gráficos, formato condicional) y Power Query.

## Hallazgos principales

- El total de compras limpio asciende a **$4,786,627**, distribuido entre 484 clientes válidos.
- **Pakistán** es el país líder tanto en cantidad de clientes (89) como en monto total de compras ($901,880).
- **Clothing** es la categoría con mayor monto comprado ($955,529), pero tiene uno de los ratings promedio más bajos (2.84) — mientras que **Furniture**, con menor facturación, tiene el mejor rating (3.21).
- La distribución de clientes por género es exactamente equilibrada (242 hombres, 242 mujeres).
- 2023 y 2024 fueron los años con mayor monto de compras (~$1.5M cada uno); 2025 muestra cifras menores, pero los datos de ese año solo cubren hasta mayo.

## Estructura del archivo

| Hoja | Contenido |
|---|---|
| `Sobre este Análisis` | Resumen del proyecto y metodología |
| `Data Profiling` | Diagnóstico de calidad de datos por columna |
| `Datos_Crudos` | Dataset original, sin procesar |
| `Datos_Limpios` | Dataset final, limpio y estructurado |
| `Preguntas` | 10 preguntas de negocio resueltas |
| `Evidencia Respuestas` | Tablas dinámicas de respaldo para cada respuesta |
| `Gráficos` | Dashboard con 3 visualizaciones (barras, líneas, pastel) |
| `Dashboard` | Versión interactiva con filtros y KPIs dinámicos |
| `Conclusiones` | Hallazgos finales y recomendación de negocio |

## Cómo revisarlo

Descarga el archivo `.xlsx` y ábrelo en Excel (algunas funciones interactivas, como la segmentación de datos, no se visualizan correctamente en visores en línea de GitHub).
