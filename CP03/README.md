## README

### Caso Práctico 03: Pruebas PISA

The data set has been constructed using average Science scores by country from the Programme for International Student Assessment (PISA) 2006, along with GNI per capita (Purchasing Power Parity, 2005 dollars), Educational Index, Health Index, and Human Development Index from UN data. The key variables are as follows:

El conjunto de datos se ha construido utilizando la puntuación media en Ciencias por país del Programa para la Evaluación Internacional de Estudiantes (PISA) 2006, junto con el GNI per cápita (paridad del poder adquisitivo, dólares de 2005), el índice educativo, el índice de salud y el índice de desarrollo humano de la ONU (HDI).

Las variables clave son las siguientes:

- Overall Science Score (average score for 15 year olds)
- Interest in science
- Support for scientific inquiry
- Income Index
- Health Index
- Education Index
- Human Development Index (composed of the Income index, Health Index, and Education Index)

El objetivo es modelizar la relación entre la puntuación media (OSS) y el resto de variables, utilizando modelos de splines y GAM. Se debe realizar CV cuando se pueda.

Los datos se encuentran en el fichero `pisasci2006.csv`

### Structure

- README.md <- The top-level README for developers.

- data

	- 01_raw <- Immutable input data


- html <- html of the rmd.

- outline <- exercise information.

- rmd <- r markdowns.

