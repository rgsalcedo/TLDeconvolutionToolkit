# TLDeconvolutionToolkit

## Descripción
**TLDeconvolutionToolkit** es un conjunto de herramientas en Python diseñado para el análisis y deconvolución de curvas de brillo termoluminiscente (TL). Este repositorio incluye la implementación de métodos tradicionales para la estimación de parámetros cinéticos y el ajuste de curvas TL de materiales termoluminiscentes.

Los algoritmos disponibles permiten a los usuarios:
- Ajustar curvas utilizando modelos de cinética de primer y segundo orden.
- Realizar deconvoluciones empleando funciones gaussianas, lorentzianas y Voigt.
- Estimar parámetros cinéticos clave como la energía de activación ($E$), el factor de frecuencia ($s$) y la temperatura de emisión máxima ($T_m$).
- Visualizar ajustes y resultados de forma clara y reproducible.

## Características
- Métodos implementados:
  - Cinética de primer y segundo orden.
  - Modelos gaussianos, lorentzianos y Voigt.
- Herramientas de validación como el cálculo del coeficiente de determinación ($R^2$) y el Figure of Merit (FOM).
- Compatibilidad con datos experimentales de diferentes materiales TL, como GdAlO$_3$ y BaZrO$_3$:Eu$^{3+}$.

## Requisitos
- Python 3.8 o superior
- Dependencias: `NumPy`, `SciPy`, `Matplotlib`
