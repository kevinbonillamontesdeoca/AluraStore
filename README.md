🚀 ¡Bienvenido al Análisis de Datos de Alura Store!

Hola 👋, aquí encontrarás todo lo necesario para entender cómo vimos las ventas de las 4 tiendas de Alura Store y recomendamos cuál sería la mejor para vender.

📂 ¿Qué hay en este repositorio?

📂 alura-store-analysis/
README.md: Guía y contexto del proyecto.

exploracion.ipynb: Notebook con el análisis paso a paso en Colab.

data/

tienda_1.csv: Datos de ventas Tienda 1.

tienda_2.csv: Datos de ventas Tienda 2.

tienda_3.csv: Datos de ventas Tienda 3.

tienda_4.csv: Datos de ventas Tienda 4.

🛠️ Cómo empezar

Clona este repositorio:

git clone https://github.com/kevinbonillamontesdeoca/AluraStore.git
cd AluraStore

Crea un entorno virtual (opcional, pero recomendado):

python3 -m venv venv
source venv/bin/activate   # Linux/macOS
venv\Scripts\activate    # Windows

Instala las dependencias:

pip install -r requirements.txt

El archivo requirements.txt incluye:

pandas
matplotlib

🚀 ¿Cómo usarlo?

Abre Google Colab y carga AluraStoreLatam.ipynb.

Ejecuta las celdas en orden:

Carga de datos desde GitHub.

Limpieza y exploración para ver nulos o irregularidades.

Cálculo de métricas: ingresos, ventas por categoría, calificaciones, top/bottom productos, costo de envío.

Visualizaciones: gráficos de barras, pastel, boxplot, línea y mapas.

Observa al final los gráficos resumen para identificar la tienda con menor rendimiento.

🔍 ¿Qué analizamos?

Ingresos Totales: ¿Cuál tienda factura más? 💰

Ventas por Categoría: ¿Qué productos dominan? 🛋️📱🧸

Satisfacción del Cliente: ¿Cómo califican las tiendas? ⭐

Top/Bottom Productos: Lo que más y menos se vende. 🏆👇

Costo de Envío Promedio: ¿Quién cobra más por el envío? 🚚

Análisis Geográfico (Opcional): Mapa de dispersión y heatmap para ver dónde compran más. 🗺️

Resumen Gráfico: Tres gráficos clave para entenderlo todo de un vistazo.
