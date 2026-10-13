# 🔱 Algoritmo Phi (1.618): El Reloj Secreto del Trading

![Version](https://img.shields.io/badge/version-1.0.0-gold)
![License](https://img.shields.io/badge/license-MIT-blue)
![Role](https://img.shields.io/badge/Engineer-Jeferson%20Leonardo%20Contreras%20Maldonado-orange)
![Tech](https://img.shields.io/badge/Tech-JavaScript%20%7C%20HTML5%20%7C%20Quant-cyan)

## 📌 Descripción General

**Algoritmo Phi** es una metodología y herramienta cuantitativa desarrollada para la optimización de ventanas de tiempo en mercados financieros (Acciones, Criptomonedas, Forex y Memecoins). 

A diferencia de los enfoques tradicionales centrados exclusivamente en la dimensión del precio, el algoritmo aplica la constante matemática de la Proporción Áurea ($\Phi = 1.618$) sobre estructuras de tiempo y rangos de acumulación para proyectar:
1. **Ventanas de Expansión (Take Profit Temporal):** Duración estimada de la ruptura (*breakout*).
2. **Stop-Loss Cuántico (Invalidación Temporal):** Tiempo límite de estancamiento del precio antes de abortar la posición y mitigar el riesgo (*drawdown*).

---

## 📐 Fundamento Matemático

El modelo utiliza la constante áurea para la proyección de expansiones de tiempo a partir de fases de consolidación lateral:

$$T_{\text{expansión}} = T_{\text{acumulación}} \times 1.618$$

$$T_{\text{stop-loss}} = \frac{T_{\text{acumulación}}}{1.618}$$

Donde:
* $T_{\text{acumulación}}$ es el tiempo medido en minutos (u otra temporalidad) que el activo permanece dentro de un rango comprimido.
* $T_{\text{expansión}}$ determina la ventana máxima de ejecución para toma de ganancias.
* $T_{\text{stop-loss}}$ fija la invalidación temporal del flujo de liquidez.

---

## 🛠️ Arquitectura y Componentes

El proyecto cuenta con un **Simulador Algorítmico Interactivo (JLCM Factor 1.618)** desarrollado en HTML5 y Vanilla JavaScript sin dependencias externas, garantizando máximo rendimiento e integración ligera.

---

## 👨‍💻 Autoría e Propiedad Intelectual

* **Autor:** Ing. Jeferson Leonardo Contreras Maldonado
* **Perfil:** Ingeniero Informático / Especialista en Arquitectura de Software & Tokenización (RWA)
* **Licencia:** Distribuido bajo la Licencia MIT.
