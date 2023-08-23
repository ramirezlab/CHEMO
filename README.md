# "Collaborative Chemoinformatics Open Platform" (CHEMO)

## INTRODUCCIÓN
### Diseño y modelado de fármacos: exploración de la intersección entre la ciencia de datos y el descubrimiento de fármacos.
El diseño y modelado de fármacos es un área que continúa expandiéndose en importancia en el campo del descubrimiento de fármacos. Específicamente, la ciencia del diseño de fármacos asistido por computadora (CADD, por sus siglas en inglés) ha demostrado ser fundamental para descubrir, diseñar u optimizar moléculas pequeñas que tienen el potencial de convertirse en tratamientos medicinales viables.

A medida que CADD continúa evolucionando, la ciencia de datos ha llegado a desempeñar un papel vital en el avance del descubrimiento de fármacos. La aplicación de técnicas de ciencia de datos, como el aprendizaje automático y la minería de datos, ha aumentado la eficiencia y la precisión del proceso.

"Collaborative Chemoinformatics Open Platform" (CHEMO) tiene como objetivo proporcionar una comprensión completa y profunda de los fundamentos de CADD, con énfasis en la incorporación de técnicas clave de ciencia de datos en todo momento. El curso cubre una amplia gama de contenido, que va desde los elementos fundamentales de la programación de Python, hasta el diseño de fármacos basado en estructuras y ligandos, así como la detección virtual.

CHEMO es un recurso excepcional para estudiantes, investigadores y profesionales que buscan mejorar su conocimiento de CADD y aquellos interesados en comprender el papel fundamental que desempeña la ciencia de datos en el descubrimiento de fármacos. Al tomar este curso, los participantes pueden esperar obtener una comprensión más profunda de los emocionantes desarrollos en este campo de rápido crecimiento.

## Resultados de aprendizaje

1. Conocer metodologías y entornos de programación en lenguaje de Python para usuarios de ciencias químicas y/o afines.
2. Configurar y utilizar librerías para el análisis y visualización de datos aplicados a la quimioinformática.  
3. Implementar soluciones que permitan optimizar los procesos de diseño de fármacos asistido por computador.  	 
4. Aplicar soluciones basadas en algoritmos de aprendizaje automático (Machine learning) para realizar campañas de cribado virtual basado en ligandos.  

## Contenido
- **Parte uno**. Introducción a Python
  - Variables, tipos de datos, estructuras de datos, manipulación de archivos, estructuras de control de flujo, funciones...
  - *Práctica 1 y 2*: Expresión del material genético
  - *Práctica 3*: Proteínas y aminoácidos

- **Parte dos**. DataFrames y visualización de datos
  - **2.1** Introducción a la manipulación de Estructuras de Datos avanzadas con Pandas
      - Librerias `numpy` y `pandas`
      - Limpieza y filtrado de bases de datos.
      - *Práctica 1*: Adquirir datos de ChEMBL
      
  - **2.2** Introducción a la visualización de Datos
      - Librerias `matplotlib` y `seaborn`
        - Gráficos de líneas, gráficos circulares, gráficos de barras horizontales, gráficos de barras verticales, histogramas, gráficos de radar, ...
      - *Práctica 1*: Filtrado molecular: ADME y criterios de similitud 'lead-likeness'
      - *Práctica 2*: Detección basada en ligandos: similitud de compuestos y agrupamiento de compuestos
- **Parte tres**. Machine learning
  - **3.1** Introducción a Machine Learning
  - **3.2_Práctica 1**: Modelo de clasificación de ligandos
       
## Objetivo
El objetivo de este curso es enseñar conceptos y habilidades esenciales en el diseño y modelado de fármacos. El curso está diseñado para atender a una amplia gama de estudiantes, desde principiantes hasta avanzados, y cubre múltiples temas, como una introducción a Python, manipulación y visualización de datos, diseño de fármacos basado en estructuras y ligandos, y detección virtual. El plan de estudios es modular para permitir que los instructores personalicen el material de acuerdo con sus necesidades y métodos de enseñanza.

