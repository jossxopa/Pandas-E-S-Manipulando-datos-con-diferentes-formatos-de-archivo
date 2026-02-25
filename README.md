# Manipulación de Datos: JSON, HTML, XML y SQL

Este repositorio contiene un notebook de Google Colab diseñado para aprender y practicar la extracción, limpieza y normalización de datos desde múltiples formatos utilizando **Python** y **Pandas**.

## 🚀 Contenido del Proyecto

El notebook está organizado en secciones prácticas que cubren el flujo de trabajo de un Analista de Datos:

### 1. Archivos JSON
* **Lectura básica:** Uso de `pd.read_json()`.
* **Normalización:** Técnicas para aplanar estructuras JSON anidadas (cuando hay diccionarios dentro de listas).
* **Visualización:** Recomendaciones para usar herramientas como *JSON Crack* para entender la jerarquía de los datos.

### 2. Web Scraping Tabular (HTML)
* Extracción automática de tablas desde páginas web directamente a DataFrames de Pandas.

### 3. Formatos XML
* Manejo y conversión de datos estructurados en XML para análisis tabular.

### 4. Bases de Datos (SQLAlchemy)
* **Conexión:** Creación de un `engine` para interactuar con bases de datos.
* **Inspección:** Uso de `inspect` para auditar esquemas, nombres de tablas, claves primarias y tipos de datos.
* **Consultas:** Ejecución de queries SQL y carga de resultados en Pandas.

## 📁 Estructura de Archivos Recomendada

Para que el notebook funcione correctamente, asegúrate de tener los archivos en la raíz de tu proyecto o cargarlos en tu sesión de Colab:

* `Manipulando_Datos.ipynb`: El notebook principal.
* `pacientes.json`: Dataset de ejemplo con datos de salud.
* `pacientes_2.json`: Dataset anidado para ejercicios de normalización.
* *(Cualquier otro archivo .sql o .xml que utilices en tus celdas).*

## 📊 Notas sobre el Dataset
Debido al tamaño del archivo de clientes (>25MB), este se encuentra comprimido en formato `.zip`. 
El notebook está configurado para leerlo cuando el archivo se descomprima.

## 🛠️ Requisitos

Si deseas ejecutar este notebook localmente, necesitarás:
* Python 3.x
* Pandas
* SQLAlchemy
* Lxml (para la lectura de HTML/XML)

## 💡 Cómo usar este Notebook
1. Sube el archivo `.ipynb` a [Google Colab](https://colab.research.google.com/).
2. Sube los archivos `.json` a la sección de archivos de la barra lateral izquierda en Colab.
3. Ejecuta las celdas en orden para observar cómo se transforman los datos desde su estado crudo hasta un DataFrame limpio.

---
*Este proyecto fue desarrollado como parte de una práctica en ciencia de datos y manipulación de archivos.*
