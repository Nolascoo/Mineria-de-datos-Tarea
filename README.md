# Dataset Sintético - Deserción Estudiantil

Este repositorio contiene un dataset sintético creado para la actividad **Supervised vs Unsupervised Learning** en la Universidad de la Costa.

## 📂 Archivos incluidos
- `dataset_desercion.csv`: contiene 550 registros con variables demográficas, académicas y financieras de estudiantes.
- `README.md`: documento explicativo sobre el dataset.

## 📊 Descripción de las variables
- **Edad**: numérica, entre 17 y 30 años (se introdujeron outliers como 5 y 100).
- **Genero**: categórica, valores posibles: M, F, Otro.
- **Origen**: categórica, Urbano o Rural.
- **Promedio_colegio**: numérica, escala 1.0 – 5.0.
- **Puntaje_admision**: numérica, escala 0 – 100.
- **Notas_semestre1**: numérica, escala 0.0 – 5.0.
- **Estrato**: numérica, valores de 1 a 6 (algunos nulos introducidos).
- **Beca**: categórica, Sí/No.
- **Prestamo**: categórica, Sí/No.
- **Dropout**: variable objetivo, Sí/No (30% Sí, 70% No).

## ⚠️ Nulos y Outliers
- Se incluyeron valores **nulos** en algunas columnas (promedio, puntaje, notas, estrato).
- Se agregaron **outliers** en la columna `Edad` (ej: 5, 100) y en `Promedio_colegio` (valores fuera de rango).

## 🛠️ Uso
Este dataset es útil para practicar:
- **Problemas de clasificación supervisada** (ejemplo: predicción de deserción).
- **Limpieza de datos** (tratamiento de nulos y outliers).
- **Preprocesamiento de variables categóricas y numéricas**.

---
✍️ *Creado como parte de la actividad de Control Automáticos II - Data Mining.*
