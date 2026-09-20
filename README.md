# 🎮 Análisis de reseñas y ventas de videojuegos  

## 📖 Introducción  
¿Las reseñas de críticos y usuarios realmente influyen en el éxito de un videojuego?  
Este proyecto analiza datos de ventas y reseñas de videojuegos del año 2016, explorando cómo las plataformas, géneros y calificaciones impactan en la popularidad y desempeño comercial de los títulos.  

---

## 📌 Planteamiento del problema  
El mercado de videojuegos es altamente competitivo y diverso. Cada año se lanzan cientos de títulos en múltiples plataformas y géneros, pero no todos alcanzan el mismo nivel de éxito. La pregunta clave es: **¿qué factores determinan si un videojuego logra destacar en ventas?**  

---

## 🎯 Objetivos  
- **General:** Evaluar la relación entre reseñas, géneros, plataformas y ventas de videojuegos en 2016.  
- **Específicos:**  
  - Limpiar y preparar el dataset para un análisis confiable.  
  - Identificar tendencias de ventas por año, plataforma y género.  
  - Analizar la correlación entre reseñas de críticos/usuarios y ventas.  
  - Comparar diferencias regionales en preferencias de plataformas y géneros.  
  - Realizar pruebas de hipótesis para validar diferencias significativas entre plataformas y géneros.  

---

## 🧩 Hipótesis  
1. Las reseñas de críticos tienen mayor impacto en las ventas que las reseñas de usuarios.  
2. Los géneros de acción, disparos y deportes concentran la mayoría de las ventas globales.  
3. Las plataformas dominantes varían según la región (PlayStation/Xbox en occidente, Nintendo en Japón).  
4. La clasificación ESRB influye en las ventas, especialmente en Norteamérica y Europa.  

---

## 📊 Metodología  
1. **Preparación de datos:**  
   - Limpieza de columnas y tratamiento de valores ausentes.  
   - Conversión de tipos de datos (años, puntuaciones).  
2. **Análisis exploratorio:**  
   - Tendencias de lanzamientos y ventas por año.  
   - Comparación de ventas por plataforma y género.  
   - Distribución regional de ventas.  
3. **Visualización:**  
   - Gráficos de barras, boxplots y heatmaps para identificar patrones.  
4. **Pruebas estadísticas:**  
   - Prueba t de Student y Welch para comparar calificaciones entre plataformas y géneros.  

---

## 📓 Resultados principales  
- **Ventas por plataforma:** PlayStation 4 y Xbox One dominaron en occidente; Nintendo 3DS fue líder en Japón.  
- **Ventas por género:** Acción, Shooter y Deportes fueron los más rentables globalmente; RPGs destacaron en Japón.  
- **Reseñas vs. ventas:** La correlación con críticos fue positiva (≈0.37), mientras que la de usuarios fue débil.  
- **Clasificación ESRB:** Impactó más en NA y EU que en Japón.  
- **Pruebas de hipótesis:** Se confirmaron diferencias significativas entre géneros (Acción vs. Deportes), pero no entre plataformas (Xbox One vs. PC).  

---

## 🚀 Conclusión  
El análisis muestra que el éxito de un videojuego depende de una combinación de factores:  
- **Plataforma:** algunas tardan años en ganar tracción, otras declinan rápidamente.  
- **Género:** no basta con publicar muchos títulos, lo importante es la demanda del público.  
- **Reseñas:** las críticas profesionales tienen mayor peso en las ventas que las reseñas de usuarios.  
- **Región:** las preferencias culturales influyen en qué plataformas y géneros dominan.  

En resumen, los datos evidencian que entender el mercado y las reseñas es clave para anticipar el éxito de un videojuego.  

---

## 🚀 Tecnologías utilizadas  
- Python (pandas, seaborn, matplotlib, scipy)  
- Jupyter Notebook (Anaconda)  
- GitHub (portafolio)  

---

## 📌 Cómo usar  
1. Clonar este repositorio.  
2. Abrir el notebook en Jupyter.  
3. Ejecutar las celdas en orden para reproducir el análisis y visualizaciones.  

---

## ✨ Autor  
**Roberto González Espinosa de los Monteros**  
