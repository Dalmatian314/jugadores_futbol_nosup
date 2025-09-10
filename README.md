# Jugadores de Fútbol - Análisis No Supervisado

Este proyecto aplica **técnicas de Machine Learning no supervisado** para analizar y agrupar jugadores de fútbol en base a sus características estadísticas.  
El trabajo se centra en **exploración de datos, visualización, escalado y clustering**, con el objetivo de identificar perfiles de jugadores que podrían desempeñar roles similares en un equipo.

---

## 📂 Dataset

Se utiliza la base de jugadores **`male_players.csv`**, disponible en Kaggle:  
👉 [Football Player Performance Prediction](https://www.kaggle.com/code/nongflook/football-player-performance-prediction?select=male_players.csv)

⚠️ Importante: esta base **no coincide exactamente con la vista en clase (FIFA2019)** y tiene diferencias de formato y jugadores.

---

## 📝 Objetivos y análisis realizado

1. **Análisis exploratorio inicial de la base.**  
   - Revisión de estructura, tipos de variables y valores faltantes.  
   - Estadísticas descriptivas y distribuciones iniciales.  

2. **Evaluación visual de variables numéricas.**  
   - Scatterplots de pares de variables con sentido futbolístico.  
   - Análisis de correlaciones y tendencias.  

3. **Normalización o escalado.**  
   - Discusión sobre la necesidad de escalar variables antes del clustering.  
   - Justificación de la técnica elegida (StandardScaler, MinMax, etc.).  

4. **Aplicación de técnicas de clustering.**  
   - Se prueban al menos **dos métodos**:  
     - K-means  
     - DBSCAN / Gaussian Mixtures / Clustering jerárquico (según el caso)  
   - Justificación de hiperparámetros: número de clusters, métrica de distancia, etc.  

5. **Análisis cualitativo de clusters.**  
   - Interpretación de los grupos de jugadores.  
   - ¿Qué jugadores podrían reemplazarse en un equipo?  
   - Discusión sobre clusters homogéneos vs heterogéneos y diferencias de tamaño.  

6. **Transformaciones y visualización.**  
   - Uso de **PCA** u otros embeddings para reducir dimensionalidad.  
   - Visualización de los clusters en 2D.  

Cada sección incluye comentarios y explicaciones detalladas (**verbose=True 😉**).

---

## 🧰 Tecnologías utilizadas

- Python 3.x  
- Jupyter Notebook  
- Pandas, NumPy  
- Scikit-learn (escalado, clustering, PCA)  
- Matplotlib, Seaborn (visualización)

---

## 🚀 Cómo ejecutarlo

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/Dalmatian314/jugadores_futbol_nosup.git
   cd jugadores_futbol_nosup
   ```

2. Instalar dependencias:
   ```bash
   pip install -r requirements.txt
   ```

3. Abrir el notebook:
   ```bash
   jupyter notebook jugadores_futbol_clustering.ipynb
   ```

---

## 📊 Resultados esperados

- Identificación de patrones en los jugadores según atributos numéricos.  
- Visualización de relaciones entre variables.  
- Agrupamiento de jugadores en clusters con roles equivalentes.  
- Representación gráfica en 2D de los clusters.  

---

## 📄 Licencia

Este proyecto se distribuye bajo la licencia **MIT** – libre para usar y modificar.

---

✍️ Autor: [Dalma Micaela Márquez](https://github.com/Dalmatian314)
