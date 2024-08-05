# Análisis de Datos de Acciones con Web Scraping y Visualización

Este repositorio contiene un Jupyter Notebook que demuestra cómo extraer y visualizar datos de acciones utilizando Python. El cuaderno realiza las siguientes tareas:

1. **Extracción de Datos de Acciones para Tesla y GameStop**
   - Utiliza la biblioteca `yfinance` para descargar precios históricos de acciones.
   - Extrae datos para Tesla (TSLA) y GameStop (GME).

2. **Extracción de Datos de Ingresos mediante Web Scraping**
   - Utiliza la biblioteca `requests` para obtener páginas HTML que contienen datos de ingresos.
   - Analiza el HTML utilizando `BeautifulSoup` para extraer información de ingresos para Tesla y GameStop.

3. **Limpieza de Datos**
   - Limpia y procesa los datos de ingresos extraídos, eliminando caracteres no deseados (como signos de dólar, comas) y manejando valores faltantes.

4. **Visualización de Datos**
   - Utiliza `plotly` para crear y mostrar visualizaciones de precios históricos de acciones y datos de ingresos para Tesla y GameStop.

## Instrucciones de Configuración

Para ejecutar este cuaderno, necesitarás tener Python instalado junto con las siguientes bibliotecas:

- `yfinance`
- `pandas`
- `requests`
- `beautifulsoup4`
- `plotly`
