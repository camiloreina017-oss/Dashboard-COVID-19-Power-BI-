# Dashboard Estadístico de Fallecidos por COVID-19 en Colombia

![Dashboard](./Dashboard%20de%20fallecidos%20%20de%20covid.png)

### ¿Qué problema resuelve?
Centraliza y visualiza las estadísticas clave sobre fallecimientos por COVID-19 en Colombia para analizar patrones epidemiológicos por tipo de contagio, edad, género y ubicación geográfica.

###  Tecnologías utilizadas
- **Power BI Desktop:** Modelado de datos y diseño del panel visual.
- **DAX:** Creación de medidas personalizadas (`Edad Promedio`, `Total Fallecidos`, `% Contagio Comunitario`).
- **Power Query:** Limpieza, transformación y estructuración de la fuente de datos.

###  Origen de los datos y Limpieza
- **Fuente de datos:** Registros oficiales de casos reportados de COVID-19 en Colombia (Datos Abiertos).
- **Limpieza realizada:** Normalización de nombres de departamentos y municipios, filtrado de datos nulos, estandarización de categorías de contagio (*Comunitaria, Relacionado, Importado*) y homologación del campo de sexo.

###  Principales Conclusiones del Tablero
1. **Predominio del contagio comunitario:** El **78%** de los contagios corresponden a transmisión comunitaria, afectando principalmente a las ciudades y departamentos con mayor densidad poblacional como Bogotá, Medellín y Barranquilla.
2. **Impacto en adultos mayores y distribución por sexo:** La edad promedio de los fallecidos es de **67 años**, concentrándose la mayor mortalidad en el rango de 60 a 80 años. Además, el **60.68% (9.941 casos)** de los fallecidos corresponden a hombres, frente al **39.32% (6.442 casos)** en mujeres.

### ¿Cómo se ejecuta?
Para visualizar de manera interactiva, descarga el archivo `.pbix` del repositorio y ábrelo en **Power BI Desktop**.
