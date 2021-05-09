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
<img src="">

### Optimización en Cython

https://optimizacion-2-2021-1-gh-classroom.github.io/practica-2-segunda-parte-yefovar/
