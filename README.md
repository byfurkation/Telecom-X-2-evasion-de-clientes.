![portada challenge](https://github.com/byfurkation/Telecom-X-2-evasion-de-clientes./blob/main/assets/portada_proyecto.png?raw=true)

# <h1 align="center"> TelecomX- Modelos de predicción y su evaluación - Tree decision, Random forest y KNN  </h1>
## <h1 align="center"> Machine Learning en Python. </h1>

![Static Badge](https://img.shields.io/badge/Data%20Analysis-Python-brightgreen?style=flat-square)

## Indice  

- [1 El propósito del análisis realizado](#1-el-propósito-del-análisis-realizado)

- [2 La estructura del proyecto y organización de los archivos](#2-La-estructura-del-proyecto-y-organización-de-los-archivos)

- [3 Acceso al proyecto](#3-Acceso-al-proyecto)

- [4 Instrucciones para ejecutar el notebook](#4-Instrucciones-para-ejecutar-el-notebook) 

- [5 Tecnologías utilizadas](#5-tecnologías-utilizadas)

- [6 Autor](#6-autor)

## 1 El propósito del análisis realizado

En este proyecto me propuse aplicar de manera práctica algunos de los conceptos más importantes de estadística, porque son la base para entender cómo se comportan los datos y poder tomar mejores decisiones con ellos.

Lo primero que hice fue preparar y dividir los datos de la forma correcta, ya que para poder crear modelos predictivos es clave tener un buen balance entre los datos de entrenamiento y los de prueba. Si no se hace bien este paso, los modelos simplemente no son confiables.

Después me enfoqué en analizar la correlación entre variables, lo que me permitió ver cuáles factores están más relacionados con la cancelación de servicios, es decir, con el churn. Con esa información a la mano, utilicé la regresión lineal para modelar esas relaciones y entender qué tanto impacta cada variable en el comportamiento de los clientes.

Al final, con todo esto, logré sentar una *base sólida para avanzar hacia modelos de machine learning *que predicen la evasión de clientes. Esto no solo sirve para anticipar el riesgo de pérdida, sino también para ayudar a la empresa a tomar decisiones más estratégicas y reducir el impacto del churn.

**Requisitos:**

✅ Cargar y manipular datos desde un archivo a través de un libro de Júpiter en Google Colab.

✅ Aplicar los conceptos de ETL (Extracción, Transformación y Carga) en la preparación de los datos.

✅ Crear visualizaciones estratégicas para identificar patrones y tendencias.

✅ Realizar un Análisis Exploratorio de Datos (EDA).

✅ correlacionar y seleccionar variables.

✅ Escalar y normalizar datos para su uso en modelos de predicción.

✅ Generar Modelos de predicción para Machine learning.

✅ Evaluación de los modelos de predicción con Accuracy, Precision, Recall, F1-Score, ROC-AUC.

✅ Analizar la importancia de las variables de cada modelo de predicción.

✅ Generar un informe con insights relevantes.

## 2 La estructura del proyecto y organización de los archivos

Para llevar a cabo el presente análisis, se puede dividir en las siguientes etapas:

1️⃣ **Objetivo** 🎯

2️⃣ **Contexto del escenario**

3️⃣**Preparación de los Datos**🛠️

4️⃣**Correlación y Selección de Variables** 🎯

Análisis de descriptivo

Análisis de Correlación

Análisis Dirigido

5️⃣**Modelado Predictivo** 🤖

Separación de Datos

Creación de Modelos: Tree decision, Random forest y KNN.

Escalación y Normalización de datos

Balanceo de datos

6️⃣**Interpretación y Conclusiones** 📋

Análisis de la Importancia de las Variables

Informe de Análisis de Churn: Factores de Cancelación de Clientes

## 3 Acceso al proyecto 

Para Acceder al proyecto se necesita ingresar al repositorio alojado en Git Hub en la siguiente url: [[https://github.com/byfurkation/Telecom-X-2-evasion-de-clientes.](https://github.com/byfurkation/Telecom-X-2-evasion-de-clientes.)], dónde se deberá hacer clic sobre el archivo de nombre "X_telecom_2_evasion_clientes.ipynb".

Al ingresar hay dos opciones para acceder al proyecto, la primera, será dar clic en la parte superior derecha en el botón que tiene una flecha hacia abajo para descargar el archivo y recuperarlo desde nuestra carpeta de descargas predeterminada, para posteriormente ir a la página https://colab.research.google.com/ y cargarlo, o como segunda opción, dar clic sobre las letras que dicen "open in colab", lo cual nos llevará directamente al Notebook de Júpiter en Google colab. 

Si hemos seleccionado Descargar el proyecto podemos subirlo a Google Drive Y desde ahí vincularlo con Google Colab, para lo cual será necesario tener una cuenta de Google. Otra manera de subirlo será poniendo el link del repositorio, directamente en Google colab, o por último si lo hemos descargado subirlo desde la sección  "Subir", lo cual nos permitirá Buscar en nuestros archivos de nuestra computadora. 

## 4 Instrucciones para ejecutar el notebook

Una vez dentro del proyecto encontraremos secciones de código, las cuales estando dentro de ellas, podremos ejecutarlo mediante la presión de los botones "shift" + "enter" o con el botón de Play que aparece a la izquierda del código. De esta manera si alguien quiere agregar código para realizar algún cálculo se puede llevar a cabo dentro de estas celdas o generar nuevas para correr otro código diferente, en el presente se utiliza python. 

## 5 Tecnologías utilizadas
* Python. Pandas y Matplotlib, plotly.express y Seaborn para llevar a cabo ETL.
* Python. sklearn y  relacionados tales como: tree, metrics, model_selection, ensemble, preprocessing, neighbors, entre otros para modelos de predicción.
* Jupiter Notebook en Google Colab.
* Github.

## 6 Autor

| [<img src="https://avatars.githubusercontent.com/u/194540551?s=200" width=115><br><sub>Christian Carvajal</sub>](https://github.com/byfurkation) |
| :---: |
