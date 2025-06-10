# Challenge_TelecomX_latam
# 📊 Análisis de Cancelación de Clientes - TelecomX

Este proyecto analiza los factores que influyen en la cancelación de clientes (churn) de la empresa ficticia **TelecomX**, proveedora de servicios de telecomunicaciones. Utilizando datos obtenidos desde una API en formato JSON, se realiza un análisis exploratorio completo, limpieza, transformación y visualización de los datos, con el objetivo de obtener insights útiles y formular recomendaciones estratégicas.

---

## 🎯 Objetivos

- Entender los factores asociados a la cancelación de clientes.
- Identificar patrones y comportamientos que expliquen el churn.
- Sugerir acciones para reducir la pérdida de clientes.
- Crear visualizaciones claras y efectivas para stakeholders.

---

## 🛠️ Tecnologías Utilizadas

- Python 3
- Pandas
- NumPy
- Plotly
- Seaborn
- Matplotlib
- Google Colab
- API JSON

---

## 📂 Estructura del Análisis

1. **Extracción de Datos**
   - Consumo de datos desde una API pública en formato JSON.
   - Aplanamiento y renombramiento de columnas.

2. **Limpieza y Transformación**
   - Conversión de tipos de datos.
   - Eliminación de duplicados y valores nulos.
   - Normalización de texto.
   - Imputación de datos faltantes.
   - Creación de nuevas variables (`DailyCharges`).
   - Codificación binaria y categórica.

3. **Análisis Exploratorio**
   - Matriz de correlación de variables numéricas con `Churn`.
   - Gráficos boxplot de:
     - `DailyCharges` vs. Cancelación.
     - `Tenure` vs. Cancelación.
   - Top 5 factores con mayor correlación con el churn.

4. **Conclusiones**
   - Mayor churn en clientes nuevos con altos cargos.
   - Contratos largos reducen significativamente la cancelación.
   - Factores como `Partner`, `PhoneService` y `PaperlessBilling` también influyen.

5. **Recomendaciones Estratégicas**
   - Incentivar contratos largos.
   - Ofrecer beneficios a nuevos clientes.
   - Personalizar tarifas para clientes con cargos altos.
   - Realizar campañas de retención específicas.

---

## 📥 Cómo usar este repositorio

```bash
# Clona este repositorio
git clone [https://github.com/alebaldion/Challenge_TelecomX_latam]

# Accede a main del proyecto
Final_TelecomX_LATAM.ipynb

# Abre el archivo en Google Colab o Jupyter
```
---
##  📌 Créditos
Proyecto desarrollado por [Alexandra Baldión], 2025.
Inspirado en prácticas de análisis de datos aplicadas al sector de telecomunicaciones.
