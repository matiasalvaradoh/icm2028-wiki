# Ley de Hooke Generalizada

## Descripción

La ley de Hooke generalizada "establece la proporcionalidad entre las fuerzas (acciones) y desplazamientos (efectos), a la relación existente entre tensiones y deformaciones unitarias actuantes en un punto" (Cervera, 2009). 

Robert Hooke fue quien planteó esta proporcionalidad, donde básicamente existe una relación entre las tensiones que se le aplican a un cuerpo y las deformaciones que este sufre. Cabe mencionar que esta es tan solo una aproximación ya que en la vida real cada material tiene un grado de "no linealidad". Pero, de todas formas, esta ecuación nos permite obtener el campo de esfuerzos a partir del campo de deformaciones de un cuerpo.

## Fórmula

La ley de Hooke generalizada puede ser representada por la siguiente ecuación:

<img src="https://latex.codecogs.com/svg.latex?\large&space;\epsilon_{x}=\frac{1}{E}[\sigma_{x}-\nu(\sigma_{y}+\sigma_{z})]"/>


<img src="https://latex.codecogs.com/svg.latex?\large&space;\epsilon_{y}=\frac{1}{E}[\sigma_{y}-\nu(\sigma_{x}+\sigma_{z})]"/>


<img src="https://latex.codecogs.com/svg.latex?\large&space;\epsilon_{z}=\frac{1}{E}[\sigma_{z}-\nu(\sigma_{x}+\sigma_{y})]"/>

Donde sigma es la tensión, epsilon la deformación y nu el coeficiente de Poisson.

Y si se considera la variación de temperatura con su respectivo coeficiente de dilatación según el material se tiene:

<img src="https://latex.codecogs.com/svg.latex?\large&space;\epsilon_{x}=\frac{1}{E}[\sigma_{x}-\nu(\sigma_{y}+\sigma_{z})]+\alpha*\Delta*T"/>


<img src="https://latex.codecogs.com/svg.latex?\large&space;\epsilon_{y}=\frac{1}{E}[\sigma_{y}-\nu(\sigma_{x}+\sigma_{z})]+\alpha*\Delta*T"/>


<img src="https://latex.codecogs.com/svg.latex?\large&space;\epsilon_{z}=\frac{1}{E}[\sigma_{z}-\nu(\sigma_{x}+\sigma_{y})]+\alpha*\Delta*T"/>

Con alpha el coeficiente de dilatación del material.

## Ejemplo aplicado

Consideraremos un ejercicio planteado en el libro Mechanics of Solid, Crandall.

5.2 Demostrar que para deformaciones unitarias pequeñas el cambio en fracción de volumen es la suma de las componentes normales de la deformación, referidas a un sistema de 3 ejes perpendiculares.

Para ello consideremos el siguiente diagrama:

![ejemplo_crandall.png](https://drive.google.com/uc?export=view&id=1h8Df5cUvriOe6gJFfSNCbFB28ICxp0-E)

El volumen de este paralelepipedo viene por la multiplicación de todos los lados del paralelepipedo (alto por ancho por largo):

<img src="https://latex.codecogs.com/svg.latex?\large&space;v_{paralelepipedo}=\Delta_x*\Delta_y*\Delta_z"/>

Luego de aplicar cierta carga pequeña que deforma el paralelepípedo el volumen queda como:

<img src="https://latex.codecogs.com/svg.latex?\large&space;v_{paralelepipedo}=(\Delta_x+\epsilon_x*\Delta_x)*(\Delta_y+\epsilon_y*\Delta_y)*(\Delta_z+\epsilon_z*\Delta_z)"/>

Luego para calcular el cambio en el volumen del paralelepipedo, restamos el volumen final con el volumen inicial:

<img src="https://latex.codecogs.com/svg.latex?\large&space;\Delta_V=(\Delta_x+\epsilon_x*\Delta_x)*(\Delta_y+\epsilon_y*\Delta_y)*(\Delta_z+\epsilon_z*\Delta_z)-(\Delta_x*\Delta_y*\Delta_z)"/>

Desarrollando la expresión y reduciendo términos tenemos que:

<img src="https://latex.codecogs.com/svg.latex?\large&space;\Delta_V=(\epsilon_x+\epsilon_y+\epsilon_z)-(\Delta_x*\Delta_y*\Delta_z)"/>

Finalmente si dividimos el cambio del volumen entre el volumen original, la expresión que resulta es:

<img src="https://latex.codecogs.com/svg.latex?\large&space;\frac{\Delta_V}{v_{paralelepipedo}}=\epsilon_x+\epsilon_y+\epsilon_z"/>

Con ello, queda demostrada la proposición.

AUTORA: Gisselle Poblete Ramos

### Referencias:

Cervera, Resistencia de Materiales, 2009. Recuperado de: http://cervera.rmee.upc.edu/libros/Resistencia%20de%20Materiales.pdf

