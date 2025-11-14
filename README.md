# Análisis Computacional y Visual del Firefly Algorithm: Simulación del Comportamiento Colectivo en Sistemas Biológicos Multimodales

## 👥 Autores
- Wilmer Alexis Leal Duran
- Nelsis Zulay Cassiani

## 🎯 Objetivo
Implementar y analizar computacionalmente el Firefly Algorithm para estudiar el comportamiento colectivo emergente en sistemas biológicos multimodales, validando sus propiedades de optimización mediante simulaciones y visualizaciones avanzadas.

## 🔬 Analogía Biológica
El algoritmo simula el comportamiento de fototaxis observado en poblaciones de luciérnagas, donde individuos se atraen mutuamente mediante señales lumínicas.

## 📊 Datos y Paisaje Multimodal
Se diseñó un paisaje sintético multimodal compuesto por tres óptimos gaussianos:

| Pico | Coordenadas | Intensidad |
|------|-------------|------------|
| Pico 1 | (4.0, 4.0) | 1.0 |
| Pico 2 | (-3.0, 3.0) | 0.8 |
| Pico 3 | (2.0, -4.0) | 0.7 |

**Población**: 20 luciérnagas  
**Generaciones**: 100  
**Espacio de búsqueda**: [-8, 8] × [-8, 8]

## ⚙️ Parámetros del Algoritmo
- β₀ = 1.0 (Atracción máxima)
- γ = 0.15 (Coeficiente de absorción)
- α = 0.25 → 0.0 (Aleatoriedad con decaimiento)

## 📈 Resultados Principales
- **Distribución final**: Pico 1: 40%, Pico 2: 30%, Pico 3: 20%, No convergentes: 10%
- **Transición exploración→explotación**: 70% → 65%
- **Correlación intensidad-distancia**: r = -0.72

## 🎥 Video Explicativo
[Enlace al video de YouTube](https://youtu.be/3SSwJup2JWk?si=TwyoHe8kyu6JoVkF)

## 🚀 Cómo Ejecutar
Abre el notebook en Google Colab:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1K9pHSB1ykeSvqCDK2y3t69kRLKxqqwlY?usp=sharing)

## 📁 Estructura del Proyecto
- `Firefly_Algorithm_Simulation.ipynb` - Notebook principal
- `README.md` - Este archivo
- `informe_final.pdf` - Informe de resultados

## 📄 Licencia
Este proyecto se distribuye bajo licencia MIT.

---
*Proyecto desarrollado para el curso de Algoritmos Evolutivos y Bioinspirados*