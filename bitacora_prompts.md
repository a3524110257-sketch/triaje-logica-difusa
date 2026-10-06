# Bitácora de prompts

Proyecto: Sistema Difuso de Priorización de Pacientes

Esta bitácora registra algunos de los prompts utilizados durante el desarrollo del prototipo.

| N.º | Fecha | Integrante | Herramienta | Prompt | Resultado obtenido | Uso |
|---|---|---|---|---|---|---|
| 1 | 04/10/2026 | [Nombre] | ChatGPT | Ayúdame a desarrollar un prototipo de lógica difusa para un sistema de triaje médico utilizando temperatura, presión arterial y nivel de dolor. | Se definió la estructura general del prototipo y las variables principales. | Modificado |
| 2 | 04/10/2026 | [Nombre] | ChatGPT | Ayúdame a crear las funciones de pertenencia para temperatura, presión, dolor y prioridad usando Scikit-Fuzzy. | Se generaron funciones de pertenencia triangulares y trapezoidales para las variables del sistema. | Modificado |
| 3 | 04/10/2026 | [Nombre] | ChatGPT | Ayúdame a crear reglas SI...ENTONCES para calcular la prioridad utilizando lógica difusa. | Se propusieron reglas difusas para relacionar temperatura, presión y dolor con la prioridad. | Modificado |
| 4 | 04/10/2026 | [Nombre] | ChatGPT | Ayúdame a crear una función que reciba temperatura, presión y dolor, valide los datos y calcule la prioridad del paciente. | Se creó la función evaluar_paciente() con validaciones y clasificación del resultado. | Modificado |
| 5 | 04/10/2026 | [Nombre] | ChatGPT | Ayúdame a crear datos simulados para probar automáticamente el sistema de lógica difusa. | Se generaron casos de prueba y archivos CSV para evaluar varios pacientes simulados. | Modificado |
