# Analizador de Código con IA

Aplicación de escritorio desarrollada en Python con Kivy que analiza fragmentos de código fuente para detectar nivel de dificultad y posibles errores usando modelos de Inteligencia Artificial (KNN y Árbol de Decisión). Además, provee feedback hablado, gráficos de métricas y exportación de reportes.

## Características principales

- Interfaz gráfica intuitiva para ingresar código fuente.
- Análisis de líneas, complejidad (basado en palabras clave), errores y tiempo estimado.
- Predicción del nivel de dificultad (Bajo, Medio, Alto) mediante modelos KNN y Árbol de Decisión entrenados.
- Feedback hablado usando pyttsx3.
- Visualización gráfica de métricas del análisis.
- Exportación de reportes en PDF y TXT.
- Visualización histórica de los últimos 5 análisis realizados.
- Almacenamiento local de análisis en base de datos SQLite.

## Requisitos

- Python 3.9 o superior  
- Las siguientes librerías Python (puedes instalarlas con pip):  

## Instalación y uso

1. Clonar el repositorio:
 ```bash
 git clone https://github.com/ludagus/analizador-codigo-ia.git
 cd analizador-codigo-ia

2. Instalar las dependencias
  pip install -r requirements.txt

## USO 

- Escribí o pegá el código que deseás analizar en el área de texto.
- Hacé clic en "Analizar Código" para obtener la predicción del nivel de dificultad, feedback hablado y métricas gráficas.
- Podés exportar el análisis actual a PDF o TXT con los botones correspondientes.
- Visualizá el histórico de los últimos análisis con el botón "Mostrar gráfico histórico".

## Autores:
- Jésica S. Sténico
- Laura R. Pared
