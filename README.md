# Instacart · Análisis de pedidos y recompra

Proyecto del Sprint 4 de TripleTen. Analiza cuándo compran los clientes, qué productos aparecen con mayor frecuencia y qué proporción de los artículos se vuelve a pedir.

## Análisis

- Validación de cinco tablas, revisión de duplicados y tratamiento de valores ausentes.
- Comparación de los horarios de compra y de las distribuciones de pedidos por cliente y artículos por pedido.
- Identificación de productos populares, tasas de recompra y artículos que suelen añadirse primero al carrito.

En la muestra, el domingo registró más pedidos. La mediana fue de ocho artículos por pedido y la banana fue el producto que se añadió primero al carrito con mayor frecuencia.

[Abrir el notebook con tablas, gráficos y conclusiones](analisis_instacart.ipynb).

## Ejecución local

1. Descarga del proyecto de TripleTen los archivos `instacart_orders.csv`, `products.csv`, `aisles.csv`, `departments.csv` y `order_products.csv`. Colócalos junto al notebook. El análisis espera los archivos del curso separados por punto y coma.
2. Desde la raíz del repositorio, ejecuta estos comandos con Python 3.12.

   ```bash
   python -m pip install -r requirements.txt
   python -m jupyterlab analisis_instacart.ipynb
   ```

3. En JupyterLab, ejecuta todas las celdas con el kernel del entorno donde instalaste las dependencias.

El repositorio incluye las salidas de la ejecución original. Los CSV del curso se obtienen por separado.
