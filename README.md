# DFToy

**DFToy** es un software interactivo y educativo para explorar conceptos de la **Teoría del Funcional de la Densidad (DFT)** de manera sencilla.  
Permite al usuario realizar simulaciones básicas, visualizar densidades electrónicas bajo diferentes potenciales externos y comparar resultados de forma gráfica.  

El proyecto está diseñado con una arquitectura modular basada en el patrón de diseño **Strategy**, lo que facilita extender y personalizar las simulaciones sin modificar el núcleo del sistema.

---

## ✨ Características principales

- Cálculo de densidades electrónicas para diferentes potenciales externos (armónico, pozo finito, barrera, etc.).
- Visualización gráfica de resultados en tiempo real.
- Exportación de gráficos en formatos de alta calidad (`.eps`, `.png`).
- Interfaz gráfica interactiva para:
  - Seleccionar tipo de cálculo.
  - Configurar parámetros numéricos.
  - Escoger qué resultados visualizar.
- Manejo de errores (por ejemplo, falta de convergencia o parámetros inválidos).
- Estructura extensible para agregar nuevos potenciales o métodos de cálculo.

---

## 🏗️ Arquitectura y patrón de diseño

El software utiliza el patrón **Strategy**:

- Cada método de simulación o cálculo de densidad se implementa como una **estrategia independiente**.
- La interfaz gráfica permite al usuario seleccionar la estrategia deseada en tiempo de ejecución.
- Esto facilita:
  - Extender el software agregando nuevos tipos de cálculos.
  - Mantener el código limpio y modular.
  - Reutilizar componentes comunes (visualización, manejo de archivos, etc.).

---


