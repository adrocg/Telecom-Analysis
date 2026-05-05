# Telecom-Analysis
## DA-S7 Final Project

Este repositorio contiene el análisis realizado durante el Sprint 7 de la empresa de TeleComunicaciones, ConnectaTel.

Se utilizaron 3 fuentes diversas de datos/datasets: `plans.csv`, `users_latam.csv`, `usage.csv`. Los cuales incluyen 4,000 usuarios en LatAm, de clientes con valores faltantes, sentinels y outliers.

## 📂 Contenido del repositorio

- `notebooks/everpeak_analysis.ipynb`
  → Notebook principal con limpieza, EDA, distribuciones, outliers y conclusiones.

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1zETaRaTyY4wpVdr9cj41URbtcP1i66UO?usp=sharing)

O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

## 📘 Cómo reproducir el análisis

1. Abre `notebooks/everpeak_analysis.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)

## 🧠 Objetivo del análisis

El objetivo es identificar patrones de uso, detectar comportamientos atípicos y comprender qué segmentos de clientes muestran necesidades diferenciadas, con el fin de optimizar la oferta comercial y mejorar la experiencia del usuario.

- ¿Qué segmentos de clientes muestran mayor o menor uso de llamadas y mensajes?
- ¿Qué usuarios presentan valores atípicos que puedan indicar comportamientos inusuales, fraude o errores de registro? 
- ¿Cómo varía el uso según la edad y el tipo de plan contratado?
- ¿Qué patrones pueden ayudar a diseñar mejores planes, optimizar la oferta y mejorar la satisfacción del cliente?