### ¿Por qué tomar este curso?
Hay varias razones para tomar este curso. En primer lugar, proporciona una base sólida en el diseño de fármacos asistido por computadora (CADD), que es un campo cada vez más vital en el descubrimiento de fármacos. En segundo lugar, el curso está diseñado de manera integral para cubrir desde temas básicos hasta temas avanzados, lo que lo hace adecuado para estudiantes de todos los niveles. Finalmente, la flexibilidad del plan de estudios permite que se adapte a las necesidades de aprendizaje de cada uno.

### ¿Para quién es este curso?

Este curso es adecuado para estudiantes de pregrado y posgrado que deseen profundizar en el diseño de fármacos asistido por computadora (CADD) y aplicar los principios de la ciencia de datos al campo del diseño de fármacos. También es adecuado para investigadores, profesionales y científicos que deseen enriquecer su comprensión de los conceptos y técnicas de CADD.

### ¿Qué necesitas?

Para utilizar el cuaderno puedes:

- Opción 1: Clonando el repositorio a tu ordenador usando el paquete `git`.
- Opción 2: Descargándolo como archivo zip y descomprimiéndolo. 
- Opción 3: Seguir los enlaces de Google CoLab en cada cuaderno.

   **Nota**: En Windows, es necesario instalar el paquete `Git`. Puede ver las instrucciones [aquí](https://git-scm.com/download/win).
   
```console
git clone https://github.com/ramirezlab/CHEMO.git
```

**Nota**: Para abrir la consola de comandos en Windows, puede buscar “Símbolo del sistema” o "cmd" en el menú de inicio o presionar la tecla de Windows + R en tu teclado para abrir la ventana Ejecutar. Desde allí, escribe “cmd” y presiona Enter, y la ventana de la consola de comandos aparecerá.

2. Recomendamos usar el software Anaconda para una instalación limpia donde puede crear un entorno e instalar todos los paquetes necesarios.

Instalar Anaconda: [https://docs.anaconda.com/anaconda/install/](https://docs.anaconda.com/anaconda/install/)

3. Utilice el sistema de gestión de paquetes conda para crear un entorno (CHEMO). Proporcionamos un archivo de entorno (archivo yml) que contiene todos los paquetes necesarios. Una vez que se instala Anaconda, puede iniciar la línea de comando para crear el entorno e instalar los requisitos utilizando el siguiente código:

  **Nota**: Para iniciar la línea de comando de anaconda en Windows, puede buscar “Anaconda Prompt” en el menú de inicio y se abrirá la ventana de la consola de comandos.

```console
conda env create -file requisites.yml
```

El archivo `requisites.yml` debe estar en el mismo directorio donde se ejecuta el código.

4.  Activar el entorno conda
```console
conda activate chemo
```
Ahora, puede trabajar dentro del entorno conda.

5. Inicie el Jupyter notebook.
```console
jupyter notebook
```
>Ahora puede comenzar con su primer cuaderno. ¡Disfrutelo!

## Contacto


## Licencia
Este trabajo está autorizado bajo la Licencia MIT

## Citación

*******************************************************************************************

# Collaborative Chemoinformatics Open Platform (CHEMO)

## INTRODUCTION
### Drug Design and Modeling: Exploring the Intersection of Data Science and Drug Discovery
Drug design and modeling is an area that continues to expand in significance in the field of drug discovery. Specifically, the science of computer-aided drug design (CADD) has proven critical to discovering, designing, or optimizing small molecules that have the potential to become viable medicinal treatments.

As CADD continues to evolve, data science has come to play a vital role in advancing drug discovery. The application of data science techniques such as machine learning and data mining have increased the efficiency and accuracy of the process.

The Collaborative Chemoinformatics Open Platform (CHEMO) aims to provide a comprehensive and thorough understanding of CADD fundamentals, with an emphasis on incorporating key data science techniques throughout. The course covers a wide array of content, ranging from the foundational elements of Python programming, to ligand-based and structure-based drug design, as well as virtual screening.

CHEMO is an exceptional resource for students, researchers, and professionals seeking to enhance their knowledge of CADD, and those interested in understanding the critical role that data science plays in drug discovery. By enrolling in this course, participants can expect to gain a deeper understanding of the exciting developments in this rapidly-growing field.

## Learning Outcomes

1. To know methodologies and programming environments in Python language for users of chemical and/or related sciences.
2. To configure and use libraries for data analysis and visualization applied to chemoinformatics.  
3. To implement solutions to optimize computer-aided drug design processes.  
4. To apply solutions based on Machine learning algorithms to perform ligand-based virtual screening campaigns. 

## Contents
- **Part one**. Introduction to Python
  - Variables, data types, data structures, file manipulation, flow control structures, functions...
  - *Practice 1 and 2*: Expression of genetic material
  - *Practice 3*: Proteins and amino acids

- **Part two**. DataFrames and data visualization
  - **2.1** Introduction to manipulating advanced data structures with Pandas
      - `numpy` and `pandas` libraries
      - Database cleaning and filtering 
      - *Practice*: Compound data acquisition: ChEMBL
      
  - **2.2** Introduction to data visualization
      - `matplotlib` and `seaborn` libraries
        - Lineplots, pie plots, horizontal bar plots, vertical bar plots, histograms, radar plots, ...
      - *Practice 1*: Molecular filtering: ADME and lead-likeness criteria
      - *Practice 2*: Ligand-based screening: Compound similarity and compound clustering
- **Part three**. Machine learning
  - **3.1** Introduction to Machine Learning
  - **3.2_Practice 1**: Ligand classification model
       
## Objetive
The aim of this course is to teach essential concepts and skills in drug design and modeling. The course is designed to cater to a wide range of students, from novice to advanced, covering multiple topics, such as an introduction to Python, data manipulation and visualization, structure-based and ligand-based drug design, and virtual screening. The curriculum is modular to let instructors customize the material according to their needs and teaching methods.

### Why take this course?
There are several reasons for taking this course. Firstly, it provides a strong foundation in computer-aided drug design (CADD), which is an increasingly vital field in drug discovery. Secondly, the course is comprehensively designed to cover from basics to advanced topics, making it suitable for students at all levels. Finally, the flexibility of the curriculum enables it to be tailored according to one's learning needs.

### Who is this course for?

This course is suitable for undergraduate and graduate students who want to delve into computer-aided drug design (CADD) and apply the principles of data science to the field of drug design. It is also fitting for researchers, professionals, and scientists who want to enrich their understanding of the concepts and techniques of CADD.

### What do you need?

To use the notebook you can:

- Option 1: Cloning the repository to your computer using the `git` package.
- Option 2: Downloading it as a zip archive and unzipping it. 
- Option 3: Follow the Google CoLab links in each notebook. 

   **Note**: In Windows operating system, it is necessary to install the `Git` package. Please see [here](https://git-scm.com/download/win) for instructions on how to install it.

```console
git clone https://github.com/ramirezlab/CHEMO.git
```
**Note**: To open the command prompt in Windows, you can either search for “Command Prompt” or "cmd" in the Start menu or press the Windows key + R on your keyboard to open the Run dialog box. From there, type “cmd” and press Enter, and the command prompt window will appear.

2. We recommend using the Anaconda software for a clean installation where you can create an environment and install all the required packages.

Install Anaconda: [https://docs.anaconda.com/anaconda/install/](https://docs.anaconda.com/anaconda/install/)

3. Use the package management system conda to create an environment (chemo). We provide an environment file (yml file) containing all required packages. Once Anaconda is installed, you can initiate the command line to create the environment and install the requirements using the following code:
   
  **Note**: To initiate the `command line` in Windows, you can either search for "_Anaconda Prompt_" in the Start menu and the command prompt window will appear.
```console
conda env create -file requisites.yml
```

The `requisites.yml` file must be in the same directory where the code is executed.

4.  Activate the conda environment
```console
conda activate chemo
```
Now, you can work within the conda environment.

5. Start the Jupyter notebook.
```console
jupyter notebook
```
>You can now get started with your first notebook. Enjoy!

## Contact


## Licence
This work is licensed under the MIT License

## Citation


