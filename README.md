# La previa a la PyConAr 2020


Para que ya tengan su ambiente de trabajo preparado, dejo aquí los requerimientos mínimos y una guia de como prepararlo.

## Requerimientos

El requerimiento para realizar este taller es tener un ambiente con python3 y las siguientes librerías:

 - JupyterLab o Jupyter Notebook
 - sympy
 - bqplot
 - voila
 - pandas

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

Alguno de estos comandos ( depende del ambiente y la consola ):

```bash
conda activate previa-pyconar
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