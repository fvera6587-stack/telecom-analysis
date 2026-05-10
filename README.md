📱 Análisis de Comportamiento de Clientes: ConnectaTel
Este proyecto presenta un análisis profundo de los patrones de uso y segmentación de clientes para ConnectaTel, una empresa de telecomunicaciones con operaciones en México y Colombia. El objetivo es transformar datos crudos en estrategias comerciales accionables para optimizar la oferta de servicios y mejorar la retención.

🎯 Objetivo del Proyecto
Identificar patrones de consumo, detectar comportamientos atípicos (outliers) y comprender las necesidades de los diferentes segmentos demográficos. Los resultados sirven como base para:

Diseñar planes de servicios especializados.

Implementar estrategias de retención basadas en datos.

Optimizar la calidad de la captura de información.

📊 Datasets Utilizados
El análisis se basa en tres fuentes de datos principales:

plans.csv: Detalle de los planes (Básico y Premium), incluyendo precios, minutos, mensajes y costos adicionales.

users_latam.csv: Perfil demográfico de los usuarios (edad, ciudad, fecha de registro y plan contratado).

usage.csv: Registros de actividad real, detallando duración de llamadas y cantidad de mensajes enviados.

🛠️ Etapas del Análisis
El proyecto se desarrolló siguiendo un flujo de trabajo de ciencia de datos:

Exploración y Diagnóstico: Identificación de nulos, valores centinela (como -999 en edad) y errores de captura (fechas en 2026).

Limpieza Robusta: Imputación de datos mediante medianas, corrección de tipos de datos y validación estructural de variables.

Análisis Estadístico: Generación de métricas descriptivas por usuario.

Visualización: Histogramas y Boxplots para entender la distribución del consumo y detectar sesgos.

Segmentación Avanzada: Clasificación de usuarios por nivel de uso (Bajo, Medio, Alto) y grupos etarios.

Estrategia de Negocio: Formulación de recomendaciones con métricas de éxito y cronograma de implementación.

🚀 Cómo ejecutar el Notebook
Puedes visualizar y ejecutar el análisis de dos formas:

Opción 1: Google Colab (Recomendado)
Haz clic en el botón "Open in Colab" (si está disponible en el repo) o sube el archivo .ipynb a Google Colab.
https://colab.research.google.com/drive/1zDSN-H11dVb9MZR8iGAEO_l_U1RO9FyC?hl=en 
Carga los archivos CSV contenidos en la carpeta /datasets de este repositorio.

Ejecuta las celdas en orden secuencial.
