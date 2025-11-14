# 🚨 Análisis de Accidentes de Tráfico (Streamlit App)

Este proyecto analiza accidentes de tráfico utilizando Python, geolocalización y un dashboard interactivo creado en **Streamlit**.

## 🎯 Objetivo
Identificar:
- Zonas con mayor siniestralidad ("puntos negros").
- Horas y días con más accidentes.
- Tipos de vehículo más involucrados.
- Evolución temporal.

## 🛠 Tecnologías
- Python (Pandas, Plotly, Folium, GeoPandas)
- Streamlit
- Notebooks Jupyter
- Visualización en mapas (HeatMap)

## 📂 Estructura del proyecto
accidentes-trafico-streamlit/<br>
├── data/<br>
├── notebooks/<br>
├── src/<br>
├── app/<br>
└── README.md<br>

## ▶ Ejecutar la app
streamlit run app/streamlit_app.py

## 📊 Funcionalidades
- Filtros por año y mes  
- Histograma por hora  
- Histograma por día de la semana  
- Accidentes por tipo de vehículo  
- Mapa de calor interactivo (Folium)  

## 📚 Dataset recomendado
Puedes usar los datos abiertos de la DGT:  
https://www.dgt.es/menusecundario/dgt-en-cifras/dgt-en-cifras-resultados/dgt-en-cifras-detalle/Ficheros-de-microdatos-de-accidentes-con-victimas-2024<br><br>
https://www.dgt.es/menusecundario/dgt-en-cifras/dgt-en-cifras-resultados/dgt-en-cifras-detalle/Datos-municipales-Siniestralidad-2023/<br><br>
https://seguridadvial2030.dgt.es/practicas-de-interes/datos-y-conocimiento-para-una-gestion-basada-en-riesgos/Aplicacion-CIDE-Catalogo-Interactivo-de-Datos-Estadisticas-sobre-Seguridad-Vial/index.html<br>

---
