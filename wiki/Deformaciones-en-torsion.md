## Deformaciones en torsión

### Descripción

Para este capítulo se consideraron 3 supuestos muy importantes, los cuales determinan las siguientes ecuaciones que se expondrán.
Consideremos el siguiente cilindro:

![cilindro.png](https://drive.google.com/uc?export=view&id=1McS0sAJIiV7and9pdUVTz8VI7nX7gx3t)

Los desplazamientos están determinados con los vectores, v (desplazamiento tangencial), w (desplazamiento longitudinal) y u (desplazamiento radial). Las consideraciones a tener son las siguientes:

1) Este cilindro no cambia de largo, por lo tanto el vector de desplazamiento en w es 0.
2) Consideraremos que la sección recta permanece constante por lo tanto el vector de desplazamiento u = 0.
3) Finalmente, consideramos que el diametro de este cilindro es recto y va a permanecer recto, por lo tanto el desplazamiento v queda determinado por el radio del cilindro t el ángulo de torsión.

Luego de estas consideraciones podemos calcular las deformaciones considerando los vectores de desplazamiento definidos con antelación que viene dado por:

<img src="https://latex.codecogs.com/svg.latex?\Large&space;\varepsilon_{r}=\frac{\delta_u}{\delta_r}"/>
<img src="https://latex.codecogs.com/svg.latex?\Large&space;\varepsilon_{\theta}=\frac{\delta_v}{\delta_\theta}*\frac{1}{r}+\frac{u}{r} "/>
<img src="https://latex.codecogs.com/svg.latex?\Large&space;\varepsilon_{z}=\frac{\delta_w}{\delta_z}"/>

Las deformaciones angulares son:

<img src="https://latex.codecogs.com/svg.latex?\Large&space;\gamma_{r\theta}=\frac{\delta_v}{\delta_r}+\frac{\delta_u}{\delta_r}*\frac{1}{r}"/>
<img src="https://latex.codecogs.com/svg.latex?\Large&space;\gamma_{z\theta}=\frac{\delta_w}{\delta_\theta}*\frac{1}{r}+\frac{\delta_v}{\delta_z}"/>
<img src="https://latex.codecogs.com/svg.latex?\Large&space;\gamma_{zr}=\frac{\delta_u}{\delta_z}+\frac{\delta_w}{\delta_r}"/>

Finalmente, las deformaciones de un cilindro debido a la torsión se pueden cuantificar según el radio de curvatura del material y del ángulo de torsión. Esta deformación se calcula como:

<img src="https://latex.codecogs.com/svg.latex?\Large&space;\gamma=\frac{\rho*\phi}{L}"/>

Con L el largo del cilindro, phi el ángulo de torsión y rho el radio de curvatura.

### Ejemplo aplicado

Este es un ejemplo sencillo y genérico para cuantificar la deformación debido a un ángulo de torsión consideremos el siguiente cilindro que tiene un momento de inercia polar I, módulo de elasticidad E, largo del cilindro L, y módulo de torsión G.

![ejemplo.png](https://drive.google.com/uc?export=view&id=1AHmtK2HX2bKflE8kE1LUrbX8Av49VGB7)

Este momento se cuantifica como:

<img src="https://latex.codecogs.com/svg.latex?\Large&space;M=G*I*\frac{\delta_\theta}{\delta_z}"/>

Luego la deformación viene dada por:

<img src="https://latex.codecogs.com/svg.latex?\Large&space;\gamma=r*\frac{\delta_\theta}{\delta_z}"/>

<img src="https://latex.codecogs.com/svg.latex?\Large&space;\gamma=\frac{r*M}{G*I}"/>

Con r el radio del cilindro dibujado anteriormente.

AUTORA: Gisselle Poblete Ramos





