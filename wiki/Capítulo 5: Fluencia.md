# Fluencia
Es la deformación irrecuperable, de la que se recuperará la parte de su deformación que corresponde a la deformación elástica, quedando una deformación irreversible. Este fenómeno ocurre sobre el límite elástico y se produce un alargamiento rápido sin que varíe la tensión aplicada.

**El esfuerzo de fluencia** corresponde al esfuerzo máximo que se puede desarrollar en un material sin causar una deformación plástica. Este esfuerzo es una aproximación práctica del límite elástico. El límite elástico convencional está determinado a partir de un diagrama esfuerzo-deformación el que se obtiene en un ensayo de tracción.

## Ensayo de tracción 
Consiste en someter una probeta normalizada realizada con el material a estudiar a un esfuerzo axial de tracción creciente hasta que se produce la rotura de la probeta.
Al cociente $$F/A$$ se lo denomina esfuerzo (stress), se denota con la letra $$\sigma$$. 
Al cociente $$\Delta L/L_0$$ se lo denomina deformación unitaria (strain), se denota con la letra $$\varepsilon$$ y es una magnitud adimensional. 

![gráfico](https://github.com/SebastianRodriguezValdes/icm2028-wiki/blob/master/wiki/images/gr%C3%A1fico%20de%20fluencia.jpg)
           *Diagrama esfuerzo-deformación*
           
           
1.	Al principio del estiramiento la deformación es proporcional al esfuerzo y se cumple la Ley de Hooke. Esto ocurre hasta que el esfuerzo aplicado alcanza un valor llamado límite de proporcionalidad ($$\sigma_p$$). Si el material es sometido hasta este valor de esfuerzo, al retirar el esfuerzo el material retomara su forma original sin deformaciones permanentes.

2.	Luego del límite de proporcionalidad, la gráfica se desvía de la recta y no existe una relación sencilla entre $$\sigma$$ y $$\varepsilon$$. Sin embargo, hasta el límite de fluencia, el objeto no sufrirá deformaciones mayores que la residual. La zona desde el origen hasta el límite de fluencia se denomina zona elástica.

3.	Si el objeto se somete a un esfuerzo más allá del límite de fluencia, entra en la zona plástica y no regresará a su longitud original al retirar la fuerza aplicada.

4.	Si el esfuerzo continúa incrementándose suficientemente se alcanza la ruptura. Entre el límite de fluencia y el punto de ruptura, existe una zona de fluencia, donde el material se deforma fácilmente, sin necesidad de aumentar el esfuerzo (región plana de la curva).
   
## Criterios de fluencia 
En clases estudiamos algunos criterios de fluencia que se utilizan para determinar los esfuerzos estáticos permisibles en estructuras o componentes de máquinas, tales como:

1.	**Criterio de Tresca**.

Que para tracción uniaxial tenemos que: 

$$Y=(\sigma_1-\sigma_3)$$


2.	Criterio de Von Mises

Que para tracción uniaxial tenemos que: 

$$\sqrt {2}*Y=\sqrt {(\sigma_1-\sigma_2)^2+(\sigma_1-\sigma_3)^2+(\sigma_2-\sigma_3)^2}$$

En ingeniería civil se utilizan diversos métodos, también denominados de fallo, consistentes en calcular qué cargas producen el fallo de la estructura, determinando la carga admisible mediante un coeficiente de seguridad.
Un ejemplo práctico del coeficiente de seguridad lo podemos ver en los ascensores.

**Ejemplo práctico**

![gráfico](https://github.com/SebastianRodriguezValdes/icm2028-wiki/blob/master/wiki/images/Ascensor%20fluencia.png)
*Representación de la situación descrita*

Supongamos que este ascensor tiene una carga máxima de 320 kg o 4 personas y que está diseñado con un factor de seguridad de 1,5.
En el caso de que suban 5 personas de 80 kg cada una, el ascensor estaría cargado con 400 kg. Pero el coeficiente de seguridad es 1,5, por lo que el ascensor aguantará esa carga, de hecho, aguantará 480 kg teóricamente. Pero si suben 6 personas de 80 kg, es decir, una carga total de 480 kg, en este caso en la practica no se puede afirmar que soportará la carga, ya que es posible que la máxima carga real sea menor a la máxima carga calculada, en cuyo caso fallará.
Es por esto que se aplica el coeficiente de seguridad sobre la carga máxima, la que se divide por el coeficiente obteniendo los 320 kg que son la carga de uso o diseño.








