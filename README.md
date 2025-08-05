# ⚡ Red Pulsos del Territorio

Este repositorio contiene el proyecto de base de datos para modelar y analizar el mercado eléctrico colombiano. Bajo el nombre “Red Pulsos del Territorio” capturamos la idea de una red energética viva, dinámica y conectada a su región.

## 🌎 Contexto

La empresa ficticia Red Pulsos del Territorio gestiona varias plantas de generación eléctrica en regiones de Colombia. Cada planta se describe por nombre, ubicación, tipo de tecnología y capacidad de generación. Los clientes (residenciales, comerciales e industriales) contratan paquetes energéticos según volumen (GWh), precio y duración. Todas las transacciones históricas quedan registradas para análisis de flujo, tendencias y rentabilidad.

## 🗂 Estructura del Proyecto

- `README.md`  
  Visión general, estructura y propósito del proyecto.  
- `docs/`  
  Documentación ampliada: dinámica del proyecto, fuentes y roadmap.  
- `modelo_datos/`  
  Diagrama ER, modelo relacional y diccionario de datos.  
- `sql/`  
  Scripts DDL (creación de tablas) y DML (población de datos)  
- `datasets/`  
  Archivos CSV con datos reales o representativos del sector.  
- `powerbi/`  
  Dashboard interactivo (.pbix) para exploración visual.  
- `notebooks/`  
  Jupyter notebooks con análisis y limpieza en Python.  
- `equipo/`  
  Roles, tareas y coordinación interna del equipo.  

## 🔍 Preguntas de Negocio

1. Qué tipo de cliente consume más energía en cada región  
2. Qué planta genera mayor rentabilidad según precio vs. capacidad  
3. Cómo varía el flujo energético a lo largo del año por tipo de planta  

## 🛠 Tecnología y Fuentes

- Base de datos en mySQL / SQL Server  
- Power BI para visualización  
- Python + Pandas para exploración en notebooks  
- Datos de SIMEM, datos.gov.co y repositorios públicos de GitHub  

## 🎯 Objetivos

- Diseñar un modelo relacional coherente y escalable  
- Implementar scripts SQL con restricciones de integridad  
- Extraer insights a través de consultas y visualizaciones  
- Facilitar la toma de decisiones con un dashboard interactivo  

## 🤝 Créditos

Proyecto desarrollado por el equipo Red Pulsos del Territorio  
Mentoría y revisión: [
Edgar Renteria
Moguel Ramirez
Valentina Alzate ]  

---

En la carpeta `docs/` encontrarás el PDF de la dinámica original y un listado de fuentes para alimentar el modelo con datos abiertos. ¡Manos a la obra!
