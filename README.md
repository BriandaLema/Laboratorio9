# LABORATORIO # 09

TEMA: AMPLIFICADOR OPERACIONAL
## 1. OBJETIVOS

**1,1.- GENERAL** 

* Analizar experimentalmente el comportamiento de un amplificación operacional.

**1,2.-ESPECÍFICOS**

*  Analizar algunas aplicaciones básicas con el amplificador operacional.

* Verificar el principio de funcionamiento de un amplificador operacional.

* Familiarizarse con el uso de instrumentos de medida.


## 2. PLANTEAMIENTO DEL PROBLEMA

Este proyecto consistió en la implementación de un circuito eléctrico, en un programa online denominado Tinkercad con la finalidad de experimentar el comportamiento y la actuación de un amplificador operacional. Se crea el circuito utilizando resistencias y capacitores, conectadas a fuentes variables, fuentes directas y a un amplificador operacional, el cuál es el principal para este laboratorio como se menciono anteriormente.


## 3. MARCO TEÓRICO 

### **AMPLIFICADOR OPERACIONAL** 

Es un circuito integrado que permite crear una gran variedad de circuitos, es utilizado en diversas aplicaciones de la electrónica analógica y digital. Su principal función es amplificar el voltaje, el símbolo de circuitos del amplificador operacional es un triángulo como podemos observar en la siguiente figura: 


