Sí. Te lo doy completo y listo para copiar directamente al README.md, usando <pre> para que la estructura del repositorio se mantenga correctamente en GitHub.

Introducción a la Ciencia de Datos

Material oficial del curso Introducción a la Ciencia de Datos para las carreras de Ingeniería Civil Agrícola e Ingeniería Ambiental de la Facultad de Ingeniería Agrícola, Universidad de Concepción.

El curso introduce los fundamentos de la ciencia de datos mediante actividades prácticas utilizando Python y Google Colab. A lo largo del curso, los estudiantes aprenderán a organizar, preparar, analizar, visualizar e interpretar datos, así como a aplicar métodos introductorios de aprendizaje automático a problemas de ingeniería agrícola y ambiental.

Los notebooks están diseñados para ejecutarse directamente en Google Colab, por lo que no es necesario instalar Python, Anaconda ni otro software en el computador.

⸻

¿Cómo utilizar este repositorio?

1. Abra el notebook correspondiente al módulo.
2. Haga clic en Open in Colab o abra el notebook directamente desde Google Colab.
3. Ejecute las celdas en el orden propuesto.
4. Realice las actividades y ejercicios incluidos en cada notebook.
5. Guarde una copia del notebook en su Google Drive si desea conservar su trabajo.

⸻

Organización del repositorio

<pre>
Curso_Introduccion_Ciencia_Datos/
│
├── README.md
├── LICENSE
│
├── Notebooks/
│   ├── M01_Primeros_pasos_Python_Google_Colab.ipynb
│   ├── M02_01_Importacion_Exploracion_Datos.ipynb
│   ├── M02_02_Seleccion_Manipulacion_Datos.ipynb
│   ├── M02_03_Limpieza_Preprocesamiento.ipynb
│   ├── M02_04_Agregacion_Exportacion.ipynb
│   ├── M03_Exploracion_Visualizacion.ipynb
│   ├── M04_Analisis_Datos.ipynb
│   ├── M05_Aprendizaje_Automatico.ipynb
│   └── M06_Proyecto_Integrador.ipynb
│
├── Datasets/
│
└── Static/
    └── Imgs/
</pre>

⸻

Contenidos del curso

Módulo 1. Introducción a la Ciencia de Datos

Introducción al entorno de trabajo que utilizaremos durante el curso y a los conceptos fundamentales de Python necesarios para comenzar a trabajar con datos.

Contenidos

* Introducción a la ciencia de datos.
* Google Colab y Jupyter Notebook.
* Primeros pasos con Python.
* Variables y tipos de datos.
* Operaciones básicas.
* Listas y diccionarios.
* Librerías para ciencia de datos.
* Introducción a Pandas, NumPy y Matplotlib.
* Introducción a DataFrames.

Notebook

M01_Primeros_pasos_Python_Google_Colab.ipynb

⸻

Módulo 2. Organización y Preparación de Datos

Herramientas para organizar, importar, explorar, limpiar y preparar datos antes de realizar un análisis. Las actividades utilizarán principalmente datos reales relacionados con clima, agricultura, medio ambiente y recursos naturales.

2.1 Importación y exploración inicial de datos

* Organización de archivos y directorios.
* Formatos de archivos.
* Importación de datos.
* Archivos CSV y Excel.
* DataFrames y Series.
* Filas y columnas.
* Tipos de datos.
* Exploración mediante head(), tail(), shape, columns, dtypes e info().
* Manejo de fechas.
* Identificación de valores faltantes.
* Identificación de fechas faltantes en series temporales.

Notebook:
M02_01_Importacion_Exploracion_Datos.ipynb

2.2 Selección y manipulación de datos

* Índices en DataFrames.
* Selección de filas y columnas.
* Uso de .loc e .iloc.
* Filtrado mediante condiciones.
* Selección por fechas.
* Ordenamiento de datos.
* Modificación de columnas.
* Operaciones sobre variables.

Notebook:
M02_02_Seleccion_Manipulacion_Datos.ipynb

2.3 Limpieza y preprocesamiento de datos

* Control de calidad de datos.
* Identificación y tratamiento de datos faltantes.
* Registros duplicados.
* Valores inválidos.
* Tipos de datos incorrectos.
* Conversión de tipos de datos.
* Renombrado de variables.
* Identificación de valores únicos.
* Preparación de datos para análisis.

Notebook:
M02_03_Limpieza_Preprocesamiento.ipynb

2.4 Agregación y exportación de datos

