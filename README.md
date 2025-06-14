# Análisis de Ventas por Tienda - Challenge Alura Latam

Este proyecto en Python analiza los datos de ventas de cuatro tiendas y genera estadísticas clave, así como gráficos para visualizar los resultados. Está basado en datos públicos del challenge de ciencia de datos de Alura Latam.

El programa realiza las siguientes acciones:

- Calcula el **ingreso total** por tienda.
- Determina el **producto más y menos vendido** por categoría.
- Calcula el **costo de envío promedio** por tienda.
- Calcula la **calificación promedio** de cada tienda.
- Genera diferentes **gráficas con `matplotlib`** para visualizar:
  - Ingresos totales por tienda.
  - Costos de envío promedio.
  - Calificaciones promedio.

# Estructura del proyecto

- Descarga los archivos CSV de cada tienda directamente desde GitHub.
- Usa la librería `pandas` para análisis de datos.
- Usa `matplotlib.pyplot` para generar las gráficas.

# Requisitos

Asegúrate de tener Python 3 instalado y ejecuta:

```bash
pip install pandas matplotlib
