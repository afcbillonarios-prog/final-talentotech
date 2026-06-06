# 🌾 AgroCrédito Colombia - Seguridad Alimentaria

**Equipo:** Andrés, Sebastián, Julián, Yuri  
**Programa:** Talento Tech 2

[![Python](https://img.shields.io/badge/python-3.10+-green?style=flat-square&logo=python)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=Streamlit&logoColor=white)](https://streamlit.io/)
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Licencia](https://img.shields.io/badge/Licencia-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)

---

## 📋 Descripción del Proyecto

**AgroCrédito Colombia** es una plataforma de inteligencia artificial diseñada para:

- 🎯 **Consultar créditos rurales por cédula**
- 📊 **Predecir tasas de interés justas con IA**
- 🌱 **Promover la tecnología rural**
- 🍽️ **Garantizar la seguridad alimentaria**

---

## 🎯 Objetivos

1. **Volver al Campo:** Incentivar a los colombianos a regresar al campo
2. **Créditos Justos:** Usar IA para predecir tasas personalizadas
3. **Tecnología Rural:** Promover energía solar, riego y drones
4. **Seguridad Alimentaria:** Aumentar la producción de alimentos

---

## 📁 Estructura del Proyecto

```
├── 📓 Cuadernos Jupyter
│   ├── 00_Generacion_Datos.ipynb      # Generación del dataset
│   ├── 01_ETL_Preparation.ipynb       # Limpieza de datos
│   ├── 02_EDA_Exploration.ipynb       # Análisis exploratorio
│   └── 03_Model_Evaluation.ipynb      # Modelado y evaluación
│
├── 🐍 Scripts Python
│   ├── generate_data.py               # Generador de datos
│   ├── run_etl.py                     # Pipeline ETL
│   ├── run_modeling.py                # Entrenamiento
│   ├── app.py                         # App Streamlit
│   └── model_utils.py                 # Funciones utilitarias
│
├── 🌐 Archivos Web
│   ├── index.html                     # Landing page
│   ├── dashboard_avanzado.html        # Dashboard interactivo
│   ├── ebook_interactivo.html         # Ebook con voz
│   ├── juego_interactivo.html         # Juego de preguntas
│   └── juego_animales.html            # Juego de animales
│
├── 📊 Datos y Modelos
│   ├── data/
│   │   ├── creditos_rurales.csv       # Dataset original
│   │   └── creditos_rurales_limpio.csv # Dataset limpio
│   └── modelo_creditos.pkl            # Modelo serializado
│
└── 📄 Archivos de Configuración
    ├── requirements.txt               # Dependencias
    ├── README.md                      # Documentación
    └── .gitignore                     # Archivos ignorados
```

---

## 🚀 Instalación y Ejecución

### 1. Clonar el repositorio
```bash
git clone https://github.com/afcbillonarios-prog/prestamos_para_el_campo_colombian.git
cd prestamos_para_el_campo_colombian
```

### 2. Instalar dependencias
```bash
pip install -r requirements.txt
```

### 3. Ejecutar pipeline (opcional)
```bash
python generate_data.py    # Genera dataset
python run_etl.py          # Limpia datos
python run_modeling.py     # Entrena modelo
```

### 4. Lanzar app Streamlit
```bash
streamlit run app.py
```

### 5. Abrir landing page
Abre `index.html` en tu navegador.

---

## 🧠 Modelo de Machine Learning

| Métrica | Valor |
|---------|-------|
| Algoritmo | Regresión Lineal Múltiple |
| R² Score | 89.2% |
| MAE | 0.75 pp |
| Variables | 11 predictoras |

### Impacto de Variables
- **Subsidio LEC Finagro:** -4.34% E.A.
- **Garantía FAG:** -2.36% E.A.
- **Energía Solar:** -0.69% E.A.
- **Cada tecnología:** -0.35% E.A.

---

## 📊 Sectores Productivos

| Sector | Productos |
|--------|-----------|
| 🌱 Agricultura | Café, cacao, arroz, frutas |
| 🐄 Ganadería | Leche, carne bovina |
| 🐟 Piscicultura | Tilapia, trucha, camarón |
| 🐷 Porcícola | Cerdo, lechón |
| 🐔 Avicultura | Pollo, huevo |
| ☀️ Energía Solar | Placas fotovoltaicas |
| 🤖 Tecnología | Riego, drones, sensores |

---

## 👥 Equipo

- **Andrés** - Desarrollo Backend
- **Sebastián** - Ciencia de Datos
- **Julián** - Frontend
- **Yuri** - Análisis de Datos

**Talento Tech 2 - 2026**

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para detalles.
