# sprint7-final-project

# 📊 Proyecto 6 - Análisis de una Empresa de Telecomunicaciones (ConnectaTel)

## 📌 Descripción del Proyecto

Este proyecto fue desarrollado como parte del bootcamp de análisis de datos de TripleTen.

El objetivo principal es analizar el comportamiento de los clientes de ConnectaTel, una empresa de telecomunicaciones con operaciones en México y Colombia, para comprender cómo utilizan los servicios móviles, identificar patrones de consumo y detectar oportunidades de negocio.

A través del análisis exploratorio de datos (EDA), segmentación de clientes y detección de outliers, se busca generar insights accionables que ayuden a optimizar la oferta comercial y mejorar la experiencia del cliente.

---

# 🎯 Objetivos del Proyecto

- Analizar el uso de llamadas y mensajes de los clientes.
- Identificar problemas de calidad de datos y realizar limpieza.
- Detectar patrones de comportamiento según tipo de plan.
- Segmentar clientes por edad y nivel de uso.
- Identificar usuarios con consumo extremo (outliers).
- Generar recomendaciones de negocio basadas en los hallazgos.

---

# 🗂️ Datasets Utilizados

## `plans`
Información de los planes telefónicos disponibles:
- nombre del plan
- mensajes incluidos
- minutos incluidos
- precio mensual
- costos adicionales

## `users`
Información de los clientes:
- user_id
- nombre
- edad
- ciudad
- fecha de registro
- tipo de plan
- fecha de cancelación

## `usage`
Registro de actividad de los usuarios:
- llamadas
- mensajes
- duración de llamadas
- longitud de mensajes
- fechas de uso

---

# 🛠️ Etapas del Análisis

## 1. Exploración inicial de datos
- Revisión de estructura de datasets
- Identificación de tipos de datos
- Detección de valores nulos

## 2. Calidad y limpieza de datos
- Tratamiento de valores inválidos (`-999`, `?`)
- Conversión de fechas
- Revisión de fechas fuera de rango
- Validación de valores faltantes estructurales

## 3. Creación de métricas
- Total de mensajes por usuario
- Total de llamadas por usuario
- Total de minutos consumidos

## 4. Análisis exploratorio (EDA)
- Estadísticas descriptivas
- Distribuciones de uso
- Comparación entre planes Básico y Premium

## 5. Visualización de datos
- Histogramas
- Boxplots
- Identificación de outliers

## 6. Segmentación de clientes
- Segmentación por edad
- Segmentación por nivel de uso

## 7. Insights ejecutivos
- Hallazgos principales
- Patrones de consumo
- Recomendaciones de negocio

---

# 📈 Principales Hallazgos

- El plan Básico concentra la mayor cantidad de usuarios.
- La mayoría de los clientes presenta un uso moderado de llamadas y mensajes.
- Existen usuarios con consumo intensivo, especialmente en minutos de llamadas.
- Los outliers identificados representan comportamientos reales y potenciales clientes de alto valor.
- Los patrones de uso entre planes son similares, aunque el plan Básico tiene mayor volumen de usuarios.

---

# 💡 Recomendaciones

- Crear planes especializados para usuarios de alto consumo.
- Diseñar estrategias de fidelización para clientes frecuentes.
- Mejorar procesos de captura y validación de datos.
- Implementar campañas segmentadas por edad y nivel de uso.

---

# ▶️ Cómo ejecutar el notebook

## Ejecutar en Google Colab
1. Descargar o clonar este repositorio.
2. Abrir el archivo `.ipynb` en Google Colab.
3. Subir los datasets necesarios (`plans`, `users` y `usage`) al entorno de Colab.
4. Ejecutar las celdas en orden desde el inicio del notebook.

---

# 🔄 Guía de reproducción del análisis

Para reproducir el análisis realizado en este proyecto:

1. Cargar los datasets originales.
2. Ejecutar la limpieza y validación de datos:
   - tratamiento de valores nulos,
   - corrección de sentinels,
   - conversión de fechas,
   - validación de registros inconsistentes.
3. Generar las métricas agregadas por usuario:
   - cantidad de mensajes,
   - cantidad de llamadas,
   - minutos totales de llamadas.
4. Ejecutar el análisis exploratorio:
   - estadísticas descriptivas,
   - histogramas,
   - boxplots,
   - detección de outliers.
5. Ejecutar la segmentación de clientes por:
   - edad,
   - nivel de uso.
6. Revisar los insights ejecutivos y recomendaciones de negocio al final del notebook.


# Repositorio del proyecto:
https://github.com/jacqueline-lopez-data/sprint7-final-project  
