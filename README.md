# 📊 Proyecto de Analítica Predictiva de Ventas e Inventarios  
### Samsung Innovation Campus – Hackathon

---

## 👨‍💻 Autor
**Miguel Angel Alfonso Saavedra**

---

## 🎯 Descripción del proyecto

Este proyecto tiene como objetivo desarrollar una solución de analítica predictiva para la estimación de la demanda de productos Samsung, utilizando datos históricos de ventas, despachos e inventarios.

Se implementan técnicas de **Machine Learning supervisado** y **clustering** para apoyar la toma de decisiones en áreas de ventas, planeación de inventarios y segmentación de clientes.

El modelo final permite identificar patrones de comportamiento en la demanda, clientes estratégicos y productos de alta rotación, facilitando la planificación comercial basada en datos.

---

## 🧠 Problema de negocio

La empresa presenta dificultades para:

- Estimar la demanda futura de productos  
- Planificar inventarios de manera eficiente  
- Identificar clientes estratégicos  
- Detectar patrones de consumo en el tiempo  

Este proyecto busca resolver estos retos mediante modelos predictivos basados en datos históricos.

---

## ⚙️ Metodología

Se utilizó la metodología **ASUM-DM**, estructurando el proyecto en las siguientes fases:

1. Comprensión del negocio  
2. Comprensión de los datos  
3. Preparación de datos  
4. Modelado  
5. Evaluación  
6. Despliegue de insights  

---

## 📊 Modelos implementados

Se evaluaron diferentes algoritmos de Machine Learning:

- Regresión Lineal  
- Decision Tree Regressor  
- Random Forest Regressor  
- XGBoost Regressor  

### 🏆 Mejor modelo:
**Random Forest Regressor**

- R²: 0.50  
- MAE: 3.47  
- RMSE: 38.99  

---

## 📦 Segmentación de clientes

Se aplicó **K-Means Clustering** para identificar grupos de clientes según su comportamiento de compra.

Se identificaron:

- Clientes de alta actividad  
- Clientes de baja actividad  
- Segmentos intermedios con comportamiento mixto  

---

## 📈 Principales hallazgos

- Alta concentración de ventas en pocos productos (ej: MOBILE)  
- Dependencia fuerte de clientes estratégicos (ej: CUSTOMER20)  
- Alta proporción de registros sin ventas (79%)  
- Comportamiento de demanda altamente intermitente  
- Variables históricas son las más influyentes en la predicción  

---

## 🛠️ Tecnologías utilizadas

- Python 🐍  
- Pandas  
- NumPy  
- Scikit-learn  
- XGBoost  
- Plotly  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 📁 Estructura del proyecto

📦 proyecto-analitica-predictiva
├── data/
│ └── dataset_final.csv
├── notebooks/
│ └── modelado_predictivo.ipynb
├── src/
│ ├── preprocessing.py
│ ├── modeling.py
├── outputs/
│ └── graficas/
├── README.md


---

## 📌 Resultados clave

- Modelo capaz de explicar ~50% de la variabilidad de la demanda  
- Identificación de productos y clientes estratégicos  
- Segmentación útil para decisiones comerciales  
- Base sólida para sistemas de predicción de demanda  

---

## 🚀 Trabajo futuro

- Incorporación de variables externas (precio, promociones, macroeconomía)  
- Implementación de modelos de series de tiempo  
- Desarrollo de dashboards interactivos  
- Despliegue del modelo en entorno productivo  

---

## 🔗 Enlaces del proyecto

- 📁 Notebook / Drive: *[https://drive.google.com/drive/u/2/folders/1FhNpIK8G3OCr80c8Pu_9tJ9qt1Q9pPQC]*  
- 💻 Video presentación: *[https://www.youtube.com/watch?v=zAB7vPiBBhM])*  
  