![](https://github.com/BriandaLema/Laboratorio9/blob/master/img/Amplificador%20operacional.jpg)

El amplificador operacional tiene dos entradas y una salida. Las entradas están marcadas con signo menos y más para especificar las entradas inversora y no inversora, respectivamente. 
Las fuentes de poder se usan para polarizar al amplificador operacional causando ciertas condiciones para que el amplificador operacional trabaje de forma correcta.

**DIAGRAMA DE UN AMPLIFICADOR OPERACIONAL**

![](https://github.com/BriandaLema/Laboratorio9/blob/master/img/Amplificador2.png)

El amplificador más común es el LM741, éste tiene 8 terminales de conexión y las cinco más importantes son:

1.	Terminal 2: entrada inversora.
2.	Terminal 3: La entrada no inversora.
3.	Terminal 6: Salida.
4.	Terminal 7: Suministro de potencia positivo V+.
5.	Terminal 4: Suministro de potencia negativo V-.

**TIPOS DE AMPLIFICADORES**

* AMPLIFICADOR OPERACIONAL IDEAL

Un amplificador operacional  ideal es aquel con ganancia infinita de lazo abierto, resistencia de entrada infinita y resistencia de salida cero.

* AMPLIFICADOR INVERSOR 

Un amplificador inversor invierte la polaridad de la señal de entrada mientras la amplifica.

* AMPLIFICADOR NO INVERSOR

Un amplificador no inversor es un circuito de amplificador operacional diseñado para suministrar una ganancia en tensión positiva.

* AMPLIFICADOR SUMADOR

Un amplificador sumador es un circuito del amplificador operacional que combina varias entradas y produce una salida que es la suma ponderada de las entradas.

* AMPLIFICADOR DE DIFERENCIA 

Un amplificador de diferencia es un dispositivo que amplifica la diferencia entre dos entradas pero rechaza toda señal común a las dos entradas.



## 4. DIAGRAMAS

Se simula el circuito con el amplificador operacional 741, con generador de señales y fuentes DC.

![](https://github.com/BriandaLema/Laboratorio9/blob/master/img/D1.png)


Se simula el circuito con el amplificador operacional 741, con generador de señales y fuentes DC.

![](https://github.com/BriandaLema/Laboratorio9/blob/master/img/D2.png)

Se simula el circuito con el amplificador operacional LM339, con generador de señales y fuentes DC.

![](https://github.com/BriandaLema/Laboratorio9/blob/master/img/D3.png)

Se simula el circuito en el programa Multisim con el amplificador operacional 741, con generador de señales y fuentes DC.

![](https://github.com/BriandaLema/Laboratorio9/blob/master/img/D4.png)

Se simula el circuito en el programa Multisim con el amplificador operacional 741, con generador de señales y fuentes DC.

![](https://github.com/BriandaLema/Laboratorio9/blob/master/img/D5.png)

Se simula el circuito en el programa Multisim con el amplificador operacional LM339, con generador de señales y fuentes DC.

![](https://github.com/BriandaLema/Laboratorio9/blob/master/img/D6png)


## 5. LISTA DE COMPONENTES

| CANTIDAD| ELEMENTO |
| ------- | -------------|
| 3       | Generador de señales  |
| 6       | Fuentes de voltaje DC  |
| 3       | Osciloscopio  |
| 3       | Protoboard  |
| 3       | Multímetro  |
|      45  | Cables conductores|
| 3 | Resistencia de 1kΩ |
| 1 | Resistencia de 4.3kΩ |
| 1 | Resistencia de 300Ω |
| 1 | Resistencia de 200Ω |
|    1    |  Capacitor de 1µF|
|   3  |Amplificadores operacionales|

## 6. MAPA DE VARIABLES 

Variables eléctricas: 

* Voltaje

* Corriente 

* Funciones dadas por el osciloscopio 

## 7. EXPLICACIÓN CÓDIGO DE FUENTE

Para este laboratorio utilizamos el simulador de Tinkercad , el cual es un sofware de diseño de circuitos, en este dispositivo encontramos una gama alta de componentes electrónicos que se utilizan para la creación de circuitos y simular su funcionamiento.
Tinkercad funciona directamente en un navegador web moderno por lo cual una conexión a internet es fundamental para la utilización de esta fuente. 
El mismo programa nos guía y asesora acerca de lo que realizamos, por lo cual la utilizacion de esta fuente es muy práctica si tienes un conocimiento básico sobre circuitos eléctricos.Una herramienta característica de Tinkercad es quemientras la simulación está en marcha podemos ir modificando las variables de cada elemento y ver los cambios en el momento. También podemos obtener una lista con los materiales empleado  que nos sirvio para realizar las fichas técnicas.



## 8. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

Fundamentalmente los prerrequisitos que requiere este laboratorio sería: un dispositivo tegnológico (sea un teléfono, una pc, un tableta, entre otras); pues trabajamos en un simulador online, nuestro segundo requisito es acceso a internet y finalmente tener conocimientos básicos sobre las leyes aplicadas, los componentes, elementos y variables que se utiliza para la creación y el siguiente análisis del circuito.

### **ANÁLISIS DE RESULTADOS**

**Analice y compare las formas de onda obtenidas en la práctica con los resultados obtenidos en el trabajo preparatorio. Comente dicha comparación.**

En el primer circuito podemos observar en las gráficas que el voltaje de salida es mucho mayor que el voltaje de entrada, la cual consiste en V3 + VR1, comparando con los demás circuitos se puede observar que si R en paralelo al amplificador es mayor a la resistencia del voltaje de entrada, esto es lo que causa que el voltaje de salida sea mayor.

En el segundo circuito 2, habiendo observado los sucesos del circuito 1, podemos concluir que el voltaje de salida del amplificador va a depender de la resistencia que está en paralelo a éste. Este es un caso especial en la cual esta resistencia es un capacitor, en este caso especial envez de aumentar el voltaje lo que sucede es que el voltaje de salida se convierte en una corriente directa.

Este tercer circuito es muy similar al primer circuito, sin embargo, en este caso se tiene dos voltajes de entrada, ambos con una corriente alterna iguales y dos resistencias distintas, con esto podemos realizar un análisis de nodos y se cumple lo mismo en el circuito 1, de que la resistencia en paralelo con el amplificador es mayor que la resistencia que contribuye voltaje.


### **PREGUNTAS**

**1.	Anote parámetros técnicos importantes de un amplificador operacional que deben ser tomados en cuenta al momento de utilizarlos en un proyecto.**

Pueden influir los siguientes parámetros:

*	Tensión de entrada diferencial:  Esta es la tensión máxima que puede aplicarse entre los terminales de entrada sin problemas de corriente.

*	Rango de Temperatura: Es el rango de temperatura en el cual el dispositivo funciona. 

* Tensión de alimentación: Tensión de alimentación máxima que puede aplicarse al amplificador.

**2. Investigue las características de amplificadores operacionales distintos a los utilizados en esta práctica.**

Otros de los amplificadores operacionales más comunes son: Amplificador de instrumentación INA125, OpAmp LM258, Op-Amp MC1741,  TL081 y TL084.

* Amplificador de instrumentación INA125

Este amplificador se alimenta con 12V, se lo utiliza para el manejo de una celda de carga. La ganancia del INA125 puede ser ajustada mediante un potenciómetro conectado a sus terminales. Toca tomar en cuenta que al cambiar la lontigud de las conexiones o alterar la fuente de alimentación puede desconfigurar la ganancia de este amplificador.
 
* OpAmp LM258

Este es un amplificador operacional dual con alta ganancia con compensación de frecuencia. 

* Op-Amp MC1741

Este amplificador operacional fue diseñado para utilizarse como amplificador sumador, integrador y en función del Componentes de retroalimentación.

* TL081

Este amplificador está diseñado con altas velocidades de rotación , baja polarización de entrada y las corrientes compensadas , y bajo coeficiente de temperatura.

* TL084

Este amplificador es de alta velocidad , tiene una entrada de alto voltaje, tiene transistores bipolares, cuenta con una alta velocidad de respuesta,tiene una frecuencia interna de compensación y cuenta con salida de protección contra cortos circuitos.

**3.	Investigue otras aplicaciones con circuitos más complejos que utilizan amplificadores operacionales.**

El amplificador operacional es un componente fundamental de la instrumentación electrónica moderna. Se utiliza extensamente en muchos dispositivos, junto con resistores y otros elementos pasivos. Entre las numerosas aplicaciones prácticas se encuentran amplificadores para instrumentos, convertidores digitales-analógicos, computadoras analógicas, cambiadores de nivel, filtros, circuitos de calibración, inversores, sumadores, integradores, diferenciadores, restadores, amplificadores logarítmicos, comparadores, elementos rotatorios, osciladores, rectificadores, reguladores, convertidores de tensión a corriente, convertidores de corriente a tensión y recortadores. 

## 9.APORTACIONES

Para complementar la correcta cuantificacion de valores calculados y valores medidos se baso en videos de la plataforma online YouTube, y se implemento el circuito en el simulador multisim para confirmar los valores.

## 10. CONCLUSIONES

Por medio de este laboratorio hemos comprobado de una forma tanto teórica como práctica la funcionalidad del amplificador operacional. 

 El uso de los amplificadores operacionales en todo sistema es fundamental, así que es importante conocer las configuraciones de las operaciones en los amplificadores. Toda configuración da una salida diferente, por ello es que como ingenieros aprendamos a conocer como pedirle a un amplificador operacional que cumpla con cierta demanda que nosotros requiramos del mismo.

Este complemento es de suma importancia, ya que es utilizado para elementos eléctricos. Ya sean computadoras, televisores, lavadoras, entre otras. Por que se emplean también en cada una de ellas para su diseño, las operaciones básicas lógicas. Y que sin ellas no tendríamos el avance tecnológico que tenemos hoy en día y que seguiremos disfrutando.



## 11. RECOMENDACIONES

Se debe tener en mente, de si se equivoca al traducir el circuito teorico al simulador esto podria causarle problemas en sus calculos, entonces recomendable siempre verificar los valores y cada una de los componentes segun el circuito prestado. 

Sugerimos que para este laboratorio se realice una previa investigación acerca de los amplificadores operacionales para conocer de manera clara sobre como se realiza la conexión y como actua el amplificador.

Finalmente se recomienda la correcta conexxión del osciloscopio para tener una buena gráfica de funcion y poder analizarla.


## 12. CRONOGRAMA

![](https://github.com/BriandaLema/Laboratorio9/blob/master/img/C9.png)

https://trello.com/c/bFvgoEnN/9-edici%C3%B3n-readme

## 13. BIBLIOGRAFÍA

* Alexander, C., & Sadiku, M. (2006). Fundamentos de Circuitos eléctricos. México: McGRAW-HILL/INTERAMERICANA EDITORES, S.A. DE C.V.

* Dorf, R., & Svoboda, J. (2006). Circuitos Eléctricos. México: ALFAOMEGA GRUPO EDITOR, S.A. DE C.V.

* Mecafenix, I. (19 de Abril de 2017). Ingeniería Mecafenix. Obtenido de https://www.ingmecafenix.com/electronica/amplificador-operacional/

* Torres, H. (21 de Diciembre de 2017). Hetpro. Obtenido de https://hetpro-store.com/TUTORIALES/amplificador-operacional/










