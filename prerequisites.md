# Instalación

Una de las herramientas con las que se trabajara en este curso son los `Notebooks de Jupyter`, empleados para el análisis de datos por medio de Python y todos sus paquetes.
Para iniciar se necesita la instalación de Python, que puede variar dependiendo del sistema operativo. En nuestro caso la manera más sencilla es instalar el ambiente de trabajo Anaconda navigator, la cual permite hacer funcionar aplicaciones, como `Python` y `R`, y administrar facilmente paquetes y librerias. 

## Instalar Anaconda en Windows 10:

La descarga se puede iniciar desde la página web de Anaconda (https://www.anaconda.com/products/individual), seleccionar **products** luego **Individual Edition** la cual no requiere licencia alguna. Por último se hace clic sobre **Download** y la descarga comenzará inmediatamente.

Una vez descargado, se ejecuta el archivo instalador haciendo doble clic, se siguen los pasos de instalación del programa estableciendo la ruta deseada. Se recomienda que tengas más de 1 GB de espacio en el disco duro ya que la extracción de los paquetes de Anaconda podría superarlo.

Finalizado el proceso **Anaconda Navigator** ya estará instalado en su computadora.

**Nota**: *Para no tener problemas a futuro con las actualizaciones se aconseja que en el momento de la instalación seleccione opciones como Install for: "**Just me**" y en Advanced Options, la opción “**Register anaconda as my default python**”*.

## Instalar las librerias y paquetes necesarios para este curso

### Opción 1
1. Crear un entorno virtual con Python 3.8 
> 1 Expliar como abrir la consola de comandos de conda (Anaconda prompt) y crear un entorno con la versión de python que es estable
> 
> 2 Explicar como activar y desactivar el entorno
> 
2. Instalar las dependencias del entorno
> 3 Explicar como dependencias y versiones específicas por medio de conda (dentro del entorno)
> 
> ---- dependencias:
> jupyterlab, jupyter, pandas, numpy, rdkit, pymol, pmw, scikit-learn, seaborn, easydict, 
>  chembl_webresource_client, biopandas, pypdb.
> 
> (lo mejor es poner el comando que instala la dependencia)

### Opción 2. Instalación empaquetada
1. Descargar el documento `env_DS_for_DS.yml` y ponerlo en C:\Users\nombre_usuario
2. Desde la consola de comamdos de conda (Anaconda Prompt) ejecutar el texto
> conda env create --name DD_for_DS --file=env_DS_for_DS.yml

Esto crea el entorno e inicia la instalación y descarga de todos los paquetes / librerías / dependencias,.

## Iniciar Jupyter

2. Explicar como activar y desactivar el entorno creado
3. Iniciar Jupyter notebook

>UNA VEZ HECHO ESTO, ESTE ARCHIVO SE INTEGRA AL README
