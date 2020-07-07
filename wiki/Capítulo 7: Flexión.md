# Flexión
Es un tipo de deformación que presenta un elemento estructural alargado en una dirección perpendicular a su eje longitudinal, se dice "alargado" ya que una de sus dimensiones es dominante frente a las otras.
![título](https://github.com/SebastianRodriguezValdes/icm2028-wiki/blob/master/wiki/images/viga%20en%20flexi%C3%B3n.png)

La característica principal de un objeto sometido a flexión es que presenta una superficie de elementos llamado eje neutro tal que la distancia a lo largo de cualquier curva contenida en ella no varía con respecto al valor antes de la deformación. El esfuerzo que provoca la flexión se denomina momento flector.

**Flexión pura**

Cuando una viga está sometida a dos momentos de la misma magnitud y sentidos opuestos, estará sometido a flexión pura.

**Deformaciones en flexión**

Debido a la flexión la viga se curvará, pero permanecerá simétrica después de la flexión, convirtiéndose en un arco circular, en el que las fibras superiores se acortan y las inferiores se alargan, entre estas fibras habrá unas que ni se estiran ni se encojen. Estas fibras estarán en un plano curvo y neutro, que se conoce como eje neutro.

![título](https://github.com/SebastianRodriguezValdes/icm2028-wiki/blob/master/wiki/images/eje%20neutro.png)


**Esfuerzos en flexión**

Designando con <img src="https://latex.codecogs.com/svg.latex?\rho"> el radio de curvatura de la viga, medido desde el centro hasta la superficie neutra, la longitud del eje neutro se puede escribir:

<img src="https://latex.codecogs.com/svg.latex?\L=\rho*\delta_\theta=\delta_x"> 

Otras fibras, que no están en el eje neutro sufrirán deformaciones y su nueva longitud será:

<img src="https://latex.codecogs.com/svg.latex?\L'=(\rho-y)*\delta_\theta"> 

Por lo que podemos escribir la siguiente relación:

<img src="https://latex.codecogs.com/svg.latex?\epsilon_x=\frac{\delta}{\L}=\frac{((\rho-y)*\delta_\theta)-\delta_x}{\delta_x}=\frac{-y}{\rho}">    

Además

<img src="https://latex.codecogs.com/svg.latex?\epsilon_x=\frac{-y}{\rho}=\frac{\sigma_x}{E}"> 

Por lo tanto, el esfuerzo es linealmente proporcional a la distancia de la fibra desde el eje neutro.

Debido a que no hay fuerzas axiales se puede escribir la siguiente ecuación de equilibrio:

<img src="https://latex.codecogs.com/svg.latex?\Sigma{F_x}=\int\sigma_xd_A=0"> 

Otra ecuación de equilibrio:

<img src="https://latex.codecogs.com/svg.latex?M=\int{y\sigma_xd_A}"> 

<img src="https://latex.codecogs.com/svg.latex?\sigma_x=-\frac{My}{I_z_z}"> 

**Ejemplo**

Hallar los esfuerzos en; a) el punto A, b) en el punto B

![título](https://github.com/SebastianRodriguezValdes/icm2028-wiki/blob/master/wiki/images/Captura%20de%20pantalla%20(265).png)

Primero tenemos que encontrar <img src="https://latex.codecogs.com/svg.latex?\bar{y}">

<img src="https://latex.codecogs.com/svg.latex?\bar{y}=\frac{120_m_m}{2}=60*10^-3_m">

<img src="https://latex.codecogs.com/svg.latex?I=\frac{1}{12}(80)(120)^3-\frac{1}{12}(40)(80)^3=9,8133*10^{-6}m^4">

Obteniendo para A:

<img src="https://latex.codecogs.com/svg.latex?\sigma_x=-\frac{My}{I}=\frac{-(15*10^3Nm)(40*10^{-3})}{9,8133*10^{-6}m^4}=-61,1413MPa">

Obteniendo para B:

<img src="https://latex.codecogs.com/svg.latex?\sigma_x=-\frac{My}{I}=\frac{(15*10^3Nm)(60*10^{-3})}{9,8133*10^{-6}m^4}=91,7122MPa">

**Referencias**

http://mecanicademateriales.wikidot.com/ejercicios-referente-a-flexion-pura

https://mecanica-usach.mine.nu/media/uploads/Apuntes_curso_RMA_clase_4.pdf
