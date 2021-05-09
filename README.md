### Práctica 2, segunda parte

Integrantes del equipo:

| usuario   | Rol               | Persona      | Actividad   |
| --------- | ------------------| ------------|--------------|
| jreyesgar93| Project Manager    | José        | Documentación en Sphinx/Docker |
| yalidt    | Perfilmiento/Reimplementación    | Yalidt      | Perfilamiento del paquete/Reimplementación|
| yefovar   |  Reimplementación Unit Test | Yedam          | Pruebas Unitaria para verificar que el algoritmo siga funcionando con los cambios |
| mfrubio   | Perfilmiento/Reimplementación         | Fernanda    | Perfilamiento del paquete/Reimplementación|

# Paquete Simplex
Implementamos un paquete en Python que resuelve problemas de maximización de una función objetivo lineal con restricciones:

![equation](https://latex.codecogs.com/gif.latex?max_{x}\quad&space;c^{T}x) 

sujeto a:

![equation](https://latex.codecogs.com/gif.latex?Ax\leq&space;b)

![equation](https://latex.codecogs.com/gif.latex?x\geq&space;0) 

con:

![equation](https://latex.codecogs.com/gif.latex?c,x\quad\epsilon\quad\mathbb{R}^{n})

![equation](https://latex.codecogs.com/gif.latex?A\quad\epsilon\quad\mathbb{R}^{m\times&space;n})

![equation](https://latex.codecogs.com/gif.latex?b\quad\epsilon\quad\mathbb{R}^{m})

Usamos sphynx para documentar nuestro [paquete.](https://optimizacion-2-2021-1-gh-classroom.github.io/practica-1-segunda-parte-yefovar/Simplex.html#module-Simplexs)

En particular, se indicó que existen imágenes de docker que ayudan a utilizar el paquete (sin y con Kale) tal como se muestra en la siguiente imagen.
<img src="docs/images/Documentacion%20paquete%20-%20Docker.png">

### Botón de binder 
Para consultar ejemplos de implementaciones usa el boton de binder y el notebook para realizar el *testing* es reporte_equipo_3_parte_2_practica_2.ipynb

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/optimizacion-2-2021-1-gh-classroom/practica-2-segunda-parte-yefovar/HEAD)

# Perfilamiento en instancia de AWS

Para hacer más eficiente los métodos del paquete realizamos perfilamiento en instancias de AWS. Incluimos características de la instancia en la que lo realizamos.

## Perfilamiento tiempo

Para revisar la documentacion se puede accesar al siguiente [reporte.](https://github.com/optimizacion-2-2021-1-gh-classroom/practica-2-segunda-parte-yefovar/blob/main/perfilamiento/Perfilamiento_tiempo.ipynb)

## Perfilamiento memoria

Para revisar la documentacion se puede accesar al siguiente [reporte.](https://github.com/optimizacion-2-2021-1-gh-classroom/practica-2-segunda-parte-yefovar/blob/main/perfilamiento/Perfilamiento_memoria.ipynb) 

# Eficiencia del metodo

Una vez realizado el perfilamiento evaluamos cómo eficientiar  nuestro método:
1. Uso de compilación a C para secciones de su código.

Para revisar la documentacion se puedea ccesar al siguiente [reporte.](https://github.com/optimizacion-2-2021-1-gh-classroom/practica-2-segunda-parte-yefovar/blob/main/perfilamiento/Perfilamiento_tiempo_cython.ipynb)

## Optimización en Cython

La documentación del paquete se encuentra en la siguiente [liga.](https://optimizacion-2-2021-1-gh-classroom.github.io/practica-2-segunda-parte-yefovar/)

# Evidencia trabajo AWS

Se anexa evidencia de trabajo y solución del problema a través de cómputo en la nube.
<img src="https://github.com/optimizacion-2-2021-1-gh-classroom/practica-2-segunda-parte-yefovar/blob/main/docs/images/Uso%20instancia%20AWS%20-%20Practica%202%20segunda%20parte.png">
