                         Laboratorio No. 2 Analisis de nodos
                               INFORMACIÓN GENERAL:
              DEPARTAMENTO: Eléctrica, Electrónica y Telecomunicaciones-DEEL
                      ÁREA DE CONOCIMIENTO: Sistemas Eléctricos-SEL
                   CARRERA: Ingeniería Electrónica y Automatización
     • NIVEL: Segundo
     • PERIODO ACADÉMICO: SII 202250
     • INTEGRANTES:
                   - CAMAYO PEREZ ARLEY DAVID
                   - FUENTES SALAS AARON DAVID
                   - MAILA LLUMIQUINGA DAVID ALCIDES
                   
     • DOCENTE: DARWIN OMAR ALULEMA FLORES
     • CORREO ELECTRÓNICO INSTITUCIONAL DEL DOCENTE: doalulema@espe.edu.ec
     
 OBJETIVO GENERAL

 • Emplear analisis de nodos a nuestro circuito fisico y simulado para encontrar los valores de sus corrientes y voltajes
   identificando cuales son los nodos principales.

OBJETIVO ESPECIFICO

 • Aplicar las herramientas y practica que hemos obtenido con el uso de simuladores de circuitos en la realizacion de un circuito fisico donde podamos evidenciar como      se cumplen las leyes que se han estado estudiando.
 
 • Aprender el uso fisico del multimetro, como medir voltajes, corrientes y resistencias y como identificar posibles problemas que se puedan presentar en nustro            circuito.
 
 MARCO TEORICO
 
Analisis de nodos
 
En el análisis de nodos se define en la aplicación de KCL a cada nodo del circuito
para encontrar al final todos los voltajes de nodo del circuito. Para que el sistema
de ecuaciones sea consistente debemos tener una ecuación por cada nodo. Así el
número de incógnitas es igual al número de ecuaciones.
De acuerdo al tipo de circuito y la forma en que se seleccione el nodo de referencia
se pueden tener distintas posibilidades de conexión de las fuentes:

• Fuentes de corriente independientes

• Fuentes de corriente controladas

• Fuentes de voltaje independientes a tierra

• Fuentes de voltaje independientes flotantes

• Fuentes de voltaje controladas a tierra

• Fuentes de voltaje controladas flotantes 

![image](https://user-images.githubusercontent.com/105386939/172763703-07757aa2-ec6a-4c6b-968c-5ca008e97e96.png)
Ley del voltaje de Kirchhoff

La ley del voltaje de Kirchhoff establece que la suma de todas las diferencias de potencial eléctrico alrededor de un circuito es cero. También a veces se le llama ley de lazos de Kirchhoff o segunda ley de Kirchhoff. Esto significa que en un lazo, la energía suministrada por la batería la utilizan todos los demás componentes, ya que no puede entrar o salir energía de un circuito cerrado. La ley es una aplicación de la conservación de la energía en términos de la diferencia de potencial eléctrico, \Delta VΔVdelta, V.

NODO

En un circuito eléctrico, un nodo es un punto donde se cruzan dos o más elementos de circuitos, sea una fuente de voltaje o corriente, resistencias, capacitores, inductores, etc.
![image](https://user-images.githubusercontent.com/105386939/172764495-c7b282bf-8fe7-4e1c-a177-1d2df830b6c4.png)

RESOLUCION

Siempre que se trabaja con la Ley de las Corrientes de Kirchhoff aparece un sistema de ecuaciones lineales. Luego de establecidas las ecuaciones, se procede a resolver el mismo. Se puede usar cualquier método (reducción, sustitución, determinantes, etc).

![image](https://user-images.githubusercontent.com/105386939/172764860-1a7d0bb9-fa30-44a8-b1e0-8f8ca1715a4d.png)

![image](https://user-images.githubusercontent.com/105386939/172764822-fc86181c-a510-4619-8733-6460d1dba57e.png)

Nodo de referencia 
Durante el análisis de un circuito se escoge uno de los nodos en el circuito para que sea el nodo de referencia, mediremos el volatje en los otros nodos se mide en relación al nodo de referencia. Cualquier nodo puede ser el de referencia, pero dos opciones comunes que simplifican el análisis de circuitos son:
la terminal negativa de la fuente de voltaje o de corriente que alimenta al circuito, o
el nodo conectado al mayor número de ramas.

Tierra 

El nodo de referencia suele referirse como la tierra. El concepto de tierra tiene tres significados importantes.

![image](https://user-images.githubusercontent.com/105386939/172767233-6f9087a1-9fba-4910-8178-116cce01a3bf.png)

Los pasos en el método del voltaje en los nodos

1) Asignar un nodo de referencia (tierra).
2) Asignar nombres a los voltajes en los nodos restantes.
3) Resolver los nodos fáciles primero, los que tienen una fuente de voltaje conectada al nodo de referencia.
4) Escribir la ley de Kirchhoff de la corriente para cada nodo. Haz la ley de Ohm en tu cabeza.
5) Resolver el sistema de ecuaciones resultante para todos los voltajes en los nodos.
6) Resolver para cualquier corriente que quieras conocer mediante el uso de la ley de Ohm.

