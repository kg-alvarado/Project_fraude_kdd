# Detección de Fraude Bancario con el modelo KDD

Proyecto final · SINF-633 Análisis Exploratorio de Datos · Universidad Cenfotec

**Pregunta central:** ¿Qué patrones permiten distinguir transacciones bancarias legítimas de fraudulentas, y cómo puede el banco operacionalizar esos patrones para reducir pérdidas sin degradar la experiencia del cliente legítimo?

## Estructura
- `proyecto_kdd_fraude.ipynb`: notebook con las 5 etapas del KDD
- `data/`: carpeta para el dataset `transacciones_bancarias.csv` (no se sube al repositorio, ver `data/LEEME.md`)
- `figuras/`: gráficos generados por el notebook
- `informe/informe_tecnico.pdf`: informe técnico
- `presentacion/presentacion_defensa.pptx`: presentación para la defensa
- `requirements.txt`: librerías necesarias

## Cómo ejecutarlo
1. Instalar las librerías: `pip install -r requirements.txt`
2. Poner `transacciones_bancarias.csv` dentro de la carpeta `data/`
3. Cambiar la ruta del CSV en la celda 1.1 por `data/transacciones_bancarias.csv` (en Colab se usa `/content/sample_data/transacciones_bancarias.csv`)
4. Ejecutar todas las celdas

La versión de scikit-learn está fijada en 1.6.1 porque los resultados del Random Forest pueden cambiar un poco con otras versiones.

## Herramientas
Usé claude como apoyo para estructurar el código y redactar parte de los enunciados y crear el README, las decisiones del análisis, la revisión de los resultados y las conclusiones son mías, tambien use principalmente google colab, seaborn, pandas, entre otras librerias para la finalizacion del proyecto.
