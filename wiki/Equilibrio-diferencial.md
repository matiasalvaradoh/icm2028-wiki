# Equilibrio diferencial

## Descripción

A lo largo de todo el curso hemos trabajado bajo el principio de que toda partícula perteneciente a un cuerpo debe estar en equilibrio, es decir que la sumatoria de las fuerzas externas e internas del cuerpo debe ser 0.
Con esta idea en mente, se pueden establecer ciertas relaciones con respecto a un área pequeña de una figura.

Consideremos el siguiente diagrama, con un área diferencial:

![diferencial.png](https://drive.google.com/uc?export=view&id=1sTzJn88XUzLmWGYkz3KFqm5-q8vnjGDE)

Además se definió las componentes del tensor de esfuerzo y con ello podemos definir una matriz con las tensiones de este elemento, considerando un área diferencial. Así, podemos definir derivadas parciales respecto a cambios diferenciales en los distintos ejes de la figura descrita con antelación.
Las cuales se describen en el siguiente diagrama:

![diferencial_parciales.png](https://drive.google.com/uc?export=view&id=1gBTL76T9UHGSPwshu9MU1oL_uhve9msS)

Ahora podemos definir las condiciones de equilibrio, que la sumatoria de momentos con respecto a un punto central del cubo sea igual a 0 y que la sumatoria de fuerzas en cada eje sea igual a 0.


<img src="https://latex.codecogs.com/svg.latex?\Large&space;\sum{F}=0"/>
<img src="https://latex.codecogs.com/svg.latex?\Large&space;\sum{M}=0"/>

Desarrollándolas:

<img src="https://latex.codecogs.com/svg.latex?\sum{M}=((\tau_{xy}\Delta_y\Delta_z)\frac{\Delta_x}{2}+[(\tau_{xy}+\frac{\partial\tau_{xy}}{\partial_x}\Delta_x)\Delta_y\Delta_z]\frac{\Delta_x}{2}-(\tau_{yx}\Delta_x\Delta_z)\frac{\Delta_y}{2}-[(\tau_{yx}+\frac{\partial\tau_{yx}}{\partial_y}\Delta_y)\Delta_x\Delta_z]\frac{\Delta_y}{2})k"/>

<img src="https://latex.codecogs.com/svg.latex?\sum{F_x}=(\sigma_x+\frac{\partial\sigma_x}{\partial_x}\Delta_x)\Delta_y\Delta_z+(\tau_{yx}+\frac{\partial\tau_{yx}}{\partial_y}\Delta_y)\Delta_x\Delta_z-\sigma_x\Delta_y\Delta_z-\tau_{yx}\Delta_x\Delta_z"/>

<img src="https://latex.codecogs.com/svg.latex?\sum{F_y}=(\sigma_y+\frac{\partial\sigma_y}{\partial_y}\Delta_y)\Delta_x\Delta_z+(\tau_{xy}+\frac{\partial\tau_{xy}}{\partial_x}\Delta_x)\Delta_y\Delta_z-\sigma_y\Delta_x\Delta_z-\tau_{xy}\Delta_y\Delta_z"/>

Simplificando estas ecuaciones llegamos a que:

<img src="https://latex.codecogs.com/svg.latex?\Large&space;\tau_{xy}=\tau_{yx}"/>


Finalmente, las ecuaciones de equilibrio diferencial en un estado de tensiones plano son:

<img src="https://latex.codecogs.com/svg.latex?\Large&space;\frac{\partial\sigma_x}{\partial_x}+\frac{\partial\tau_{xy}}{\partial_y}=0"/>

<img src="https://latex.codecogs.com/svg.latex?\Large&space;\frac{\partial\sigma_y}{\partial_y}+\frac{\partial\tau_{xy}}{\partial_x}=0"/>

## Ecuaciones generales

<img src="https://latex.codecogs.com/svg.latex?\Large&space;\frac{\partial\sigma_x}{\partial_x}+\frac{\partial\tau_{xy}}{\partial_y}+\frac{\partial\tau_{zx}}{\partial_z}=0"/>

<img src="https://latex.codecogs.com/svg.latex?\Large&space;\frac{\partial\sigma_y}{\partial_y}+\frac{\partial\tau_{xy}}{\partial_x}+\frac{\partial\tau_{yz}}{\partial_z}=0"/>

<img src="https://latex.codecogs.com/svg.latex?\Large&space;\frac{\partial\sigma_z}{\partial_z}+\frac{\partial\tau_{yz}}{\partial_y}+\frac{\partial\tau_{zx}}{\partial_x}=0"/>



Referencias:

Imágenes de: https://www.u-cursos.cl/usuario/0e81e8de7142238176399e927d26fe27/mi_blog/r/Apuntes_Resistencia_Materiales_5.pdf

AUTORA: Gisselle Poblete Ramos

