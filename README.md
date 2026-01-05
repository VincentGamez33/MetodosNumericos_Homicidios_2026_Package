# Análisis Numérico de la Tasa de Homicidios en México (2015-2025)

Este repositorio contiene el ecosistema completo del proyecto final para la asignatura de **Métodos Numéricos II** en la Escuela Superior de Física y Matemáticas (**ESFM-IPN**). El trabajo integra un artículo de investigación académica con una implementación robusta en Python para el análisis de series de tiempo sociológicas.

## 📊 Estructura del Proyecto

El repositorio está organizado siguiendo el flujo metodológico del estudio:

- **📄 Documentación**: `Articulo_Investigacion_Chavarria_Gamez.pdf` (Consultar para el rigor matemático y análisis de resultados).
- **💻 Code/Python/**:
    - `01-Limpieza Datos/`: Pre-procesamiento de la base oficial del Secretariado Ejecutivo del Sistema Nacional de Seguridad Pública (SESNSP).
    - `02-Interpolacion/`: Implementación de Lagrange global y por bloques para el análisis del Fenómeno de Runge.
    - `03-Splines/`: Desarrollo de **Splines Cúbicos Naturales** ($C^2$).
    - `04-Diferenciacion/`: Cálculo de tasas de cambio instantáneas mediante esquemas de 5 puntos ($O(h^4)$).
    - `05-Integracion/`: Cuadratura numérica (Riemann, Trapecio y Simpson 1/3) para el cálculo de impacto acumulado.
- **📁 Fuente LaTeX**: Archivos `.tex`, clases y fuentes necesarias para la compilación del documento.

## 🛠️ Instalación y Uso

### Python (Análisis de Datos)
Los scripts están diseñados para ser ejecutables de manera modular.
1. Clonar el repositorio.
2. Instalar dependencias: `pip install -r requirements.txt`.
3. Ejecutar los scripts en orden numérico para replicar el análisis desde la limpieza de datos hasta la integración final.

### Edición y Compilación de LaTeX
El artículo fue escrito y compilado originalmente en **Overleaf**. 
- **Motor**: LuaLaTeX.
- **Paquetes**: Se incluyen todos los archivos de estilo (`.cls`), fuentes (`Fonts/`) y configuración (`Setup/`) necesarios para la reproducción fiel del formato *Disquisitio Elementalis*.

Para editarlo localmente o en Overleaf:
1. Sube la carpeta raíz al dashboard de Overleaf.
2. Asegúrate de seleccionar **Menu > Compiler > LuaLaTeX**.

## 🔬 Resumen de Hallazgos
El estudio demuestra que la interpolación global es insuficiente para datos con alta variabilidad, mientras que los Splines Cúbicos proporcionan la estabilidad y suavidad necesaria para identificar crisis asincrónicas en la seguridad pública de México.

---
**Autor:** Vicente Chavarría Gámez  
**Profesor:** Alejandro Soto González  
**Institución:** Escuela Superior de Física y Matemáticas, IPN.
