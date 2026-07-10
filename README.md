# ConnectaTel – Proyecto Estudiantil Sprint 7

## 📌 Objetivo del proyecto
Analizar el comportamiento de los usuarios de ConnectaTel, identificando patrones de uso, segmentación por niveles de consumo y oportunidades comerciales. El proyecto proporciona insights accionables para mejorar los planes de servicio y la experiencia del cliente.

## 📂 Datasets utilizados
- **S7 Version-Estudiante-Project-ConnectaTel.ipynb**: Notebook con datos de usuarios y métricas de uso.
- Variables clave:
  - Edad (`age`)
  - Cantidad de mensajes (`cant_mensajes`)
  - Cantidad de llamadas (`cant_llamadas`)
  - Minutos totales de llamadas (`cant_minutos_llamada`)
  - Tipo de plan (`plan`)

## 🛠 Etapas del análisis realizadas
1. **Limpieza de datos**
   - Reemplazo de valores faltantes y sentinels.
   - Conversión de fechas y manejo de valores nulos.
2. **Análisis exploratorio**
   - Resumen estadístico de variables numéricas.
   - Distribución de variables categóricas.
3. **Visualización**
   - Histogramas y boxplots para detectar outliers.
   - Comparación de segmentos por edad y plan.
4. **Segmentación de usuarios**
   - Grupos por nivel de uso: Bajo, Medio, Alto.
   - Grupos por edad: Joven, Adulto, Adulto mayor.
5. **Detección de outliers**
   - Identificación de usuarios intensivos y extremos.
6. **Insights ejecutivos**
   - Recomendaciones para mejorar planes y estrategias comerciales.

## ⚡ Cómo ejecutar el notebook
- Abre el archivo `.ipynb` en [Google Colab](https://colab.research.google.com/).
- Alternativamente, usa **Jupyter Notebook** en tu computadora local.
- Ejecuta las celdas en orden para reproducir el análisis completo.

## 📝 Breve guía de reproducción
1. Cargar el notebook en Colab o Jupyter.
2. Asegurarse de que las librerías de Python necesarias estén instaladas (`pandas`, `seaborn`, `matplotlib`).
3. Ejecutar todas las celdas para generar los gráficos y resultados.
4. Consultar las secciones de **Insights** y **Segmentación** para interpretar los hallazgos.