# TFG - Análisis de Datos de Saque Voleibol Femenino

## 📋 Descripción
Análisis de datos de rendimiento de saques de jugadoras de semi-profesionales de Superliga 2 de voleibol femenino, temporada 2024/2025.

Este proyecto incluye modelado predictivo con técnicas de Machine Learning (Regresión Lineal, Random Forest, XGBoost) y explicabilidad con LIME y SHAP.

---

## � Origen de los Datos

**Creación propia**: El archivo `TFG-TomaDatosSaqueVb2425-AleGravinaFabregat.csv` fue creado en colaboración con operadores de **DataVolley en España**.

### Proceso de obtención:

1. **Recopilación de datos**: Se extrajeron datos brutos de DataVolley
2. **Procesamiento**: Se aplicó el formato interno estándar de análisis de voleibol (ver estructura en imagen adjunta)
3. **Validación**: Se verificó la integridad de los datos con los operadores
4. **Anonimización**: Los jugadores se identifican como "Jugadora_1", "Jugadora_2", etc.

---

## 📥 Archivo de Datos

El archivo **`TFG-TomaDatosSaqueVb2425-AleGravinaFabregat.csv`** está incluido en el repositorio.

- ✅ Descárgalo directamente desde GitHub
- ✅ Colócalo en esta carpeta (o donde esté el notebook)
- ✅ El programa lo cargará automáticamente desde la ruta local

---

## 📊 Estructura del Proyecto

```
TFG_SaqueVb2425_DataScience_AleGravinaFabregat.ipynb
├── IMPORTACIÓN DE LIBRERÍAS
├── TRANSFORMACIÓN DE DATOS
├── CREACIÓN DE NUEVAS VARIABLES
├── ANÁLISIS DESCRIPTIVO
├── MODELADO:
│   ├── Regresión Lineal Multivariable
│   ├── Random Forest
│   └── XGBoost
└── EXPLICABILIDAD:
    ├── LIME (Local Interpretable Model-agnostic Explanations)
    └── SHAP (SHapley Additive exPlanations)
```

---

## 🔒 Privacidad y Seguridad

- ✅ Los archivos `.csv` están incluidos en `.gitignore` 
- ✅ **No se suben a GitHub** datos personales o sensibles
- ✅ Los jugadores están anonimizados como "Jugadora_1", "Jugadora_2", etc.

---

## 🚀 Cómo ejecutar el Notebook

### 1. Requisitos previos
- Python 3.8+
- Jupyter Notebook o JupyterLab

### 2. Instala las dependencias (Primera vez)

**Opción A - Desde `requirements.txt` (Recomendado)**:
```bash
# Clona el repositorio
git clone <repo-url>
cd <repo-folder>

# Instala todas las dependencias de una sola vez
pip install -r requirements.txt
```

**Opción B - Instalar manualmente**:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost shap lime plotly statsmodels weasyprint ipywidgets
```

### 3. Coloca el archivo CSV en la carpeta
Ver apartado **📥 Archivo de Datos**

### 4. Abre y ejecuta el notebook
```bash
jupyter notebook TFG_SaqueVb2425_DataScience_AleGravinaFabregat.ipynb
```

⚠️ **IMPORTANTE**: Ejecuta la **primera celda de instalación** del notebook SOLO UNA VEZ para verificar que todas las dependencias están correctas.

---

## 📚 Librerías Utilizadas

- **Procesamiento de datos**: `pandas`, `numpy`
- **Visualización**: `matplotlib`, `seaborn`, `plotly`
- **Machine Learning**: `scikit-learn`, `xgboost`
- **Explicabilidad**: `shap`, `lime`
- **Estadística**: `statsmodels`

---

## 👨‍💻 Autor

**Ale Gravina Fabregat** - TFG Universitat EUNCET - CTEF

---

## 📝 Licencia

Este proyecto es confidencial y está destinado únicamente a fines académicos.

---

## ❓ Problemas Comunes

### Error: `FileNotFoundError: TFG-TomaDatosSaqueVb2425-AleGravinaFabregat.csv`

**Solución**: Asegúrate de que:
1. El archivo CSV está descargado
2. Está en la misma carpeta que el notebook
3. El nombre del archivo es exacto (sin espacios adicionales)

### Error de importación de librerías

**Solución**: Reinstala los paquetes:
```bash
pip install --upgrade pandas scikit-learn xgboost shap lime
```

---

¡Cualquier duda, revisa la documentación oficial de las librerías utilizadas!
