# Proyecto Final KDD: Prevención de Fraude Bancario en Costa Rica
**Curso:** SINF-633 Análisis Exploratorio de Datos (EDA) — Universidad CENFOTEC (2026)  
**Estudiante:** Lucerito Chacón Matamoros  

## 📌 Descripción del Proyecto
Implementación integral y reproducible del modelo **Knowledge Discovery in Databases (KDD)** de Fayyad et al. (1996) sobre un registro de 5 000 transacciones bancarias (`transacciones_bancarias.csv`), integrando limpieza estadística, ingeniería de atributos, algoritmos no supervisados (`K-Means`, `DBSCAN`, `PCA`), reglas de asociación (`Apriori`) y modelos supervisados balanceados (`Regresión Logística`, `Random Forest` y `Gradient Boosting`).

## 📊 Resultados Clave
* **Patrón de negocio descubierto:** El **83.49%** de los fraudes ocurren en horario nocturno (`22:00 a 05:59`). La combinación de un outlier de monto (`> $379.91`) con horario nocturno eleva la tasa de fraude del `2.18%` global al **`41.03%`**.
* **Mejor modelo supervisado (`Random Forest Balanced`):** Alcanza **Accuracy = 99.60%**, **Precision = 100.00% (0 falsos positivos)**, **Recall = 81.82%**, **F1-Score = 0.9000** y **AUC-ROC = 0.8964** sobre el conjunto de prueba estratificado (20%).

## ⚙️ Instrucciones de Reproducibilidad
1. Clonar el repositorio o descargar los archivos:
   ```bash
   git clone [https://github.com/lchaconm24/proyecto_kdd_fraude.git](https://github.com/lchaconm24/proyecto_kdd_fraude.git)
   cd proyecto_kdd_fraude
