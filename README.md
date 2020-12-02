---

## Universidad de Costa Rica
### Escuela de Ingeniería Eléctrica
#### IE0405 - Modelos Probabilísticos de Señales y Sistemas


---

* Estudiante: **Daniel Quesada Valverde**
* Carné: **B65592**
* Grupo: **1**

---

En este laboratorio se procedió por calcular nuestro nuevo valor del tiempo de servicio, con base en el resultado obtenido de la fórmula a continuación para un valor del 10%. Es por este valor del 10%, que en la fórmula se coloca el 0.9, en el caso del exponente ponemos uno, ya que queremos saber el dato para el valor mínimo de clientes que están utilizando el servicio. Conforme a los datos planteados obtenemos que el nuevo valor del tiempo de servicio será 2.22.

Luego de obtener estos datos, se procedió a incorporarlos al código que se nos brindó.  En este solo fue necesario cambiar la ecuación que calcula el un, y ponerle nuestro nuevo valor del tiempo de servicio. Además de esto nuestro, P ahora será de uno en vez de P-1, ya que deseamos saber cuándo haya al menos una persona en el 90% del tiempo de servicio. Con la gráfica obtenida en el documento en L5.ipynb, podemos confirmar los datos obtenidos. Donde la línea verde es la que indica el límite en el por debajo de ella habrán menos de una persona en el sistema, que serían en el 10% de los casos. En cuando a la gráfica roja, esta nos indica la cantidad de personas en el sistema o servidor. Es importante resaltar, que como se están usando variables aleatorias los resultados de la gráfica irán variando conforme a cada simulación.

