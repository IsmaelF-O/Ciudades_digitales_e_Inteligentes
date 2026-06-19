# Ciudades_Digitales_e_Inteligentes

# Sistema de Análisis Bibliométrico y Limpieza de Datos Científicos con Python

Este proyecto desarrolla un sistema de limpieza, procesamiento y análisis bibliométrico de información científica obtenida desde la base de datos Scopus. Su propósito es transformar grandes volúmenes de registros bibliográficos en información estructurada que permita identificar patrones de producción científica, tendencias de investigación, autores influyentes, revistas de alto impacto y la evolución temporal de diferentes áreas del conocimiento.

La investigación se centra en el análisis de publicaciones relacionadas con ciudades inteligentes, transformación digital urbana y geopolítica del conocimiento en Iberoamérica durante el periodo 2010-2025. Para ello, los registros exportados desde Scopus son sometidos a un proceso de limpieza y normalización que garantiza la calidad y consistencia de los datos antes de realizar cualquier análisis bibliométrico.

El sistema elimina registros duplicados, corrige valores faltantes, normaliza palabras clave, transforma variables numéricas y organiza la información en estructuras de datos eficientes para facilitar su exploración. Posteriormente, se aplican técnicas de análisis descriptivo para identificar los temas más investigados, los autores con mayor productividad científica, los investigadores más citados, las revistas con mayor volumen de publicaciones y la evolución histórica de la producción científica.

## Tecnologías y Herramientas Utilizadas

### Python

Python constituye el lenguaje principal del proyecto debido a su flexibilidad, facilidad de aprendizaje y amplio ecosistema de herramientas para ciencia de datos, análisis estadístico, minería de texto e inteligencia artificial. Su capacidad para procesar grandes volúmenes de información lo convierte en una herramienta ideal para estudios bibliométricos.

### Pandas

Pandas es la biblioteca principal utilizada para la manipulación y análisis de datos. Permite cargar archivos CSV exportados desde Scopus, organizar la información en estructuras denominadas DataFrames, eliminar duplicados, gestionar valores faltantes, filtrar registros y realizar transformaciones sobre miles de documentos científicos de manera eficiente.

### NumPy

NumPy proporciona herramientas para el procesamiento numérico de alto rendimiento. Se emplea para realizar cálculos estadísticos, operaciones matemáticas y transformaciones de datos necesarias para los análisis cuantitativos de la producción científica.

### Matplotlib

Matplotlib se utiliza para generar visualizaciones científicas que permiten representar gráficamente la evolución temporal de las publicaciones, tendencias de investigación y otros indicadores bibliométricos. Estas representaciones facilitan la interpretación de los resultados obtenidos durante el análisis.

### Collections

El módulo Collections, mediante la clase Counter, permite realizar conteos automáticos de frecuencia. Esta herramienta resulta fundamental para identificar las palabras clave más utilizadas, los autores más productivos y las revistas con mayor presencia dentro del corpus documental analizado.

### Re (Regular Expressions)

La biblioteca Re se emplea para la limpieza y normalización de texto mediante expresiones regulares. Gracias a ella es posible eliminar caracteres especiales, corregir inconsistencias en las palabras clave y preparar los datos para análisis posteriores de minería de texto y modelado temático.

## Funcionalidades Implementadas

* Limpieza y normalización de datos bibliográficos.
* Eliminación de registros duplicados.
* Tratamiento de valores faltantes.
* Procesamiento y limpieza de palabras clave.
* Identificación de temas de investigación predominantes.
* Análisis de autores más productivos.
* Identificación de autores más citados.
* Análisis de revistas con mayor producción científica.
* Estudio de tendencias temporales de publicación.
* Detección preliminar de temas emergentes.
* Exportación automática de resultados en formato CSV.
* Generación de visualizaciones bibliométricas.

## Desarrollo Futuro

Las siguientes etapas del proyecto contemplan la incorporación de técnicas avanzadas de análisis bibliométrico e inteligencia artificial, incluyendo:

* Modelado de temas mediante LDA (Latent Dirichlet Allocation).
* Descubrimiento automático de temas con BERTopic.
* Detección de explosiones temáticas mediante el algoritmo de Kleinberg.
* Dashboards interactivos utilizando Plotly y JavaScript.
* Visualizaciones dinámicas e interactivas para exploración de datos.
* Análisis predictivo de tendencias científicas.
* Integración de técnicas de procesamiento de lenguaje natural (NLP).

Este proyecto busca servir como una plataforma reproducible para el estudio de la estructura, evolución e impacto de la producción científica, combinando bibliometría, ciencia de datos e inteligencia artificial para comprender mejor la dinámica de generación y circulación del conocimiento científico.
