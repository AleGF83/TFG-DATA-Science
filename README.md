# TFG - Análisis de Datos de Saque Voleibol Femenino

## 📋 Descripción
Análisis de datos de rendimiento de saques de jugadoras de semi-profesionales de Superliga 2 de voleibol femenino, temporada 2024/2025.

Este proyecto incluye modelado predictivo con técnicas de Machine Learning (Regresión Lineal, Random Forest, XGBoost) y explicabilidad con LIME y SHAP.

---

## 📥 Descarga de Datos

**IMPORTANTE**: Los datos NO están incluidos en el repositorio por privacidad y protección de datos.

### Cómo obtener los datos:

1. **Accede a la web oficial de la RFEVB**:
   - [Estadísticas RFEVb - Rally Edition](https://rfevb-web.dataproject.com/Statistics.aspx?ID=151&PID=185)

2. **Descarga el archivo CSV** con los datos de saque de la temporada.

3. **Coloca el archivo en esta carpeta** renombrado como:
   ```
   TFG-TomaDatosSaqueVb2425-AleGravinaFabregat.csv
   ```

4. **El programaa lo cargará automáticamente** desde la ruta local.

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

1. **Requisitos previos**:
   - Python 3.8+
   - Jupyter Notebook o JupyterLab

2. **Instala las dependencias**:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost shap lime plotly statsmodels weasyprint ipywidgets
   ```

3. **Coloca el archivo CSV en la carpeta** (ver apartado de Descarga de Datos)

4. **Abre y ejecuta el notebook**:
   ```bash
   jupyter notebook TFG_SaqueVb2425_DataScience_AleGravinaFabregat.ipynb
   ```

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
