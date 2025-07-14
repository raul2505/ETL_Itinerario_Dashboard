# ETL_Itinerario_Dashboard
Este proyecto implementa un proceso completo de **ETL (Extract, Transform, Load)** sobre un dataset de itinerarios de naves y aeronaves, integrando información adicional de puertos y países.  
Los datos son transformados, limpiados y modelados para construir dashboards interactivos que permiten identificar patrones logísticos clave.

## 🎯 Objetivos

- Integrar y limpiar datos provenientes de múltiples tablas: itinerario, nave, puerto y país.
- Analizar rutas y frecuencias de carga y descarga.
- Identificar puertos y países con mayor tráfico.
- Visualizar insights estratégicos mediante dashboards interactivos (Power BI).
---

## 🗂️ Datasets utilizados

- **Itinerario**: Detalles de cada viaje, incluyendo fechas de salida y llegada, códigos de nave, puertos de carga y descarga, y países relacionados.
- **Nave**: Información sobre cada nave o aeronave (por ejemplo, código, nombre, tipo).
- **Puerto**: Datos de ubicación y códigos de los puertos utilizados.
- **País**: Códigos y nombres oficiales de países.

## 🔧 Proceso ETL

### ✅ Extracción
- Importación de datos desde archivos CSV y/o bases de datos relacionales.

### ✅ Transformación
- Eliminación de registros duplicados y tratamiento de valores nulos.
- Estandarización de códigos y nombres (puertos, países).
- Cálculo de métricas adicionales: duración de los viajes, número de escalas, rutas más utilizadas.
- Creación de tablas derivadas para análisis (por ejemplo: tabla unificada de países).

### ✅ Carga
- Generación de modelos de datos limpios y listos para ser utilizados en visualizaciones.

---

## 📊 Visualizaciones y análisis

- **Top 5 países** con mayor volumen de carga y descarga combinados.
- **Puertos más utilizados** como origen y destino.
- **Evolución mensual y anual** de los viajes.
- **Distribución de viajes por nave** (participación relativa).
- **Filtro para visualizar los viajes** en un intervalo de fechas tomando en cuenta la fecha de salida y la fecha de llegada

---

## 🚀 Herramientas y tecnologías

- Python (pandas, numpy) o Power Query para ETL.
- Power BI  para visualizaciones.
- Git y GitHub para control de versiones.

---

## Autor
ERICK JAUREGUI - Erick Jauregui Mesneses (Linkedin)
  
