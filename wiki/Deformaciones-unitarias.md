# Deformaciones unitarias

La deformación es el cambio de tamaño o forma que sufre un cuerpo tras ser sometido a tensiones o esfuerzos.

Esta deformación puede ser de varios tipos puede ser plana, elástica, plástica, uniforme o no uniforme. La deformación plana se produce cuando todas las partículas del cuerpo están en el mismo plano, por ende, el cuerpo solo sufre una deformación ese plano. La deformación plástica y elástica, tiene que ver con la capacidad del cuerpo para volver a su estado normal (tamaño y forma original), tras el cuerpo dejar de ser sometido a esfuerzos. Finalmente, la deformación uniforme y no uniforme está relacionado con la cantidad deformada de cada uno de los puntos del cuerpo. Si todos los puntos se deforman la misma cantidad, entonces es deformación uniforme y si no, entonces es no uniforme. 

Imaginemos un ejemplo simple, un cubo:


![cubo_deformado.png](https://drive.google.com/uc?export=view&id=12SRuO5oquZTcE7fx2aYwOPaGHJlybSbJ)

La primera imagen es del cubo en su tamaño original. El segundo es un cubo que sufrió una deformación uniforme (es más pequeño). El último es un cubo que sufrió una deformación en el eje x.

Luego de haber definido los tipos de deformaciones, podemos definir a la deformación unitaria como una deformación muy pequeña que experimenta un cuerpo continuo y delgado en un plano xy, el cual presenta esta deformación en este plano.


## Componentes deformación unitaria


Esta deformación unitaria, presenta 2 componentes, una componente normal, que es una medida de alargamiento o contracción de una línea o eje del cuerpo y una componente cortante que otorga una dimensión referente a la rotación de la deformación.

La componente normal se designa con el símbolo e y la componente cortante con el y.

La deformación unitaria entonces se define con estas dos componentes y considera el cambio diferencial en cada una de estas dos componentes sobre la unidad de medida del objeto. 

Finalmente, si sabemos que cada componente está dada por la variación en ese eje tenemos que:


<img src="https://render.githubusercontent.com/render/math?math=\epsilon_x = \frac{du}{dx}">
<img src="https://render.githubusercontent.com/render/math?math=\epsilon_y = \frac{dv}{dx}">
<img src="https://render.githubusercontent.com/render/math?math=\gamma_{xy} =\frac{dv}{dy}--\frac{dv}{dx}">

**No se logró colocar el símbolo +, por lo que se reemplazó con --

## Ejemplo aplicado

Consideremos el siguiente tubo:

![tubo_deformado.png](https://drive.google.com/uc?export=view&id=1CHK1cSvu-i48F_NVQvtW9eJbwAHb_j16)


Debido a que dijimos que son deformaciones muy pequeñas, definimos los vectores de desplazamiento v y u los cuales describen la deformación de un objeto con respecto al eje x e y.

Luego, consideremos que el punto inicial marcado con negro en el dibujo anterior, está en las coordenadas x, y. Entonces ambos vectores de desplazamiento serían v(x,y) y u(x,y).

Luego si consideramos la situación anterior donde el tuvo se desplazo solo en el eje y, entonces los vectores desplazamientos quedan como:

<img src="https://render.githubusercontent.com/render/math?math=v(x, y -- \delta y)">
<img src="https://render.githubusercontent.com/render/math?math=u(x,y)">

**No se logró colocar el símbolo +, por lo que se reemplazó con --


Esto considerando que el desplazamiento en y es de delta(y).


Es fácil ver, que al ser la deformación el cambio entre la variación de tamaño, en este caso de desplazamiento del eje, se deduce entonces que:


<img src="https://render.githubusercontent.com/render/math?math=\epsilon_x = 0">
<img src="https://render.githubusercontent.com/render/math?math=\epsilon_y = 0">
<img src="https://render.githubusercontent.com/render/math?math=\gamma_{xy} =\delta y">

AUTORA: Gisselle Poblete Ramos
