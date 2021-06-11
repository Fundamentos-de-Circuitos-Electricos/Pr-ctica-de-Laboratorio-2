![image](https://user-images.githubusercontent.com/84390820/121572442-d0a57780-c9e9-11eb-8dd4-14f9354a6f6d.png)

# Práctica de Laboratorio 2

1. OBJETIVOS

General

* Detallar la tipología de los circuitos mediante técnicas analíticas de circuitos cerrados o mallas, en la cual se hace uso de Leyes de Kirchoff y Ley de Ohm, para expresar el comportamiento de la corriente que pasa por los elementos pasivos del circuito, además de calcular las caídas de voltajes que se producen dentro de una rama, malla o nodo en conexiones en paralelo, serie y mixta.  

Específicos

* Identificar nodos, ramas y mallas correctamente en los tipos de circuitos eléctricos.
* Interpretar y aplicar las Leyes de Kirchhoff en circuitos paralelos, en serie o mixtos.
* Calcular mediante leyes de Kirchhoff la intensidad y voltajes de los elementos de circuitos.

2. MARCO TEÓRICO

![image](https://user-images.githubusercontent.com/85137398/121629514-f4e07300-ca40-11eb-8f37-d9dc20317286.png)

3. EXPLICACIÓN DEL PROCEDIMIENTO

* Material y equipo requerido

![image](https://user-images.githubusercontent.com/85137398/121629786-8bad2f80-ca41-11eb-8c22-37f5822e950c.png)

* Descripcion de equipo y material

Protoboard: Un protoboard es una placa de pruebas en la que se pueden insertar componentes electrónicos y cables, donde se puede ensamblar un circuito sin la necesidad de soldar ningún componente. El protoboard tiene agujeros conectados entre sí, por medio de pequeñas láminas metálicas.

Resistores: Una resistencia o resistor al componente electrónico diseñado para introducir una resistencia eléctrica determinada entre dos puntos de un circuito eléctrico.

Fuente de voltaje: En electrónica, el elemento activo que puede transferir energía se llama fuente de voltaje.

Multímetro digital: Un multímetro digital es una herramienta que sirve para medir dos o más valores eléctricos, principalmente tensión (voltios), corriente (amperios) y resistencia (ohmios).

* Armado del circuito

Procedimiento

I. Escoger las fuentes de energia de 18v y 5v respectivamente.

![image](https://user-images.githubusercontent.com/85137398/121630400-afbd4080-ca42-11eb-9be2-7f3fa43c8902.png)

II. Escoger correctamente los resistores con su codificación de colores.

![image](https://user-images.githubusercontent.com/85137398/121630515-eabf7400-ca42-11eb-8084-eb3a272bf587.png)

III. Conectar el circuito en base al diagrama de conexión.

* Diagrama esquemático

![image](https://user-images.githubusercontent.com/85137398/121630611-12aed780-ca43-11eb-82db-47217e2cd336.png)

* Conexión del circuito

![image](https://user-images.githubusercontent.com/85137398/121630859-910b7980-ca43-11eb-9a13-c3c1e66a569c.png)

IV. Procedemos a medir la corriente de cada malla del circuito. Utilizamos como instrumento de medida un amperimetro.

A continuación calculamos los valores teóricos de corriente en las mallas del circuito, para completar la siguiente tabla:

Aplicamos la Ley de voltaje de Kirchhoff 

![image](https://user-images.githubusercontent.com/85137398/121634958-15adc600-ca4b-11eb-86c5-eeaf52a14517.png)

Planteamos la ecuación de la Malla I1

(0.82kΩ + 1kΩ)·I1 – I2 = 18

Planteamos la ecuación de la Malla I2

(1kΩ + 1.2kΩ + 2.2kΩ)·I2 – I1 - 2.2kΩ·I3 = 0

Planteamos la ecuación de la Malla I3

(2.2 kΩ + 0,39 kΩ)·I3 – 2.2 kΩ·I2 = -5

Simplificamos las ecuaciones

•	1.82kΩ·I1 – I2 = 18 (Ecuación 1)

•	4.4 kΩ·I2 – I1 – 2.2 kΩ·I3 = 0 (Ecuación 2)

•	2.59 kΩ·I3 – 2.2 kΩ·I2 = -5 (Ecuación 3)

Multiplicar la Ecuación 1 por (-2.2) y sumar con la Ecuación 3 y despejar I1:

I1 = (44.6 + 2.59·I1) / 4.004 (Ecuación 4)

Reemplazar Ecuación 4 en Ecuación 1 y despejar I2:

I2 = (9.1 + 4.71·I3) / 4004 (Ecuación 5)

Reemplazar Ecuación 4 y Ecuación 5 en Ecuación 2, despejar y sacar el valor de I3:

I3 = 0.49 mA. (Ecuación 6)

Reemplazar Ecuación 6 en Ecuación 3 y calcular el valor de I2:

I2 = 2.82 mA. (Ecuación 7)

Reemplazar Ecuación 7 en Ecuación 1 y calcular el valor de I1:

I1 = 11,44 mA.

Resolviendo el sistema de ecuaciones por método de reducción de Gauss Jordan, obtenemos como resultado:

I1 = 11,44 mA.

I2 = 2.82 mA. 

I3 = 0.49 mA.


4. RESPUESTAS A INTERROGANTES Y CÁLCULO DEL ERROR

Para calcular el porcentaje de error de las mediciones, se tiene en cuenta la siguiente fórmula:

![image](https://user-images.githubusercontent.com/85137398/121631171-2e66ad80-ca44-11eb-8e72-d3a386c3d334.png)

Con los que se obtiene los siguientes resultados:

5. VIDEO

6. CONCLUSIONES

•	Los valores de corriente de cada malla determinados por los cálculos haciendo uso la ley de Kirchhoff son muy aproximados a los valores simulados, obteniendo porcentajes de error menores al 1%.

•	Se demostró la Ley de voltaje de Kirchhoff en cada malla al manifestar que la suma algebraica de los voltajes en dicha malla es igual a 0 ya que con los valores obtenidos y al realizar la suma prácticamente nos dio como resultado 0.

•	Por medio de los cálculos matemáticos y del análisis crítico, se garantiza que se aplicó de manera correcta la ley de voltajes de Kirchhoff en el circuito eléctrico.


7. BIBLIOGRAFÍA

* Carak.K.(2019).Metodo de mallas - anáñisis de circuitos.10/06/2021.from https://dademuch.com/2019/11/05/metodo-de-mallas-analisis-de-circuitos/

* Ingeniería Mecafenix.(2018).Ley de voltaje de Kirchhoff.10/06/2021.from https://www.ingmecafenix.com/electronica/ley-de-voltaje-de-kirchhoff/





