# Optimización de Campañas de Marketing para Restaurantes mediante Segmentación y Recomendaciones

## Descripción del Proyecto
Este repositorio contiene el proyecto integrador para el curso de Fundamentos de Ciencia de Datos, Estadística y Probabilidad. El objetivo es optimizar estrategias de segmentación de marketing para restaurantes locales en InsightReach, una empresa de marketing digital. Usando datos de clientes y restaurantes (de Yelp API), se integra, analiza y visualiza información para generar insights accionables.

Habilidades demostradas:
- ETL (Extracción, Transformación, Carga) con Pandas.
- Integración de APIs (Yelp) con manejo seguro de credenciales (.env).
- Análisis exploratorio y visualizaciones con Matplotlib/Seaborn.
- Generación de recomendaciones basadas en datos (score ponderado de restaurantes).
- Manejo ético de datos (anonymization).

Para reclutadores: Este proyecto muestra mi capacidad para manejar datos reales/sintéticos, generar insights de negocio y estructurar código reproducible. Contacto: [Tu email o LinkedIn].

## Instalación
1. Clona el repo: `git clone https://github.com/tu-usuario/marketing-segmentation-restaurants.git`
2. Instala dependencias: `pip install -r requirements.txt`
3. Crea un `.env` basado en `.env.example` con tus credenciales de Yelp API.
4. Ejecuta los notebooks en orden (Avance_1 → Avance_2 → Avance_3).

## Uso
- **notebooks/Avance_1.ipynb**: ETL y limpieza de datos de clientes.
- **notebooks/Avance_2.ipynb**: Extracción de datos de Yelp API (Nueva York).
- **notebooks/Avance_3.ipynb**: Visualizaciones y análisis.
- Datos en `/data/` son anonymizados para privacidad.

## Insights Clave
- Chicago concentra la mayoría de clientes (~5384), sugiriendo foco en campañas urbanas.
- Segmentación por estrato socioeconómico revela oportunidades en nichos (ej. vegetarianos de 20-30 años que consumen licor).
- Restaurantes top en NYC: Los Tacos No.1 (score 4.65), basado en rating ponderado.

## Manejo de Datos
Todos los datos son sintéticos/anónimos. Columnas sensibles (emails, teléfonos) han sido redactadas. No se comparten datos reales.

## Licencia
MIT License.
