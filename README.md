# modelado-botella-solidos-revolucion
# Modelado de una botella mediante sólidos de revolución

Proyecto académico desarrollado para la materia de **Cálculo II** de la Licenciatura en Matemáticas Aplicadas y Computación en la Facultad de Estudios Superiores Acatlán, UNAM.

## Descripción

El proyecto consiste en el modelado matemático de una botella mediante funciones por tramos y sólidos de revolución.

A partir de dimensiones aproximadas de una botella comercial, se construyó un perfil matemático dividido en distintas regiones. Posteriormente, este perfil fue utilizado para generar un modelo tridimensional y estimar propiedades geométricas como el volumen y el área superficial.

El desarrollo se realizó principalmente en Python mediante Google Colab.

## Objetivos

- Modelar el perfil de una botella mediante funciones matemáticas por tramos.
- Aplicar conceptos de cálculo integral y sólidos de revolución.
- Calcular el volumen aproximado del modelo.
- Calcular el área superficial.
- Representar gráficamente los métodos de discos y arandelas.
- Generar una visualización tridimensional de la botella.
- Comparar el resultado obtenido con una botella comercial de referencia.

## Modelo matemático

El perfil de la botella fue dividido en distintas regiones, representando cada una mediante funciones matemáticas.

Entre las secciones consideradas se encuentran:

1. Cuello.
2. Zona de transición.
3. Cuerpo principal.
4. Base.

A partir de estas funciones se utilizaron sólidos de revolución para obtener una aproximación del volumen de la botella.

La fórmula general utilizada para el volumen mediante discos es:

\[
V = \pi \int_a^b [f(x)]^2 \, dx
\]

También se trabajó con el método de arandelas cuando fue necesario:

\[
V = \pi \int_a^b \left(R(x)^2-r(x)^2\right)\,dx
\]

Para el cálculo del área superficial se utilizó la expresión:

\[
A = 2\pi \int_a^b f(x)\sqrt{1+[f'(x)]^2}\,dx
\]

## Tecnologías utilizadas

- Python
- Google Colab
- NumPy
- SymPy
- SciPy
- Matplotlib
- Plotly
- ipywidgets

## Visualizaciones

El proyecto incluye distintas representaciones gráficas utilizadas para comprender el modelo matemático y los métodos aplicados.

Entre ellas se encuentran:

- Gráficas de las funciones que forman el perfil de la botella.
- Representación de sólidos de revolución.
- Visualización del método de discos.
- Visualización del método de arandelas.
- Modelo tridimensional interactivo de la botella.

## Resultados

El modelo obtenido produjo valores aproximados de:

- **Volumen:** 605.4 cm³
- **Área superficial:** 209.7 cm²

El volumen calculado se aproxima a la capacidad de referencia de una botella comercial de 600 ml.

## Conceptos aplicados

Durante el desarrollo del proyecto se trabajaron conceptos como:

- Cálculo integral.
- Sólidos de revolución.
- Método de discos.
- Método de arandelas.
- Área superficial.
- Funciones por tramos.
- Modelado matemático.
- Integración numérica.
- Representación gráfica en Python.

## Mi participación

El proyecto fue desarrollado en equipo. Mi participación se enfocó principalmente en:

- Investigación de los fundamentos matemáticos relacionados con sólidos de revolución.
- Revisión de conceptos y teoremas de cálculo integral necesarios para el desarrollo del modelo.
- Apoyo en la implementación del código en Python.
- Desarrollo y ajuste de algunas gráficas utilizadas para representar los métodos de discos y arandelas.
- Colaboración en el análisis y representación matemática del modelo.

## Integrantes

- Luis Alberto Avendaño Zarza
- Luis Fernando Romero Velázquez
- Juan Diego Gallegos Bedolla
- Saul Renato Ortiz Jiménez

## Contexto académico

Proyecto realizado como parte de la Licenciatura en Matemáticas Aplicadas y Computación de la Facultad de Estudios Superiores Acatlán, UNAM.

Su objetivo fue aplicar conceptos de cálculo integral mediante programación y modelado matemático a un problema de diseño geométrico.
