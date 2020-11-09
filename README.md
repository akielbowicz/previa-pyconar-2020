# La previa a la PyConAr 2020


Para que ya tengan su ambiente de trabajo preparado, dejo aquí los requerimientos mínimos y una guia de como prepararlo.

## Requerimientos

El requerimiento para realizar este taller es tener un ambiente con python3 y las siguientes librerías:

 - [JupyterLab]()
 - [sympy](https://docs.sympy.org/latest/tutorial/preliminaries.html)
 - [bqplot](https://github.com/bqplot/bqplot#usage)
 - [voila](https://github.com/voila-dashboards/voila#the-voil%C3%A0-gallery)
 - [pandas](http://pandas.pydata.org/docs/getting_started/index.html#intro-to-pandas)
 - [ipywidgets](https://github.com/jupyter-widgets/ipywidgets#ipywidgets-interactive-html-widgets)

## Instalación

### Si te manejás bien con Conda 

Primero antes que nada, cloná este repositorio. Lo podés hacer descargando el [zip](https://github.com/akielbowicz/pyconar-2019-jupyter-tarea/archive/master.zip) o si tenés instalado _git_ ejecutar en la consola:

```
git clone https://github.com/akielbowicz/previa-pyconar-2020.git
cd previa-pyconar-2020
```

Si no tenés python instalado, te recomiendo bajarte [miniconda](https://conda.io/miniconda.html)

Una vez instalada:

Si estás en Windows, abrí la consola de *miniconda* desde la barra de inicio.

Si estás en un ambiente Unix, abrí la una consola de tu preferencia.

Para que conda se auto configure vas a tener que ejecutar:

```
conda init
```
 
En esa consola cambiá de directorio a donde clonaste el repositorio y ejecutá
 
```
conda env create --name previa-pyconar --file environment.yml
```

Una vez que termine de instalar todo, tenés que activar el ambiente de *conda* ejecutando:

```
conda activate previa-pyconar
```

Y despues terminar de instalar un par de herramientas de jupyter adicionales que vamos a usar 

```
jupyter labextension install @jupyter-widgets/jupyterlab-manager@2.0 bqplot @jupyter-voila/jupyterlab-preview
```

Una vez activado hay que abrir Jupyter ejecutando:

```
jupyter lab
```

Se va a abrir un navegador y ya podemos empezar a probar cosas.

# Version Online

En caso de que no puedas instalar o quieras probarlo podes usar Binder, que es un servicio gratuito para que pruebes cosas relacionadas a Jupyter.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/akielbowicz/previa-pyconar-2020.git/HEAD?urlpath=lab)

Hay que tener cuidado porque si dejas de utilizar por un tiempo la pagina el servidor apaga la instancia que estas corriendo y vas a perder todo lo que hiciste.

# Materiales

Podes empezar a trabajar yendo al cuaderno de [Introduccion](./notebooks/00_Intro.ipynb)