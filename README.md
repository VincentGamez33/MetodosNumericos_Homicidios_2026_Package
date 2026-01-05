# Análisis Numérico de la Tasa de Homicidios en México (2015-2025).

Este repositorio contiene el ecosistema completo del proyecto final para la asignatura de **Métodos Numéricos II** en la Escuela Superior de Física y Matemáticas (**ESFM-IPN**). El trabajo integra un artículo de investigación académica con una implementación robusta en Python para el análisis de series de tiempo sociológicas.

## 🖼️ Vista Previa del Proyecto

<p align="center">
  <img src="Github/Articulo_Investigacion_Chavarria_Gamez_Vicente_2026_p1.jpg" width="600" alt="Portada del Artículo">
</p>

<p align="center">
  <img src="Github/Articulo_Investigacion_Chavarria_Gamez_Vicente_2026_p11.jpg" width="600" alt="Análisis de Velocidad">
</p>

<p align="center">
  <img src="Github/Articulo_Investigacion_Chavarria_Gamez_Vicente_2026_p12.jpg" width="600" alt="Validación Numérica">
</p>

---

## 📊 Estructura del Proyecto

El repositorio está organizado siguiendo el flujo metodológico del estudio:

- **📄 Documentación**: `Articulo_Investigacion_Chavarria_Gamez.pdf` (Consultar para el rigor matemático y análisis de resultados).
- **💻 Code/Python/**:
    - `01-Limpieza Datos/`: Pre-procesamiento de la base oficial del SESNSP.
    - `02-Interpolacion/`: Análisis del Fenómeno de Runge mediante Lagrange global y por bloques.
    - `03-Splines/`: Desarrollo de **Splines Cúbicos Naturales** ($C^2$).
    - `04-Diferenciacion/`: Cálculo de tasas de cambio instantáneas con esquemas de orden $O(h^4)$.
    - `05-Integracion/`: Cuadratura numérica (Riemann, Trapecio y Simpson 1/3).
- **📁 Fuente LaTeX**: Archivos `.tex`, clases y fuentes para compilación.

## 🛠️ Instalación y Uso

### Python (Análisis de Datos)
1. Clonar el repositorio.
2. Instalar dependencias: `pip install -r requirements.txt`.
3. Ejecutar los scripts en orden numérico para replicar el análisis.

### Edición y Compilación de LaTeX
El artículo fue desarrollado en **Overleaf**.
- **Motor**: LuaLaTeX.
- **Configuración**: Se incluyen archivos `.cls`, carpetas de fuentes y bibliografía. Para compilar, asegúrese de seleccionar LuaLaTeX en el menú de configuración de Overleaf o su editor local.

## 🔬 Resumen de Hallazgos
El estudio demuestra la inestabilidad de la interpolación polinómica global ante datos con alta variabilidad. Se propone el uso de Splines Cúbicos para garantizar la suavidad necesaria en la identificación de crisis de seguridad asincrónicas y la cuantificación del impacto social acumulado.

---
**Autor:** Vicente Chavarría Gámez  
**Profesor:** Alejandro Soto González  
**Institución:** Escuela Superior de Física y Matemáticas, IPN.
