
Este proyecto de investigación tiene como objetivo monitorizar y analizar la evolución temporal del NDVI (Índice de Vegetación de Diferencia Normalizada) en las principales zonas verdes de los distritos 2 y 3 de Madrid, con el fin de identificar patrones de cambio vegetal y proporcionar herramientas para la gestión ambiental urbana.

🎯 Objetivo Principal
Identificar y cuantificar las zonas verdes que presentan mayor regresión vegetal a lo largo del tiempo mediante el análisis del NDVI, proporcionando datos científicos para la toma de decisiones informadas en políticas de conservación y recuperación ambiental.

📍 Ámbito de Estudio
Distritos analizados: Zona 2 y Zona 3 de Madrid

Tipo de áreas: Parques, jardines públicos, zonas arboladas y espacios verdes urbanos

Parámetro medido: NDVI (Normalized Difference Vegetation Index)

Periodo de análisis: Series temporales multi-anuales

📊 Metodología
1. Extracción de Datos
python
# Proceso de extracción de NDVI
- Obtención de imágenes satelitales multiespectrales
- Cálculo del NDVI: (NIR - Red) / (NIR + Red)
- Procesamiento de series temporales
- Validación y limpieza de datos
2. Procesamiento y Análisis
Extracción de NDVI a partir de imágenes satelitales

Análisis temporal comparativo por estaciones y años

Clasificación por tipologías de zonas verdes

Detección de tendencias (mejora/estabilidad/regresión)

Priorización de áreas que requieren intervención urgente



🛠️ Aplicaciones Prácticas
Gestión Municipal
	Identificación temprana de estrés vegetal

	Optimización de recursos en mantenimiento de zonas verdes

	Evaluación de impacto de políticas ambientales

	Planificación urbana sostenible

	Monitoreo Ambiental
	Alertas tempranas para prevención de degradación

	Seguimiento de intervenciones de mejora

	Benchmarking entre diferentes áreas verdes

	Indicadores de sostenibilidad urbana

Toma de Decisiones
	Priorización de inversiones en áreas críticas
	
	Evaluación de efectividad de programas de conservación

	Comunicación transparente con la ciudadanía

	Base científica para planes de desarrollo urbano

📈 Indicadores Clave
Métricas Cuantitativas
	NDVI promedio por zona y temporalidad

	Tasa de cambio anual del índice de vegetación

	Variabilidad estacional del verdor

	Persistencia temporal de estados vegetativos

Indicadores de Desempeño
	Ranking de salud vegetal por zona verde

	Mapas de calor de salud vegetal

	Series temporales de evolución

	Alertas de degradación temprana

Umbrales de Referencia
python
# Clasificación del estado vegetal
NDVI > 0.6: "Vegetación muy saludable" ✅
NDVI 0.4-0.6: "Vegetación saludable" ✅
NDVI 0.2-0.4: "Vegetación moderada" ⚠️
NDVI < 0.2: "Vegetación en riesgo" ❌
🔬 Metodología Técnica Detallada
Fuentes de Datos
Imágenes satelitales: Sentinel-2, Landsat 8

Resolución espacial: 10-30 metros

Frecuencia temporal: Revisita cada 5-16 días

Periodo histórico: Múltiples años de datos

Procesamiento
Corrección atmosférica de imágenes

Cálculo de NDVI por píxel

Agregación por zona verde

Filtrado de valores atípicos

Suavizado de series temporales

Análisis Estadístico
Tendencias lineales (método de mínimos cuadrados)

Pruebas de significancia estadística

Análisis de varianza entre zonas

Correlaciones con variables climáticas

📱 Dashboard Interactivo
Funcionalidades Principales
	Selección individual de zonas verdes

	Comparativas temporales personalizadas

	Filtros por periodos específicos

	Descarga de informes ejecutivos

Visualizaciones Disponibles
	Evolución temporal con líneas de tendencia

	Distribución estadística por zona verde

	Ranking comparativo de desempeño

	Análisis de tendencias anuales

	Indicadores en Tiempo Real
	Estado actual de cada zona verde

	Tendencias recientes (últimos 6 meses)

	Alertas proactivas de posibles problemas

Recomendaciones de intervención

🎯 Criterios de Priorización
Para Intervención Urgente
python
if (NDVI_promedio < 0.3 and 
    tendencia < -0.01 and 
    variabilidad > 0.1):
    prioridad = "ALTA"
Factores Considerados
Valor absoluto del NDVI

Tendencia temporal (mejora/empeoramiento)

Variabilidad interanual

Importancia social de la zona verde

Potencial de recuperación

📋 Resultados Esperados
Corto Plazo
Identificación de zonas críticas

Alertas tempranas de degradación

Base de datos histórica consolidada

Mediano Plazo
Evaluación de intervenciones realizadas

Optimización de recursos de mantenimiento

Mejora continua del monitoreo

Largo Plazo
Modelos predictivos de evolución vegetal

Integración con políticas urbanísticas

Plataforma ciudadana de participación

👥 Público Objetivo
Gestores Públicos
Departamentos de medio ambiente municipales

Planificadores urbanos

Responsables de parques y jardines

Técnicos e Investigadores
Ambientólogos y ecólogos urbanos

Investigadores en sostenibilidad

Consultores ambientales

Ciudadanía
Asociaciones vecinales

Colectivos ecologistas

Ciudadanos interesados en su entorno

🚀 Cómo Utilizar Este Proyecto
Para Gestores
Identifique zonas prioritarias en el dashboard

Analice tendencias históricas

Planifique intervenciones basadas en datos

Evalúe resultados de forma objetiva

Para Investigadores
Acceda a los datos procesados

Realice análisis específicos

Contribuya con mejoras metodológicas

Publique resultados derivados

Para Ciudadanos
Consulte el estado de su zona verde

Participe en procesos de mejora

Utilice los datos para propuestas vecinales

Divulgue la importancia del verde urbano

📞 Contacto y Contribuciones
Este proyecto está en constante evolución. Para sugerencias, colaboraciones o reporte de problemas, por favor contacte a través de los canales establecidos en el repositorio.

🌳 Juntos por un Madrid más verde y sostenible
<img width="1691" height="458" alt="image" src="https://github.com/user-attachments/assets/bff33cb2-46dd-4dfd-bd1c-10535b642bbb" />



<img width="720" height="443" alt="image" src="https://github.com/user-attachments/assets/e9e89980-41a0-4bcd-b968-9bb228b59556" />



