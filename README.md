README

# Proyecto 1 — Regresión Lineal Simple  
**Predicción de Salario según Años de Experiencia**

---

## 1. Objetivo del Proyecto  
El objetivo de este proyecto es construir un modelo de **Regresión Lineal Simple** capaz de predecir el salario de un empleado en función de sus **años de experiencia**, utilizando el dataset *Salary Dataset* de Kaggle.

El proyecto incluye:

- Análisis exploratorio de datos (EDA)  
- Entrenamiento del modelo  
- Evaluación con métricas estándar  
- Análisis de residuos  
- Diagnóstico del modelo  
- Validación cruzada  
- Predicciones nuevas  

---

## 2. Dataset  

**Fuente:**  
https://www.kaggle.com/datasets/abhishek14398/salary-dataset-simple-linear-regression  

**Archivo:**  
`Salary_dataset.csv`

**Variables:**

- `YearsExperience` → Variable independiente (X)  
- `Salary` → Variable dependiente (y)

---

## 3. Metodología  

El proyecto sigue los pasos clásicos de un flujo de Machine Learning:

1. Importación de librerías  
2. Carga y exploración del dataset  
3. Análisis exploratorio (EDA)  
4. Preparación de datos  
5. Entrenamiento del modelo  
6. Evaluación  
7. Análisis de residuos  
8. Diagnóstico del modelo  
9. Predicciones nuevas  
10. Conclusiones  

---

## 4. Ecuación del Modelo  

Tras entrenar el modelo, se obtiene la ecuación:



\[
\text{Salario} = \beta_0 + \beta_1 \cdot \text{AñosExperience}
\]



Donde:

- **β₀** = Intercepto  
- **β₁** = Pendiente (incremento del salario por cada año adicional de experiencia)

---

## 5. Resultados del Modelo  

### 5.1 Métricas en el conjunto de prueba  

- **R²:** valor_generado_por_tu_modelo  
- **MAE:** valor_generado_por_tu_modelo  
- **RMSE:** valor_generado_por_tu_modelo  

*(Sustituir por tus valores reales.)*

---

### 5.2 Validación Cruzada (cv=5)  

- **R² por fold:** [lista_de_scores]  
- **R² promedio:** promedio  
- **Desviación estándar:** std  

---

## 6. Diagnóstico del Modelo  

Se realizaron los siguientes análisis:

- Detección de outliers mediante residuos  
- Comparación entre R² de entrenamiento y prueba  
- Evaluación de posible overfitting  
- Validación cruzada para medir estabilidad  

El modelo mostró:

- Estabilidad razonable si la diferencia entre R² train y test es baja  
- Buen desempeño si R² ≥ 0.90  
- Errores bajos si MAE y RMSE están dentro de los rangos esperados  

---

## 7. Predicciones Nuevas  

Se generaron predicciones para los siguientes valores de experiencia:

- 1.5 años  
- 5.0 años  
- 8.0 años  
- 10.0 años  
- 12.0 años  

El modelo devuelve un salario estimado para cada caso.

---

## 8. Conclusiones  

- Existe una relación lineal fuerte entre años de experiencia y salario.  
- El modelo de regresión lineal simple es adecuado para este dataset.  
- Las métricas obtenidas indican un buen nivel de precisión.  
- La validación cruzada confirma que el modelo es estable.  
- Puede utilizarse para estimar salarios en escenarios similares.  

---

## 9. Tecnologías Utilizadas  

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit‑Learn  

---

## 10. Estructura del Proyecto
📁 Proyecto_Regresion_Lineal  
│── 📄 Salary_dataset.csv  
│── 📄 notebook.ipynb  
│── 📄 README.md  




---

📁 Proyecto_Regresion_Lineal
│── 📄 Salary_dataset.csv
│── 📄 notebook.ipynb
│── 📄 README.md

