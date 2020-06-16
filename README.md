UNIVERSIDAD DE LAS FUERZAS ARMADAS ESPE

![](https://github.com/BraddJCJ/Informe3_Jerez_Sangoquiza_Zambrano/blob/master/img/Logo_ESPE.png)

¨Práctica de Laboratorio N°3 Análisis de nodos¨  
¨Fundamentos de Circuitos Eléctricos¨  
Integrantes: Jerez Bradd; Sangoquiza Andrés; Flores de Valgas Jonathan.  
NRC: 8702   
Fecha: 2020 - 06 - 17  

1.- PLANTEAMIENTO DEL PROBLEMA

¿Cuáles son los voltajes respectivos en cada nodo del circuito? ¿La leyes de corriente de kirchhoff nos permitirán analizar debidamente el circuito? ¿Qué características presenta un análisis nodal en un circuito electrónico?¿Cuál será el porcentaje de error en el voltaje que se presentará entre los datos simulados y analizados?

2.- OBJETIVOS.

Generales:

- Comprobar experimentalmente el análisis de nodos midiendo los voltajes en cada uno de ellos.

Específicos:

- Implementar el circuito en la plataforma virtual TINKERCAD.
- Realizar las debidas mediciones de voltaje mediante el multímetro virtual que nos brinda la plataforma.
- Comparar los valores teóricos obtenidos anteriormente mediante cálculos, con los valores obtenidos experimentalmente en el simulador y así comprobar la veracidad del análisis de nodos.

3.- MARCO TEORICO

ANALISIS DE NODOS EN UN CIRCUITO ELECTRONICO

En el análisis por nodos se parte de la aplicación de KCL a cada nodo del circuito para encontrar al final todos los voltajes de nodo del circuito. Para que el sistema de ecuaciones sea consistente debe haber una ecuación por cada nodo. Así el número de incógnitas (voltajes de nodo) es igual al número de ecuaciones (una por nodo). De acuerdo al tipo de circuito y la forma en que se seleccione el nodo de referencia se pueden tener distintas posibilidades de conexión de las fuentes:

• Fuentes de corriente independientes.

• Fuentes de corriente controladas.

• Fuentes de voltaje independientes a tierra.

• Fuentes de voltaje independientes flotantes.

• Fuentes de voltaje controladas a tierra.

• Fuentes de voltaje controladas flotantes .

El método que llamaremos general aplica a los casos de circuitos con fuentes de corriente independientes y fuentes de voltaje independientes a tierra. Este metodo no aplica a los circuitos que tienen:

Fuentes flotantes de voltaje (Se usa el método de súper nodos)
Fuentes dependientes de corriente o voltaje ( Se deben escribir las eccuaciones de dependencia de la variable controlada y controladora).
Sie el circuito solo tiene fuentes de corriente independientes entonces se aplica el metodo de nodos.

![](https://github.com/BraddJCJ/Informe3_Jerez_Sangoquiza_Zambrano/blob/master/img/250px-KCL_-_Kirchhoff's_circuit_laws.svg.png)
![](https://github.com/BraddJCJ/Informe3_Jerez_Sangoquiza_Zambrano/blob/master/img/Primera.jpg)

4.- DIAGRAMAS

 ![](https://github.com/BraddJCJ/Informe3_Jerez_Sangoquiza_Zambrano/blob/master/img/Diagrama_1.PNG)

 ![](https://github.com/BraddJCJ/Informe3_Jerez_Sangoquiza_Zambrano/blob/master/img/Diagrama_2.PNG)


5.- LISTA DE COMPONENTES 

* 1 Resistor  R1  1.8 Kohm
* 1 Resistor  R2  2.2 kohm 
* 1 Resistor  R3  470 ohm
* 1 Resistor  R4  1.5 Kohm 
* 1 Resistor  R5  3.9 kohm
* 2 Fuentes de voltaje  V1 y V2 12v y 8v.
* n Multimetros

 DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN:
 
 Para una mejor apreciación sobre el circuito, se realizó adicionalmente el análisis a través de la aplicación de Proteus, de modo que se visualice con precisión el análisis de nodos, además de sus valores.

 ANEXOS:
 
 Cálculo Analítico:
 ![](https://github.com/BraddJCJ/Informe3_Jerez_Sangoquiza_Zambrano/blob/master/img/Anexo1.jfif)
 
 Análisis de errores:
 ![](https://github.com/BraddJCJ/Informe3_Jerez_Sangoquiza_Zambrano/blob/master/img/Anexo2.jfif)
 
 Análisis en Proteus:
 ![](https://github.com/BraddJCJ/Informe3_Jerez_Sangoquiza_Zambrano/blob/master/img/Anexo3.png)
