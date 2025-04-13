# 📁 Carpeta `/datos/`

Esta carpeta contiene los archivos de datos utilizados por los integrantes del grupo para la elaboración de las visualizaciones correspondientes a la Tarea 1 del curso *Visualización de Datos* (INF-379) de la Universidad Técnica Federico Santa María. La estructura está organizada por subdirectorios con el nombre de cada integrante, facilitando la trazabilidad entre los datos utilizados, los criterios de análisis propuestos y las visualizaciones desarrolladas.

Cada conjunto de datos fue construido a partir de fuentes oficiales y cumple con los lineamientos éticos y técnicos requeridos para una visualización responsable, con foco en el contexto latinoamericano del fenómeno migratorio.

---

## ⭐ Carlos Lavin

[aquí contenido carlos]

---

## ⭐ Giovanni Mealla

### Archivos:

- `porcentaje_migrantes_latam.csv`
- `migrantes_stock_1990_2024.csv`

### Origen de los datos:

Ambos archivos fueron construidos a partir de tablas oficiales del dataset **International Migrant Stock 2024**, publicado por el *United Nations Department of Economic and Social Affairs (UNDESA)*:

- `porcentaje_migrantes_latam.csv`: Derivado de la **Tabla 3** (“International migrant stock as a percentage of the total population by country or area of destination, 1990–2024”).
- `migrantes_stock_1990_2024.csv`: Derivado de la **Tabla 1** (“International migrant stock at mid-year by country or area of destination, 1990–2024”).

Enlace oficial de la fuente: [https://www.un.org/development/desa/pd/content/international-migrant-stock](https://www.un.org/development/desa/pd/content/international-migrant-stock)

### Descripción:

Los archivos contienen información de países latinoamericanos, reorganizada para facilitar el análisis visual comparativo a lo largo del tiempo:

- `porcentaje_migrantes_latam.csv`: Contiene el porcentaje de población migrante respecto al total nacional para los años 1990, 1995, 2000, 2005, 2010, 2015, 2020 y 2024.
- `migrantes_stock_1990_2024.csv`: Contiene los valores absolutos del stock migrante para los años 1990 y 2024, utilizados para calcular la tasa de crecimiento anual compuesta (CAGR).

### Propósito:

Los datos fueron utilizados para desarrollar dos visualizaciones no convencionales:

1. Un **gráfico de burbujas animado** que muestra cómo ha evolucionado el porcentaje de población migrante en cada país.
2. Una **nube de palabras (Word Cloud)** que representa visualmente la tasa de crecimiento de la población migrante entre 1990 y 2024.

Estas visualizaciones permiten identificar tanto patrones estables como transformaciones dinámicas en los flujos migratorios de América Latina, aportando una mirada cuantitativa al análisis de impacto proporcional y crecimiento regional del fenómeno.

### Consideraciones éticas y técnicas:

Durante la depuración de los datos, se decidió excluir territorios y regiones con estatus político no resuelto o en situación colonial, tales como:

- Islas Malvinas / Falkland Islands
- Guayana Francesa
- Puerto Rico
- Otros territorios de ultramar, caribe o bajo administración extranjera

**Justificación**:

- Desde una perspectiva ética en la visualización de datos, incluir regiones con conflictos de soberanía puede introducir sesgos narrativos no intencionados, y reforzar posturas geopolíticas no consensuadas internacionalmente.
- Desde una perspectiva técnica, estos territorios suelen presentar registros incompletos, poblaciones muy reducidas o ausencias en las series temporales, afectando la representatividad y consistencia visual del conjunto. Su inclusión podría distorsionar escalas, desbalancear interpretaciones o generar resultados estadísticos erróneos.

La exclusión fue una decisión consciente, fundamentada en principios de integridad metodológica, claridad interpretativa y compromiso con buenas prácticas en visualización de datos.

---

## ⭐ Ignacio Alfaro

[aquí contenido ignacio]

---