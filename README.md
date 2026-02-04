# Produccion-de-miel
Análisis de la producción de miel en Estados Unidos (1995–2021)

# Análisis de la producción de miel en Estados Unidos (1995–2021)

Este proyecto analiza datos históricos de **producción de miel en Estados Unidos entre 1995 y 2021**, con el objetivo de **entender patrones de producción, eficiencia y valor económico**, y proponer **recomendaciones basadas en datos** para el sector apícola.

El trabajo forma parte de un **proyecto final propio inspirado en el Google Data Analytics Certificate**, combinando **SQL, Python y visualización**.

---

## 🍯 Contexto

La miel es un producto clave tanto desde el punto de vista económico como ecológico.  
Las abejas cumplen un rol fundamental en la polinización y la producción de alimentos, por lo que analizar la evolución de la producción de miel permite:

- evaluar la eficiencia productiva por estado
- detectar caídas significativas en la producción
- identificar oportunidades de mejora en rendimiento y capacidad

---

## 🎯 Objetivos

- Analizar la evolución histórica de la producción de miel
- Identificar los principales estados productores
- Evaluar rendimiento por colonia y número de colonias
- Analizar el valor económico de la producción
- Detectar anomalías temporales
- Proponer acciones concretas basadas en los hallazgos

---

## 📊 Dataset

**Fuente:** US Honey Production Dataset (1995–2021)  
**Cobertura:** Estados de EE. UU.

### Variables principales
- `state`
- `year`
- `production`
- `yield_per_colony`
- `colonies_number`
- `average_price`
- `stocks`
- `production_value`

Los datos no contienen información sensible ni identificadores personales.

---

## 🧹 Preparación y limpieza de datos

- Eliminación de estados con series incompletas
- Verificación de valores nulos
- Conversión de tipos de datos
- Reordenamiento temporal por estado y año
- Estandarización de columnas numéricas para análisis comparativo

---

## 🔍 Análisis exploratorio (EDA)

### Producción y tendencia
- Evolución de la producción total por año
- Identificación del año con mayor producción total
- Comparación de producción entre estados

### Eficiencia
- Análisis del rendimiento por colonia
- Comparación entre estados con alto número de colonias vs alto rendimiento

### Precio y valor
- Evolución del precio promedio por estado
- Análisis del valor total de producción

### Inventarios
- Evaluación de stocks recientes por estado

---

## 📉 Hallazgos clave

- **Dakota del Norte** es el mayor productor histórico de miel
- **Dakota del Sur** lidera en existencias recientes
- Se detecta una **caída abrupta de producción entre 2009 y 2010** en todos los estados
- Hawái presenta el **mayor rendimiento por colonia**, pero con pocas colonias
- El volumen de producción no depende únicamente del número de colonias, sino de su eficiencia

---

## 📊 Visualizaciones

- Gráficos de líneas para precios promedio por estado
- Histogramas y boxplots de variables clave
- Gráficos de barras comparando stocks por estado
- Distribuciones de producción a lo largo del tiempo

Las visualizaciones permiten identificar tendencias y outliers de forma intuitiva.

---

## 🧠 Recomendaciones basadas en datos

- Aumentar el número de colonias en estados con alto rendimiento (ej. Hawái)
- Mejorar el rendimiento por colonia en estados con muchas colonias (ej. Dakota del Sur)
- Investigar las causas de la caída de producción 2009–2010
- Optimizar estrategias según eficiencia y no solo volumen

---

## 🛠️ Tecnologías utilizadas

- **Python**
  - pandas, numpy
  - matplotlib, seaborn
  - scikit-learn (escalado)
- **SQL (BigQuery)**
- **Tableau** (visualización final)

---

## 📂 Estructura del repositorio

├── US_honey_dataset_updated.csv
├── produccion_miel.py
├── README.md


---

## 🚀 Próximos pasos

- Incorporar variables climáticas
- Análisis causal de la caída 2009–2010
- Modelos predictivos de producción
- Dashboard interactivo completo

---

## 👤 Autor

**Flavia Hepp**  
Data Analyst en formación  
