# Sistema Difuso de Priorización de Pacientes

## Descripción

Este proyecto es un prototipo académico que utiliza lógica difusa para simular la asignación de una prioridad de atención a un paciente.

El programa recibe tres datos:

- Temperatura corporal.
- Presión arterial sistólica.
- Nivel de dolor.

Estos datos son procesados mediante funciones de pertenencia y reglas difusas. Como resultado, el sistema genera una prioridad numérica de 0 a 100 
y una clasificación:

- Baja
- Media
- Alta
- Crítica

Este proyecto utiliza datos simulados y tiene fines exclusivamente académicos. No debe utilizarse para tomar decisiones médicas reales.

## Rama de Inteligencia Artificial

La rama utilizada es Lógica Difusa, ya que permite trabajar con valores que pueden pertenecer parcialmente a varias categorías, en lugar de utilizar 
únicamente decisiones de verdadero o falso.

## Tecnologías utilizadas

- Python
- NumPy
- Pandas
- Scikit-Fuzzy
- Matplotlib
- Google Colab
- GitHub

Las versiones utilizadas se encuentran en el archivo `requirements.txt`.

## Archivos del proyecto

- `triaje.ipynb`: código principal del prototipo.
- `requirements.txt`: dependencias necesarias.
- `pacientes_prueba.csv`: datos simulados utilizados para probar el sistema.
- `resultados_prueba.csv`: resultados generados por el sistema.

## Funcionamiento

1. Se ingresan la temperatura, presión y nivel de dolor.
2. El programa valida que los valores estén dentro de los rangos permitidos.
3. Los valores se convierten en conceptos difusos.
4. Se aplican reglas del tipo SI...ENTONCES.
5. El sistema calcula una prioridad.
6. Se obtiene una clasificación baja, media, alta o crítica.

## Cómo ejecutar el proyecto

1. Abrir `triaje.ipynb` en Google Colab.
2. Ejecutar las celdas en orden.
3. Esperar a que se instalen las dependencias.
4. Introducir los datos solicitados.
5. Consultar la prioridad obtenida.

## Datos de prueba

Los datos utilizados en este proyecto son simulados y fueron creados exclusivamente para comprobar el funcionamiento del prototipo.

No se utilizaron datos de pacientes reales.

## Créditos y fuentes

El proyecto utiliza las siguientes herramientas y librerías:

- Python: https://www.python.org/
- NumPy: https://numpy.org/
- Pandas: https://pandas.pydata.org/
- Scikit-Fuzzy: https://scikit-fuzzy.readthedocs.io/
- Matplotlib: https://matplotlib.org/
- Google Colab: https://colab.research.google.com/

## Uso de Inteligencia Artificial

Durante el proyecto se utilizó inteligencia artificial como herramienta de apoyo para:

- Organizar la estructura del prototipo.
- Orientar la programación de la lógica difusa.
- Explicar las funciones de pertenencia.
- Proponer reglas difusas.
- Apoyar en la creación de validaciones y casos de prueba.
- Organizar la documentación.

El equipo revisó, ejecutó y modificó las propuestas generadas antes de incorporarlas al proyecto.

El uso de IA también se registra en la bitácora de prompts solicitada para el proyecto.

## Limitaciones

Este sistema es únicamente un prototipo académico.

Los rangos, reglas y funciones de pertenencia utilizados no corresponden a un protocolo médico validado.

## Integrantes

- Christopher Palacios Lindo
- Miguel Yosafat Camarillo Villanueva
- Evelyn Monserrat López Carrera
- Jeovani Sánchez Sánchez
