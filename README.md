# Clases del curso 1 de la Asignatura 86.05/66.74 - Señales y Sistemas de la FIUBA

## Instalación de las herramientas de trabajo

### Jupyter

Para esta materia utilizaremos los [*jupyter notebooks*](https://jupyter.org/) que permiten visualizar código, imágenes y comentarios en un navegador web. Hay diferentes maneras de instalar el programa Jupyter (el cual permite correr los *notebooks* de este repositorio), aunque una de las más estandarizadas es a través de la distribución [Anaconda](https://www.anaconda.com/) del paquete abierto y gratuito [Conda](https://conda.io/en/latest/). Se recomienda fueremente utilizar este método para evitar problemas de compatibilidad con los notebooks del presente repositorio.

Para instalar Anaconda en Linux, Windows o iOS se debe descargar el instalador correspondiente desde [este](https://www.anaconda.com/products/distribution) link y seguir los pasos [esta](https://docs.anaconda.com/anaconda/user-guide/getting-started/#) sección de la documentación. La documentación completa de Anaconda puede ser encontrada en [este](https://docs.anaconda.com/) link.

La instalación de Anaconda incluye por defecto la última versión de Python, por lo que ya es posible utilizar Python desde una terminal o desde Jupyter.

### Julia

Para instalar Julia en Linux, Windows o iOS se recomienda seguir los pasos de la [página oficial](https://julialang.org/), los cuales se encuentran en [este](https://julialang.org/downloads/platform/) link. Se recomienda, además, instalar la última versión estable de Julia que corresponda al sistema operativo usado, el cual puede hacerse desde [este](https://julialang.org/downloads/) link.

Luego de instalar Julia, se debe abrir una terminal de Julia y ejecutar los siguentes comandos:

```Julia
using Pkg
Pkg.add("IJulia")
```
Una vez hecho esto, puede cerrarse la terminal y abrir *Jupyter* para verificar que es posible crear un notebook que corra código en Julia.


