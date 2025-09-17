# 🎓 SaberPro Prediction & Profiling

Este proyecto busca desarrollar un **modelo de aprendizaje de máquina** que, a partir de variables **sociales, económicas y académicas** de estudiantes en programas de educación superior, permita:

- **Predecir** el puntaje probable en las pruebas Saber Pro.  
- **Segmentar y clasificar** a los estudiantes para identificar perfiles característicos según su rendimiento, condiciones socioeconómicas y tipo de programa cursado.  

---

## 📊 Base de Datos

- **Fuente:** Resultados oficiales de las pruebas Saber Pro.  
- **Dimensión:** 1,22 millones de registros, 57 variables.  
- **Descripción:** Información académica, social y económica de estudiantes de educación superior en Colombia que presentaron la prueba Saber Pro entre 2018 y 2022.  

---

## 🚀 Elevator Pitch  

### Preguntas de negocio y análisis
1. ¿Qué factores sociales, económicos y académicos inciden con mayor fuerza en el desempeño de los estudiantes en las pruebas Saber Pro?  
2. ¿Cómo se pueden identificar y agrupar perfiles de estudiantes basados en rendimiento y condiciones socioeconómicas mediante técnicas de aprendizaje no supervisado?  
3. ¿De qué manera esta segmentación puede apoyar a las universidades en el diseño de políticas de admisión, acompañamiento y apoyo financiero para reducir riesgos y potenciar el éxito estudiantil?  

### Justificación
Responder estas preguntas permite que las instituciones educativas pasen de un enfoque **reactivo** a uno **preventivo**. Al conocer los factores críticos y segmentar perfiles, se pueden diseñar estrategias de **admisión, tutorías y financiamiento basadas en evidencia**, optimizando recursos y mejorando indicadores de retención y desempeño.  

---

## 📁 Estructura del Repositorio  

```bash
saberpro-prediction-profiling/
│
├── data/                           # Conjunto de datos
│   ├── raw/                        # Datos originales
│   ├── processed/                  # Datos limpios y transformados
│   └── README.md                   # Diccionario de datos
│
├── notebooks/                            # Notebooks de análisis y modelado
│   ├── 01_eda_analysis.ipynb        # Análisis exploratorio de datos (EDA)
│   ├── 02_preprocessing.ipynb       # Preparación de datos e ingeniería de características
│   ├── 03_model_selection.ipynb     # Modelado inicial (pruebas con diferentes algoritmos)
│   ├── 04_full_model.ipynb          # Modelo final completo (entrenamiento y validación)
│   └── 05_technical_report.ipynb    # Informe técnico integral (proceso completo en un único notebook)
│
├── interfaz/                       # Interfaz con Gradio
│   └── interfaz.py                 # Script principal de la interfaz
│
├── docs/                           # Documentación adicional
│   └── presentacion.pdf            # Presentación final del proyecto
│
└── README.md                       # Documentación general del proyecto
```

---

## 👥 Data Scientists  


- [Juan Pablo Arias](https://github.com/JuanPabloArias) - Scrum Master & Data Analyst

- [Sergio Pardo](https://github.com/SergioPardoHurtado) - Data Scientist (ML & Visualization)

- [Paula Andrea Romero](https://github.com/Andyy870)  - Machine Learning Engineer

- [Laura Beltrán](https://github.com/Andyy870) - Business & Data Strategy Analyst

---

## 📚 Técnicas de Machine Learning  
**Docente:** Oscar Bustos  
