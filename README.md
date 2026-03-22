# 📊 Análisis de Uso de Clientes - ConnectaTel
## 🎯 Objetivo del Proyecto
El objetivo de este proyecto es analizar cómo los clientes utilizan los servicios móviles (llamadas y mensajes) para:
- Identificar patrones de uso
- Detectar comportamientos atípicos (outliers)
- Segmentar a los clientes según su comportamiento
Esto permitirá a la empresa optimizar su oferta comercial y mejorar la experiencia del usuario.

# 📁 Datasets utilizados

Se utilizaron tres fuentes de datos:
## plans.csv
- Información sobre los planes disponibles (precio, minutos incluidos, GB, costos adicionales).
## users_latam.csv
- Datos de los clientes (edad, ciudad, fecha de registro, plan contratado).
## usage.csv
- Registro del uso real del servicio (duración de llamadas y mensajes enviados).
  
# 🔍 Etapas del Análisis

1. Carga y exploración de datos
    - Revisión inicial de estructura y tipos de datos
2. Identificación de problemas de calidad
    - Detección de valores nulos, inconsistencias y outliers
3. Limpieza de datos
    - Tratamiento de valores atípicos y ajustes necesarios
4. Análisis descriptivo
    - Estadísticas resumen (media, mediana, distribución)
5. Visualización
    - Histogramas y gráficos de distribución
    - Identificación visual de outliers
6. Segmentación de clientes
    - Segmentación por nivel de uso (bajo, medio, alto)
    - Segmentación por edad
7. Análisis de insights
    - Interpretación de resultados desde una perspectiva de negocio
      
# 📈 Principales Insights
- La mayoría de los usuarios presenta un nivel de uso medio
- Existe un grupo pequeño pero relevante de usuarios de alto consumo
- El plan Premium no muestra una diferenciación clara en el comportamiento de uso respecto al plan Básico
- Los outliers representan usuarios intensivos, no errores
# 💡 Recomendaciones
- Rediseñar el plan Premium para aumentar su valor percibido
- Implementar estrategias de upselling para usuarios de alto uso
- Crear incentivos para aumentar la actividad en usuarios de bajo uso
- Explorar segmentación más específica basada en comportamiento
## ⚙️ Cómo ejecutar el proyecto
### Opción 1: Jupyter Notebook (local)
1. Clonar el repositorio:
    - git clone <TU_REPO_URL>
2. Instalar dependencias:
    - pip install pandas numpy matplotlib seaborn
3. Abrir el notebook:
    - jupyter notebook
### Opción 2: Google Colab
1. Subir el notebook a Google Colab
2. Subir los archivos .csv
3. Ejecutar todas las celdas
   
# 🔁 Guía de reproducción

Para reproducir este análisis:
1. Asegúrate de tener los tres datasets en la misma carpeta
2. Ejecuta el notebook en orden (de arriba hacia abajo)
3. Verifica que las rutas de los archivos sean correctas
4. Los resultados (gráficos y segmentación) se generarán automáticamente
   
## 🧠 Autor
Proyecto realizado como análisis exploratorio de datos enfocado en segmentación de clientes y toma de decisiones de negocio.
