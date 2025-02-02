# R_projects
Un repertorio de proyectos hechos en el último cuatrimestre.

# Análisis de Efectos de Restricciones y Periodos Festivos en la Incidencia de COVID-19 en Canarias

Este proyecto tiene como objetivo analizar el impacto de la relajación de restricciones y los periodos festivos en la incidencia de casos de COVID-19 en las Islas Canarias. Utilizando datos públicos de casos confirmados por municipio y fecha, se exploran patrones de comportamiento en la propagación del virus tras eventos clave como la finalización del confinamiento, festividades locales, y la eliminación de medidas restrictivas como el uso de mascarillas en exteriores.

## Descripción del Proyecto

El proyecto se centra en responder a la siguiente pregunta: **¿Se observa un efecto rebote en los casos de COVID-19 tras la relajación de restricciones o durante periodos festivos?** Para ello, se analizan datos de casos confirmados en diferentes municipios e islas de Canarias, comparando la incidencia antes y después de eventos específicos.

### Características principales:
- **Análisis temporal**: Se estudian periodos específicos alrededor de festividades y cambios en las restricciones.
- **Visualización de datos**: Uso de gráficos de barras para representar la evolución de casos diarios, con líneas verticales que marcan eventos clave.
- **Enfoque geográfico**: Se analizan tanto datos a nivel municipal como insular para identificar patrones locales y generales.

## Resultados

Los gráficos generados muestran la evolución de los casos de COVID-19 en los periodos analizados, permitiendo identificar posibles aumentos en la incidencia tras la relajación de restricciones o durante festividades. Se observan patrones que sugieren un efecto rebote en algunos casos, aunque la magnitud varía según el evento y la localización.

## Requisitos

Para ejecutar el código, es necesario tener instaladas las siguientes librerías de R:
- `ggplot2`
- `dplyr`
- `lubridate`
- `scales`

## Cómo Usar

1. Clona el repositorio.
2. Abre el script en RStudio o cualquier entorno de R.
3. Descomprime la carpeta con el dataset.
4. Asegúrate de tener el archivo de datos `cv19_municipio-residencia_casos.csv` en el directorio correcto.
5. Ejecuta el script para generar los gráficos y visualizar los resultados.

## Contribuciones

Las contribuciones son bienvenidas. Si encuentras algún error o tienes sugerencias para mejorar el análisis, no dudes en abrir un issue o enviar un pull request.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.
