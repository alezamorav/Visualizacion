# Evolución y Resiliencia de la Conectividad Aérea

Proyecto de Visualización de Datos
Universidad Técnica Federico Santa María

> **Nota:** Esta es una primera versión preliminar del repositorio. Tanto el contenido como la estructura están sujetos a modificaciones conforme avanza el desarrollo del proyecto.

## Integrantes
* Alejandra Zamora
* Yamandú Lettieri
## Descripción
El mapa de vuelos ha experimentado una reconfiguración post-crisis. Actualmente, el tráfico aéreo de pasajeros presenta caídas continuas, sumado a disrupciones operativas documentadas. 

El objetivo de este proyecto es identificar las rutas resilientes para anticipar necesidades de infraestructura.

## Pregunta de Investigación
¿Cómo ha evolucionado el flujo de pasajeros y cuáles rutas son los nodos más estables hoy?

## Alcance
* **Foco:** Movilidad humana (excluye carga comercial y vuelos militares)
* **Geografía:** Vuelos con origen o destino en Chile.
* **Periodo:** 2022 al 2026.

## Datos
La fuente de información corresponde a los registros de la Junta de Aeronáutica Civil (JAC), obtenidos mediante el Portal de Datos Abiertos del Estado.

* **Registros:** +24.000 observaciones mensuales de tráfico.
* **Unidad de observación:** Flujo mensual agregado de pasajeros operado por una aerolínea en una ruta específica.
* **Variables principales:** Año, Mes, ORIG_1_N, DEST_1_N, ORIG_1_PAIS, DEST_1_PAIS, Operador, PASAJEROS.

## Estructura del Repositorio
## Estructura del Repositorio

    Visualizacion/
    ├── data/
    │   ├── raw/
    │   └── processed/
    ├── notebooks/
    │   └── 01_exploracion.ipynb
    ├── src/
    ├── figures/
    ├── app/
    ├── README.md
    └── .gitignore

**Propósito de las carpetas y archivos:**
* `data/raw/`: datos originales sin modificar.
* `data/processed/`: datos generados luego de limpieza y transformación.
* `notebooks/`: exploración, limpieza, análisis y pruebas.
* `src/`: funciones o código reutilizable.
* `figures/`: gráficos y recursos visuales.
* `app/`: aplicación Streamlit u otros componentes del producto final.
* `README.md`: documentación principal del proyecto.
* `.gitignore`: archivos que no deben almacenarse en GitHub.