* Agrupación de datos.
* Agregación temporal.
* Uso de groupby().
* Uso de resample().
* Agregación diaria, mensual y anual.
* Exportación de resultados.
* Archivos CSV y Excel.

Notebook:
M02_04_Agregacion_Exportacion.ipynb

⸻

Módulo 3. Exploración y Visualización de Datos

Introducción al análisis exploratorio y a la representación gráfica de datos para describir los datos e identificar características, relaciones y patrones.

Contenidos

* Estadística descriptiva.
* Mínimos y máximos.
* Media, mediana y moda.
* Percentiles.
* Medidas de dispersión.
* Agrupación y resumen de datos.
* Histogramas.
* Distribuciones.
* Series de tiempo.
* Diagramas de dispersión.
* Boxplots.
* Identificación de valores atípicos.
* Análisis exploratorio de datos.
* Visualización de datos con Python.

Notebook

M03_Exploracion_Visualizacion.ipynb

⸻

Módulo 4. Análisis e Interpretación de Datos

Aplicación de métodos básicos para estudiar relaciones entre variables, identificar patrones y realizar predicciones sencillas a partir de datos.

Contenidos

* Correlación.
* Regresión lineal.
* Significancia estadística.
* Predicciones básicas.
* Identificación de patrones.
* Tendencias.
* Estacionalidad.
* Variabilidad temporal.
* Interpretación de resultados.
* Comunicación de resultados.
* Elaboración de gráficos de calidad científica.

Notebook

M04_Analisis_Datos.ipynb

⸻

Módulo 5. Introducción al Aprendizaje Automático

Introducción a conceptos y métodos básicos de aprendizaje automático y sus aplicaciones en ingeniería agrícola y ambiental.

Contenidos

* Introducción al aprendizaje automático.
* Aprendizaje supervisado y no supervisado.
* Variables predictoras y variable objetivo.
* Entrenamiento y evaluación básica de modelos.
* Regresión y clasificación.
* Árboles de decisión.
* Agrupamiento de datos (clustering).
* Aplicaciones en ingeniería agrícola y ambiental.

Notebook

M05_Aprendizaje_Automatico.ipynb

⸻

Módulo 6. Proyecto Integrador

Aplicación de las herramientas desarrolladas durante el curso mediante un proyecto práctico basado en datos reales.

El proyecto permitirá integrar las principales etapas de un flujo de trabajo de ciencia de datos:

<pre>
Datos
  │
  ▼
Preparación
  │
  ▼
Exploración
  │
  ▼
Visualización
  │
  ▼
Análisis
  │
  ▼
Modelación
  │
  ▼
Comunicación de resultados
</pre>

Los estudiantes deberán aplicar las herramientas aprendidas para formular preguntas, preparar y analizar un conjunto de datos, interpretar los resultados obtenidos y comunicarlos de manera clara.

Notebook

M06_Proyecto_Integrador.ipynb

⸻

Datos utilizados

Durante el curso se trabajará principalmente con conjuntos de datos reales relacionados con:

* Agricultura.
* Clima.
* Medio ambiente.
* Recursos hídricos.
* Recursos naturales.

Parte de las actividades utilizará series climáticas obtenidas del Explorador Climático CR2, incluyendo datos de estaciones ubicadas en la Región de Ñuble.

Los archivos necesarios para las actividades estarán disponibles en la carpeta Datasets/ o serán proporcionados durante el desarrollo del curso.

⸻

Herramientas

Durante el curso utilizaremos principalmente:

* Python como lenguaje de programación.
* Google Colab como entorno para ejecutar los notebooks.
* Pandas para organización, preparación y análisis de datos.
* NumPy para operaciones numéricas.
* Matplotlib para visualización de datos.
* Scikit-learn para métodos introductorios de aprendizaje automático.
* GitHub para acceder a los materiales del curso.

⸻

Requisitos

* Cuenta de Google.
* Navegador web actualizado.
* Acceso a Google Colab.
* No se requiere experiencia previa en programación.
* No se requiere instalar Python, Anaconda ni otro software.

⸻

Docente

Paul Muñoz
Profesor Asociado
Departamento de Recursos Hídricos
Facultad de Ingeniería Agrícola
Universidad de Concepción

⸻

Licencia

Copyright © 2026 Paul Muñoz.

Todos los derechos reservados.

Este material fue desarrollado con fines docentes para la Facultad de Ingeniería Agrícola de la Universidad de Concepción.

Queda prohibida la reproducción, distribución o modificación total o parcial de este material sin autorización escrita del autor, excepto para uso académico por estudiantes oficialmente matriculados en la asignatura.
