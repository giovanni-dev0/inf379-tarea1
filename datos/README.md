# 📁 Carpeta `/datos/`

Esta carpeta contiene los archivos de datos utilizados por los integrantes del grupo para la elaboración de las visualizaciones correspondientes a la Tarea 1 del curso *Visualización de Datos* (INF-379) de la Universidad Técnica Federico Santa María. La estructura está organizada por subdirectorios con el nombre de cada integrante, facilitando la trazabilidad entre los datos utilizados, los criterios de análisis propuestos y las visualizaciones desarrolladas.

Cada conjunto de datos fue construido a partir de fuentes oficiales y cumple con los lineamientos éticos y técnicos requeridos para una visualización responsable, con foco en el contexto latinoamericano del fenómeno migratorio.

---

## ⭐ Carlos Lavin

### Archivos:

- `DatosPobrezaLatam.csv`
- `Perfilmigrante.csv`

### Origen de los datos:

Los archivos fueron construidos a partir de bases oficiales de organismos internacionales y procesados manualmente para su análisis visual:

-`DatosPobrezaLatam.csv`: Reúne datos de pobreza y desempleo en países de América Latina (2023 o año más reciente disponible), extraídos del Banco Mundial, CEPAL y Statista, junto con el Índice de Desarrollo Humano (IDH) proporcionado por el PNUD.

-`Perfilmigrante.csv`: Basado en el informe “Panorama de la población migrante en América Latina y el Caribe” de CEPAL (2024), contiene la composición etaria de la población migrante extranjera en 12 países latinoamericanos.




### Descripción:

Los archivos permiten analizar dos dimensiones clave del fenómeno migratorio en América Latina:

-`DatosPobrezaLatam.csv`: Contiene indicadores de pobreza y desempleo sumados como medida de vulnerabilidad, además del IDH para cada país. Estos datos fueron utilizados para construir un Treemap comparativo.

-`Perfilmigrante.csv`: Muestra la distribución de la población migrante en tres rangos de edad: 0–14, 15–64, y 65+, organizados para construir un Radar Chart que permite comparaciones entre países.


### Propósito:

Los datos fueron utilizados para crear dos visualizaciones enfocadas en las causas estructurales de la migración y en el perfil de quienes migran:

Un **Treemap** que representa la vulnerabilidad económica de cada país como la suma de pobreza y desempleo, y utiliza el color para representar el IDH, permitiendo interpretar simultáneamente desarrollo y desigualdad.

Un **Radar Chart** que ilustra la distribución etaria de la población migrante, revelando si se trata de migración laboral, familiar o forzada según el rango de edad predominante.

Estas visualizaciones permiten responder las preguntas: ¿quiénes migran? y ¿por qué lo hacen?, aportando un enfoque cuantitativo para entender el origen del fenómeno migratorio en la región.

### Consideraciones éticas y técnicas:

Durante el proceso de recopilación de datos, se aplicaron criterios de exclusión para asegurar la coherencia metodológica y ética:

Se excluyeron territorios sin estatus político soberano reconocido (por ejemplo, Islas Malvinas/Falkland, Guayana Francesa, Puerto Rico y otros territorios dependientes).


**Justificación**:
 
Ética: Incluir territorios en disputa podría sesgar la narrativa y reforzar posiciones geopolíticas no consensuadas.

Técnica: Estas regiones tienden a tener datos incompletos o inconsistentes, lo que podría distorsionar los análisis comparativos.

La exclusión fue una decisión consciente y fundamentada en buenas prácticas de visualización de datos.



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

### Archivos utilizados

- `acceso_servicios_2022_2023.csv`  
- `condiciones_laborales_inmigrantes_latam.csv`

### Origen de los datos

Ambos archivos fueron construidos a partir de una recopilación manual y estandarización de cifras públicas disponibles en informes institucionales publicados por organismos internacionales como la **Organización Internacional del Trabajo (OIT)**, la **Organización Internacional para las Migraciones (OIM)**, la **Comisión Económica para América Latina y el Caribe (CEPAL)**, el **Banco Interamericano de Desarrollo (BID)** y el **Alto Comisionado de las Naciones Unidas para los Refugiados (ACNUR)**.

- `acceso_servicios_2022_2023.csv`:  
  Derivado de datos y estimaciones contenidas en informes técnicos sobre inclusión social de personas migrantes, particularmente en relación al **acceso a salud, educación y vivienda** en países receptores como Colombia, Perú, Chile, Ecuador y Brasil.

- `condiciones_laborales_inmigrantes_latam.csv`:  
  Construido con base en estudios y reportes institucionales sobre la **inserción laboral de personas migrantes**, organizando los datos en cuatro categorías laborales: empleo formal, informal, autónomo y temporal.

Ambos conjuntos de datos fueron estructurados para facilitar su visualización a través de gráficos jerárquicos y relacionales.


### Descripción de los archivos

- `acceso_servicios_2022_2023.csv`:  
  Contiene valores porcentuales de acceso de personas migrantes a tres servicios sociales clave —salud, educación y vivienda— por país receptor (Colombia, Perú, Chile, Ecuador, Brasil). Los datos corresponden al período **2022–2023** y fueron armonizados para visualización comparativa.

- `condiciones_laborales_inmigrantes_latam.csv`:  
  Describe la distribución relativa de la población migrante según el tipo de empleo que desempeña (formal, informal, autónomo o temporal) en 10 países latinoamericanos. Las cifras se expresan como porcentajes del total migrante ocupado y fueron organizadas para su representación en gráficos del tipo **Chord Chart**.


### Propósito de los datos

Los datos fueron utilizados para el desarrollo de dos visualizaciones no convencionales:

1. **Gráfico de Sunburst** que muestra la **distribución porcentual del acceso a servicios sociales** por país de acogida.
2. **Gráfico de Chord Chart** que representa la **relación entre países y condiciones laborales predominantes** entre migrantes.

Estas visualizaciones buscan ofrecer una mirada sintética, intuitiva y analíticamente robusta sobre los desafíos de integración de las personas migrantes en América Latina desde una perspectiva multidimensional: social y laboral.


### Consideraciones éticas y técnicas

Durante el proceso de construcción y visualización, se tomaron decisiones metodológicas orientadas a asegurar **coherencia interpretativa**, **representatividad regional** y **alineamiento con buenas prácticas en análisis de datos migratorios**:

- Se excluyeron países con datos notablemente inconsistentes o sin cobertura suficiente en al menos dos de los informes fuente.
- Se priorizó la utilización de fuentes multilaterales reconocidas y públicas.
- Se armonizaron las categorías laborales y sociales para asegurar comparabilidad entre países, respetando definiciones de la **OIT** sobre trabajo decente y de la **CEPAL** sobre acceso a servicios esenciales.


### Justificación de exclusiones y decisiones de diseño

- Algunos países o territorios de baja población migrante (ej. Belice, Surinam) no fueron incluidos debido a la falta de datos desagregados o incompatibilidad en las series temporales.
- En el **Chord Chart**, se aplicó una técnica de diferenciación cromática con etiquetas internas (ej. `"Temporal`) para forzar la correcta asignación de colores y evitar errores de visualización.

Estas decisiones buscan priorizar la claridad visual y la integridad metodológica, evitando distorsiones en la representación de fenómenos complejos y facilitando una lectura responsable y contextualizada del fenómeno migratorio.

---
