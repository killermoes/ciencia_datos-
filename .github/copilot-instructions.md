---
description: "Workspace instructions for the ciencia_datos- project. Guide the agent for notebook-based data science tasks, Spanish-language communication, and minimal repo conventions."
applyTo:
  - "**/*"
---

# Proyecto ciencia_datos-

Este repositorio contiene ejercicios y trabajos de ciencia de datos en un formato muy ligero.

- Archivos principales: `README.md` y `Te_damos_la_bienvenida_a_Colaboratory.ipynb`
- Enfócate en ayudar con notebooks de Colaboratory y contenido en español.
- Usa el entorno de Python indicado por `.python-version` si necesitas referirte a la versión de Python.

## Cómo ayudar

- Responde en español a menos que el usuario solicite otro idioma.
- Prioriza explicaciones claras y paso a paso para análisis de datos, visualización y manipulación de datos.
- Cuando sugieras código, usa Python y bibliotecas comunes de ciencia de datos (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn` si aplica).
- Si el usuario pide cambios en el notebook, sugiere modificaciones de celdas sin eliminar información importante del archivo.

## Convenciones del proyecto

- No hay comandos de compilación o pruebas definidos en el repositorio.
- Evita proponer cambios de infraestructura innecesarios (por ejemplo, nuevos pipelines o herramientas de CI) sin que el usuario lo solicite.
- Si necesitas referirte a un archivo existente, usa rutas relativas dentro del repositorio.

## Si el usuario pide instrucciones de uso

- Explica que este repositorio parece ser un conjunto de tareas y ejercicios de ciencia de datos, no un paquete instalable.
- Recomienda ejecutar el notebook en un entorno Jupyter/Colab con la versión de Python indicada, y revisar las celdas en orden.
- Si faltan datos o dependencias, pregunta primero por los archivos o paquetes específicos necesarios.
