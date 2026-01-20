# 📚 Book Genre Classifier & Recommender System

Sistema híbrido de clasificación de géneros literarios y recomendación de libros, desarrollado en Python utilizando técnicas de Machine Learning.

## 🎯 Objetivo del Proyecto

3 fases progresivas:
1. **Fase 1:** Clasificación supervisada de géneros literarios
2. **Fase 2:** Sistema de recomendación basado en similitud de características
3. **Fase 3:** Integración de NLP para análisis de descripciones

## 🗂️ Fases del Proyecto

### ✅ Fase 1: Clasificación de Géneros
**Estado:** 🚧 En progreso

**Objetivos:**
- [ ] Análisis exploratorio de datos (EDA)
- [ ] Preprocesamiento y limpieza
- [ ] Entrenamiento de modelos supervisados:
  - Logistic Regression (baseline)
  - Decision Tree
  - Random Forest
- [ ] Evaluación y comparación de modelos

**Métricas objetivo:**
- Accuracy > 70%
- F1-Score balanceado

---

### ⏳ Fase 2: Sistema de Recomendación
**Estado:** 📅 Planificado

**Objetivos:**
- [ ] Implementar K-Nearest Neighbors (KNN)
- [ ] Calcular similitud entre libros usando:
  - Autor
  - Género predicho (Fase 1)
  - Número de páginas
  - Rating promedio
- [ ] Crear función `recommend(book_title, n=5)`

---

### ⏳ Fase 3: Mejora con NLP
**Estado:** 📅 Planificado

**Objetivos:**
- [ ] Preprocesamiento de descripciones de libros
- [ ] TF-IDF para vectorización de texto
- [ ] Integrar similitud semántica al recomendador
- [ ] Modelo híbrido (features + texto)

---

## 📊 Dataset
TBC

## 🛠️ Tecnologías y Herramientas

### Librerías Python
```
jupyter       # Notebooks interactivos
```

### Herramientas
- **Python**
- **Git** para control de versiones
- **VS Code** como IDE
- **Jupyter Notebooks** para exploración
- **GitHub** para portfolio

---

## 📁 Estructura del Proyecto
```
├── data/
│   ├── raw/              # Datos originales
│   ├── processed/        # Datos procesados por fase
│   └── models/           # Modelos entrenados
├── notebooks/            # Notebooks de exploración
│   ├── phase1/           # Clasificación
│   ├── phase2/           # Recomendación básica
│   ├── phase3/           # NLP
│   └── experiments/      # Pruebas y tests
├── src/                  # Código Python reutilizable
│   ├── data/             # Carga y preprocesamiento
│   ├── features/         # Feature engineering
│   ├── models/           # Entrenamiento y predicción
│   └── utils/            # Funciones auxiliares
├── outputs/              # Resultados
│   ├── figures/          # Gráficos
│   └── reports/          # Reportes en Markdown
└── docs/                 # Documentación
```

---

## 📊 Resultados

*Se actualizarán conforme avance el proyecto*



---

