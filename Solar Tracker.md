# SOLAR TRACKER

## ¿PROBLEMA Y ODS ELEGIDA?
Elegimos la ODS que está relacionada con la energía asequible y no contaminante.

¿Pero este proyecto como puede llegar a ser una posible solución de esta problemática?

### 1. Introducción
En este proyecto, el objetivo es dar solución a un problema cotidiano relacionado con las ODS. En la actualidad, se evidencian problemas bastante delicados y uno de los mas fuertes, es el cambio climatico y nuestro objetivo como ciudadanos de este mundo es tratar de encontrar una solución real y eficaz para mitigar las consecuencias de este brusco cambio, con esto se desarrollan diversas soluciones y una de las mas usadas por compañias y hogares en los ultimos años es el uso de paneles solares. A pesar de estar siendo implementado con gran fuerza y transcendecia, vemos que no es frecuente ver el uso de estos a manera personal y portatil. Aquí es donde entra en juego nuestro proyecto de energías sostenibles. 

### 2. Descripción de la ODS

La energía se está volviendo cada vez más sostenible y fácil de encontrar en muchos de los países del mundo. Los países pobres cada vez tienen más acceso a esta y la energía renovable esta dando muy buenos resultados en el sector eléctrico
Sin embargo, hay que mejorar este sistema en cuanto al acceso a tecnologías para más de 3000 millones de personas, y combustibles de cocina limpios y seguros; de esa manera expandir el uso de la energía renovable más allá del sector eléctrico 
Algunos datos para destacar son:
1. El 13% de la población mundial no tiene acceso a servicios modernos de electricidad
2. 3000 millones de personas dependen de la madera, el carbón o los deshechos de origen animal para cocinar y calentar comida
3. La energía es el factor que contribuye principalmente al cambio climático y representa alrededor del 60% de todas las emisiones mundiales de gases de efecto invernadero.
4. La contaminación del aire en locales cerrados debido al uso de combustibles para la energía doméstica causó 4,3 millones de muertes en 2012, 6 de cada 10 de estas fueron mujeres y niñas
5. En 2015, el 17,5% del consumo final de energía fue de energías renovables.

Dicho esto, podemos responder algunas preguntas:

#### ¿Cuál es el objetivo?

Garantizar el acceso a una energía asequible, fiable, sostenible y moderna para todos

#### ¿Por qué?

Porque nuestra vida diaria depende de servicios energéticos y un buen sistema energético cubre a todos los sectores: como empresas, como la medicina, como la educación, como la agricultura, como la infraestructura, como las comunicaciones y como la tecnología

#### ¿Cuántas personas viven sin electricidad? 

Aproximadamente 1200 millones de personas (una de cada cinco personas de la población mundial)


### 3. Descripción de la solución de la ODS

En cuanto a la solución que se presenta para la ODS, los países pueden acelerar la transición a un sistema energético asequible, fiable y sostenible invirtiendo en recursos renovables, dando prioridad a practicas de alto rendimiento energético y optando por tecnologías e infraestructura no contaminantes.

Las empresas pueden usar y desarrollar fuentes hidroeléctricas de electricidad y bioenergía, y comprometerse a satisfacer sus necesidades operacionales de electricidad con energía renovable.

Los empleadores pueden dar prioridad a las telecomunicaciones, e incentivar el transporte con menor consumo energético (como el transporte ferroviario) por encima del transporte aéreo o de carretera.

Los inversores pueden introducir nuevas tecnologías en el mercado

Las personas pueden ahorrar energía conectado los enchufes en una regleta y apagando cuando no se estén usando 

En cuanto al proyecto, incialmente decidimos crear el prototipo real y funcional de lo que es un seguidor solar para orientar un panel y así conseguir energia limpia y renovable sin necesidad de mover nuestras manos. Todo esto lo logramos gracias a la conexión de LDR's, una tarjeta Arduino, panel solar de 5V - 60mH, dos resistencia de 10k cada una y por ultimo, un servo motor. En primera instancia probamos la funcionalidad del servomotor siguiendo la luz. El panel no se encuentra conectado a ningun receptor de energia ya que es un prototipo y por tanto aún no almacena energía.  


### 4. Herramientras y materiales usados para el proyecto
- **Cautin y estaño** 

![image](https://user-images.githubusercontent.com/99029413/160122542-15d89dc6-af58-4303-9242-f99ffbd99e07.png)

- **Cables o jumpers**

![image](https://user-images.githubusercontent.com/99029413/160122681-52fe35b0-d072-430f-87eb-b05aa00d2806.png)

- **Panel solar (5V - 60mH)**

![image](https://user-images.githubusercontent.com/99029413/160122750-a3457588-9cf3-4cf0-9e91-77ee2d4aecad.png)

- **Servo-motor**

![image](https://user-images.githubusercontent.com/99029413/160122807-570d4660-8f34-4a93-afde-b3ca62a7e1b2.png)

- **Arduino Uno (R3)**

![image](https://user-images.githubusercontent.com/99029413/160122877-1e74faf0-9a4b-4592-9f6b-0d76a141ae32.png)

- **Resistencias 10k**

![image](https://user-images.githubusercontent.com/99029413/160122941-98a7f916-01f1-463b-b817-a473af5ac236.png)

- **Fotorresistencias (LDR)**

![image](https://user-images.githubusercontent.com/99029413/160123146-2b50d0f3-b879-4a31-808c-326f861eed5d.png)


### 5. Resultados
- Primer paso: hacer una conexión entre resistencias (directamente), cada resistencia  va conectada a cada LDR (cada uno de estos a cada extremos del panel) y a estas mismas les añadimos cable para soldarlas al arduino mas adelante

![image](https://user-images.githubusercontent.com/99029413/160124375-32030047-1340-41aa-8b99-c6c1221928c2.png)

- Segundo paso: hacer las conexiones al arduino, donde conectamos GND de servo motor a GND de tarjeta arduino, le signal pin del servo motor al -9 de la tarjeta, el de 5V del servo motor al de 5V de la tarjeta, Conectamos los dos cables que conectaban cada uno directo a las resistencias en los puertos A0 y A1 de la tarjeta y por ultimo conectamos el cable que salía de la unión de las dos resistencias (directamente) al GND donde conectamos el GND del servo motor. 

![image](https://user-images.githubusercontent.com/99029413/160125896-c090bf14-5c54-4a5a-9e13-a303e9284e72.png)

- Tercer paso: Crear la base, la cual nosotros hicimos con cartón y pegar en la pestaña sobresaliente el servo motor

![image](https://user-images.githubusercontent.com/99029413/160126077-8cf12e20-9ba0-49d4-b408-70d1b3e8818e.png)

- Cuarto paso: Pegar el panel al servo motor

![image](https://user-images.githubusercontent.com/99029413/160126275-d924fbbf-b478-445c-bf5c-cf9d22c5021d.png)

- Resultado final:



### 6. Conclusiones
