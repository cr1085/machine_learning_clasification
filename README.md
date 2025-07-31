# Explicación del código:
*    Librerías utilizadas en la codificación
1.   numpy/pandas: Manipulación de datos.
2.   matplotlib/seaborn: Visualización.
3.   scikit-learn: Machine learning (modelo de procesamiento y de clasificación binaria)
4. Dataset: usamos el dataset de cáncer de mama de Wisconsin 
*   30 características numéricas
*   Variable objetivo binaria (0: maligno, 1: benigno)
## Visualizaciones incluidas
1.   Distribución de clases objetivo
2.   Histogramas de todas las características
3.   Matriz de correlación entre características
4.   Matriz de confusión del modelo
5.   Importancia de características (Top 10)
### Modelo de machine learning 
- **Random Forest:** Algoritmo potente para clasificación 
- **Procesamiento:** Escalado estándar de características 
- **Evaluación:** Reporte de clasificación, precisión, matriz de confusión.
# **5. Cómo ejecutarlo**
### Copia este código en un jupyter notebook o script.py
### Asegúrate de tener instaladas las librerías:
```bash
  pip install numpy
  pip install pandas 
  pip install matplotlib
  pip install seaborn
  pip install sickit-learn
```
- Copia y pega este codigo en tu terminal, o ejecuta celda por celda en tu jupyter o todo el script
# **6. Posibles mejoras**

- Ajuste hiperparámetros con GridSearchCV
- Validación cruzada
- Prueba con otros algoritmos (SVM,XGBoost,etc.)
- Análisis más detallado de características.


**Este código proporciona un flujo completo de ML con visualizaciones profesionales listas para presentaciones o informes.** 
