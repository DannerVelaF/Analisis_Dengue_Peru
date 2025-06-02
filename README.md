# 🦟 Análisis de Casos de Dengue en Perú

Este repositorio contiene un análisis exploratorio y visual del comportamiento del dengue en Perú a lo largo del tiempo, utilizando datos organizados por departamentos, provincias, sexo, edad y año.

El objetivo es identificar patrones, regiones más afectadas y tendencias relevantes que puedan ayudar a comprender mejor la evolución de esta enfermedad y apoyar en la toma de decisiones en salud pública.

## 📁 Contenido

El análisis está estructurado en un notebook de Jupyter llamado `datos_denge.ipynb`, el cual contiene las siguientes secciones:

- 📕 **Importación de librerías**
- 📌 **Exploración inicial de los datos**
- ⌛ **Tratamiento y limpieza de datos**
- 🖼️ **Visualización interactiva y estática de los datos**
- 📈 **Análisis de tendencias anuales**
- 🌍 **Identificación de departamentos, provincias y distritos más afectados**
- 👥 **Análisis por sexo y edad**
- 🏥 **Relación entre tipo de enfermedad y género**

## 🧪 Tecnologías utilizadas

- **Python 3**
- **Pandas** – Manipulación de datos
- **Matplotlib & Seaborn** – Visualización estática

## 📊 Datos

El dataset utilizado (`datos_dengue_TF.csv`) debe estar ubicado en el mismo directorio que el notebook para su correcto funcionamiento. Este archivo contiene información sobre los casos de dengue reportados en Perú en diferentes regiones y años y fue obtenido de Kaggle https://www.kaggle.com/datasets/fazzzzzzzzzz/datos-dengue-en-el-per-2019-2022-en-csv.

## 📌 Principales hallazgos

- Algunos departamentos muestran un aumento inusual de casos en ciertos años.
- Las provincias y distritos con más incidencia están localizados principalmente en regiones tropicales y de la selva.
- Se observan diferencias significativas en la incidencia de dengue según el género y la edad.
- La tendencia general muestra una evolución preocupante en los últimos años en varias regiones del país.

## 📷 Ejemplos de visualizaciones

Aquí algunos ejemplos de los gráficos generados en el análisis:

### 🗺️ Casos por Departamento

Este gráfico muestra la distribución total de casos de dengue en los distintos departamentos del Perú.

![image](https://github.com/user-attachments/assets/e0a07796-185d-46ee-a709-12866deb14f4)

### 📊 Casos por Año

Permite observar el comportamiento anual de los casos reportados, detectando picos o patrones estacionales.

![image](https://github.com/user-attachments/assets/c8c65821-f6ca-4980-9bee-bb426b4c21d3)


### 👥 Casos por Género

Comparativa de casos entre pacientes masculinos y femeninos, identificando si hay alguna diferencia significativa.

![image](https://github.com/user-attachments/assets/ec68c5b6-c292-4dcc-a13e-5bd8e34335e3)

### 👥 Casos por Género a lo largo del tiempo por departamento

Compartativo de casos entre pacientes masculino y femeninos, cuantificando los datos por año y departamento mediante un grafico de calor

![image](https://github.com/user-attachments/assets/284f13df-d069-4c41-803c-98f4318314c7)

![image](https://github.com/user-attachments/assets/8ebd7b8d-f054-456f-bed2-d9eca1145355)

### 🧓 Casos por Edad

Análisis de distribución de casos por rangos de edad, útil para entender qué grupos son más vulnerables.

![image](https://github.com/user-attachments/assets/0604ebd2-d299-4803-a4f3-abf47b954136)

## 📊 Visualización en Power BI

Además del análisis en Python, se ha creado un panel interactivo en **Power BI** para explorar los datos de manera visual y dinámica.

![image](https://github.com/user-attachments/assets/084fb9de-f414-4635-8436-e06cb0f26c74)

![image](https://github.com/user-attachments/assets/4fdbf3d7-0410-43eb-9bf5-ec87768687c0)

Este dashboard permite:

- Filtrar casos por año, departamento y tipo de dengue.
- Visualizar mapas de calor geográficos con los focos de mayor incidencia.
- Comparar tendencias por género y edad.
- Analizar distribuciones temporales a lo largo de los años.

## ✅ Conclusiones

- El análisis permitió identificar **departamentos con alta incidencia de dengue**, como Loreto, Ucayali e Ica.
- La **distribución por género** es ligeramente mayor en mujeres durante todos los años
- Los **adultos y los adultos mayores** son uno de los grupos más afectados.
- Las visualizaciones geográficas y temporales ayudan a **comprender el comportamiento espacial y estacional del dengue**.