EXPLICACION DEL PROCEDIMIENTO

![image](https://user-images.githubusercontent.com/105386939/172768676-fb5d7f5f-91f7-450c-917b-d8e5730a0772.png)

![image](https://user-images.githubusercontent.com/105386939/172841813-305e92f9-f18e-4997-af1c-03215036d704.png)


• A continuacion se hicieron los calculos de los voltajes que se dan en los nodos principales A y B, utlizando leyes de volatje de Kirchoff y resolviendo el sistema de ecuaciones obtenemos estos valores

![image](https://user-images.githubusercontent.com/105386939/172768734-b2fa5abd-04cd-4232-8c00-80ac6842acea.png)

![image](https://user-images.githubusercontent.com/105386939/172768830-e45e8fab-133e-422b-a7f5-23302cee5d6d.png)

• Utilizando los voltajes y resistencias ideales obtuvimos los valores del simulador Tinkercad, en los circuitos fisicos obtuvimos diferente valores aproximados al ideal.

![image](https://user-images.githubusercontent.com/105386939/172769113-99542d48-8c49-4dd9-81ea-d0a2240f897e.png)

![image](https://user-images.githubusercontent.com/105386939/172770366-ce9f50a3-bf56-4538-b49c-1b0a90a3be9f.png)


![girada](https://user-images.githubusercontent.com/105386939/172770396-01edc8e7-ef42-4f75-a205-8cca0bad39ce.jpeg)

![girada2](https://user-images.githubusercontent.com/105386939/172770399-2d966157-0a8b-46f4-b64f-7fb8e2285638.jpeg)

CALCULO DE ERROR

![image](https://user-images.githubusercontent.com/105386939/172842027-f4a099a9-0c52-4107-818f-486cf323ede3.png)


VIDEO

https://youtu.be/yI0l5F0HV9Q

CONCLUSIONES

• Analizando los valores que se obtuvieron en el simulador con la ayuda del programa Tinkercad podemos ver y comparar nuestro resultados, estos valores no coinciden pero se aproximan, esto se debe a que siempre va a existir cierto porcentaje de error causado por: diferentes valores en la resistencias, los voltajes, y ciertas perdidas de precision que pueden ser causadas por el multimetro, pero se pudo observar que los voltajes en estos nodos A y B, no analizamos los valores de los nodos de las esquinas de las fuentes de voltaje ya que estos nodos reciben una corriente directa sin impedimentos por lo que es igual al voltaje de la fuente.


BIBLIOGRAFIAS

Alexander, C. 2006. Fundamentos de Circuitos Eléctricos. 3ra. Edición. Mc Graw Hill. Boylestad, R. 2011. Introducción al Análisis de Circuitos.2da. Edición. Pearson. Floyd, T. L., Salas, R. N., González, L. M. O., & López, G. P. (2007). Principios de circuitos eléctricos. Pearson Educación.

RUBRICA

![image](https://user-images.githubusercontent.com/105386939/172766291-7593f019-64c2-4b05-b8bd-e40b15081688.png)






