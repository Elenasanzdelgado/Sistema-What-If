# Sistema What-If para infraestructuras IIoT

Este repositorio contiene el código desarrollado para el Trabajo Fin de Grado Diseño y desarrollo de un sistema probabilístico tipo `What-If` para sistemas IIoT

## Ejecución

El proyecto ha sido desarrollado y probado en Google Colab.

1. Abrir `Sistema_What_if.ipynb` en Google Colab.
2. Montar Google Drive.
3. Comprobar que el dataset está en la ruta indicada en el notebook.
4. Ejecutar todas las celdas en orden.
5. Utilizar el menú interactivo para seleccionar el escenario What-If.

## Dataset

El dataset utilizado para los experimentos se encuentra en la carpeta zip `TON_IoT.zip`.

## Escenarios implementados

- Modelo base
- Caída de nodo crítico
- Compromiso de nodo crítico
- Mitigación de nodos críticos
- Compromiso de comunidad

## Dependencias principales

- pandas
- numpy
- networkx
- matplotlib
- scikit-learn
- python-louvain
- ipywidgets
- python-docx
