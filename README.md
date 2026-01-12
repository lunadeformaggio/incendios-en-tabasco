🔥🔥🔥 Incendios 2025 en Tabasco – Visor Web GIS  🔥🔥🔥

Se presenta un visor web interactivo desarrollado con **ArcGIS API for JavaScript (v4.34)** para la visualización, análisis temporal y exploración de incendios detectados por sensores satelitales en el periodo de enero a agosto de 2025 en el estado de **Tabasco, México**. 
El proyecto integra datos geoespaciales, control temporal, clustering dinámico y visualización estadística para apoyar el análisis ambiental y territorial.
La aplicación utiliza datos de sensores satelitales VIIRS y MODIS para proporcionar información detallada sobre eventos de fuego, incluyendo temperatura, potencia radiante y ubicación precisa. Al detectarse fuentes térmicas permanentes provenientes de pozos e instalaciones petroleras, se incluyó información relacionada a la ubicación de estos.

---

## 🗺️ Funcionalidades principales

- Visualización de incendios detectados por sensores **VIIRS / SUOMI**
- Separación de incendios:
  - 🔆 Incendios durante el día
  - 🌙 Incendios durante la noche
  - 🔥 Incendios en fuentes fijas
- Control temporal mediante **TimeSlider**
- Agrupamiento dinámico de eventos (clustering)
- Gráfica interactiva de incendios por día
- Consulta detallada mediante popups
- Visualización de:
  - Pozos de PEMEX
  - Instalaciones petroleras
  - Límite político del estado de Tabasco


---

## ⏱️ Análisis temporal

El visor utiliza campos de fecha y hora previamente corregidos a **UTC-6 (Hora local de México)**.

- El **TimeSlider** controla simultáneamente las capas de incendios.
- La gráfica se actualiza dinámicamente conforme al rango temporal seleccionado.
- Permite identificar:
  - Días con mayor número de eventos
  - Patrones temporales
  - Diferencias entre incendios diurnos y nocturnos

---

## 📊 Visualización estadística

Se incluye una gráfica de barras desarrollada con **Chart.js**, que muestra:

- Número total de incendios por día
- Actualización automática según el `timeExtent`
- Integración directa con consultas espaciales a las capas visibles

---

## 🧱 Capas incluidas

| Capa | Descripción |
|-----|------------|
| División Política de Tabasco | Límite estatal |
| Pozos de PEMEX | Pozos petroleros (iconografía SVG) |
| Instalaciones petroleras | Infraestructura petrolera |
| Incendios de fuentes fijas | Incendios asociados a fuentes puntuales |
| Incendios durante el día | Eventos detectados en horario diurno |
| Incendios durante la noche | Eventos detectados en horario nocturno |

---

## 🎨 Simbología y diseño

- Tema oscuro (`dark theme`)
- Simbología diferenciada por tipo de incendio
- Clusters personalizados con:
  - Tamaño dinámico
  - Etiquetas centradas
- Íconos SVG optimizados para uso cartográfico
- Widgets con fondo translúcido y tipografía clara

---

## 🧩 Widgets implementados

- Layer List (con leyenda por capa)
- Time Slider
- Coordinate Conversion
- Scale Bar
- Home
- Basemap Gallery (expandible)

---

## 🛠️ Tecnologías utilizadas

- **ArcGIS API for JavaScript 4.34**
- **Chart.js**
- **GeoJSON**
- **HTML / CSS / JavaScript**

---

## 📊 Fuentes
Los datos provienen de:
- Datos de incendios: FIRMS NASA https://firms.modaps.eosdis.nasa.gov/
- Datos de PEMEX: https://mapa-hidrocarburos.energia.gob.mx/



    

