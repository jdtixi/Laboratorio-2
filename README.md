![](https://pbs.twimg.com/profile_images/712307087577993217/D8_89Lg4_400x400.jpg)
##  LABORATORIO 2
                                                                            
                                                                            
                                                                            
                                                                            
                                                                            
                                                                            
                                                                           
                                                                           
       Janeth Katherine Oyasa Sepa, Juan Daniel Tixi Yupa
       DEPARTAMENTO DE ELECTRICA Y ELECTRONICA
       ESPE, Autopista General Rumiñahui S/N y Ambato, Sangolquí 171103.
       E-mail: jkoyasa@espe.edu.ec, jdtixi@espe.edu.ec
       Noviembre 2020 – Abril 2021
       Fundamentos de Circuitos Eléctricos
### 1.1 OBJETIVO DE LA PRÁCTICA
#### Objetivo General
Estudiar la teoria de analisis de un circuito electrico mediante el método de las mallas, indagar sobre el concepto de una malla en un circuito eléctrico y que cambia este método con respecto a los métodos ya estudiados, ademas de usar las leyes de Kirchhoff sobrel el voltaje y las corrientes y la ley de Ohm para asimilar de mejor manera el método para finalmente verificar el analisis de mallas y sus resultados obtenidos del calculo con los valores que obtendrémos en la simulacion del circuito.


#### Objetivos Específicos
 1. Definir cada uno de los concepotos a saber para el analisis de las mallas.
 2. Proceder de una manera correcta en el desarrollo de cada una de las mallas en el circuito.
 3. Realizar de una manera exitosa la simulacion del circuito usando todo lo aprendido hasta ahora.
 ### 1.2.	MARCO TEÓRICO

Entre las destrezas más importantes dentro del campo laboral de los ingenieros electrónicos se encuentra el estudio de circuitos eléctricos, que se define como la capacidad que tiene el individuo para manipular instrumentos mediante los cuales pueda comprobar datos teóricos obtenidos mediante técnicas teóricas que puedan realizarse de manera eficaz y rápida optimizando recursos en la localización de posibles causas para la operación defectuosa en aparatos electrónicos en los cuales no se puede visualizar el funcionamiento exteriormente tal como sucede en un aparato mecánico. 
A través, de este informe se planea representar una descripción resumida pero legible de como se obtienen los valores de tensión y corriente en circuitos usando el análisis de mallas. De igual manera se presenta la obtención da datos adquiridos mediante la experiencia desarrollando el laboratorio como lo es el uso del multímetro. Se mostrarán los resultados adquiridos mediante la experiencia para poder compararlos con los datos obtenidos realizando los cálculos respectivos de manera manual además se muestran explicaciones breves de su obtención. 
Los parámetros como intensidad, tensión y resistencia consecutivamente se encuentran presentes en los circuitos analizados para poder describir detalladamente la respuesta de cada uno de los elementos que están involucrados en el diseño estos circuitos, es necesario conocer métodos de análisis que permiten calcular valores teóricos en resistencias y fuentes de tensión. Estos métodos de análisis comprenden conceptos básicos en circuitos resistivos entre los que cabe mencionar algunas definiciones detalladas a continuación: 

####  1.2.1. DEFINICIONES BÁSICAS 

**1.2.1.1. Nodo**

En un circuito eléctrico, es muy usual que se generen nodos de corriente, podemos decir, que los nodos son puntos del circuito donde se unen tres o más ramas de un componente electrónico.  Se puede pensar al nodo como un “nudo” ya que dos o más componentes lo forman al permanecer soldados entre sí. 

![](https://ingelibreblog.files.wordpress.com/2014/02/nodo.jpg)
**1.2. Ramas**

Conexiones existentes entre los nodos del circuito. La rama puede constituirse como un elemento: capacitor, fuente, resistor, entre otros. Además, podemos decir que el número de ramas de un circuito es igual al número de elementos de este.

![](https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Nodes2.svg/450px-Nodes2.svg.png)

**1.2. Lazo**

Un lazo es cualquier trayectoria cerrada alrededor de un circuito. Para formar un lazo, debes comenzar en la terminal de algún componente y trazar un camino a través de elementos conectados hasta llegar nuevamente al punto de partida.

![](https://cdn.kastatic.org/ka-perseus-images/1e11477a94abdb9c8b8768f103cdb598fe9b5583.svg)

**1.2.1.4.  Malla**

Una malla es una clase restringida de lazo; una malla es un lazo que no contiene otros lazos. En el circuito de la ilustración 3, los lazos I y II son mallas porque no hay lazos pequeños dentro de ellas. El lazo punteado no es una malla, pues contiene dos lazos distintos.


![](https://electronicabasica.site/wp-content/uploads/2020/04/nodo-copia-2-1024x788.jpg)

**1.2.1.5. Red Plana **

Es una red que puede dibujarse sobre una superficie plana sin que se cruce ninguna rama. 

![](https://analisisdecircuitos1.files.wordpress.com/2014/08/screenshot2971.jpg)

### 1.2.2. ANÁLISIS DE MALLAS ELÉCTRICAS

El análisis de mallas eléctricas también se denomina método de malla de corriente o análisis de bucle. Como conocemos que las mallas eléctricas son bucles que no contienen ningún otro bucle dentro de él. La técnica de análisis de mallas eléctricas utiliza corrientes de malla como variables, en lugar de corrientes en los elementos para analizar el circuito. Por lo tanto, este método reduce considerablemente la cantidad de ecuaciones a resolver en el análisis.
Anteriormente explicamos la aplicación que el análisis de mallas eléctricas hace respecto a la Ley de Voltaje de Kirchhoff (KVL) mediante la cual se logra determinar las corrientes desconocidas en un circuito dado. De manera resumida después de encontrar las corrientes de malla usando KVL, los voltajes en cualquier parte de un circuito dado se pueden obtener mediante la ley de Ohm. 

 
 
 
 **1.2.2.1. Pasos para analizar la técnica** de análisis de mallas eléctricas
  
Veremos los pasos para el uso del método de mallas eléctricas: 

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/136666027_230034835229227_5243075648479605768_n.jpg?_nc_cat=101&ccb=2&_nc_sid=730e14&_nc_eui2=AeE1BGosPufW4CqTGsUV6ruvJanDRAToObMlqcNEBOg5s7rAWwH9oU9wnXtfBhKS2nSqHBXUdxk4YN4FB4SC1jYD&_nc_ohc=MEtNlUTP6QQAX9RSX5f&_nc_ht=scontent.fuio16-1.fna&oh=044341d5f9c46f73577ac90a41b47d33&oe=6023732E)


Para mejor comprensión aplicaremos el método de análisis de mallas al siguiente circuito.

Enunciado: Considerando el siguiente ejemplo en el que encontramos el voltaje a través de la fuente de corriente de 12 A utilizando el análisis de mallas eléctricas. En el circuito dado, todas las fuentes son fuentes de corriente.

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/137231390_230034825229228_483925131836302616_n.jpg?_nc_cat=100&ccb=2&_nc_sid=730e14&_nc_eui2=AeF_zwsVbyKQFPyQzl0K0jMyU6D2gSgxndZToPaBKDGd1hoUcVuekTmZeTr95_lxgDx1TWNvDRTNAnnjbFYOFEzm&_nc_ohc=xqaisD4gR2IAX-rM8bq&_nc_ht=scontent.fuio16-1.fna&oh=2f1b9f68d56eeaac0ab250ca97498202&oe=6020C6BF)

**Primer Paso**

En el circuito existe la posibilidad de cambiar la fuente de corriente a una fuente de voltaje en la fuente del lado derecho con resistencia paralela. La fuente de corriente se convierte en una fuente de voltaje colocando el mismo valor de resistencia en serie con una fuente de voltaje y el voltaje en esa fuente se determina de la siguiente manera:

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/135496657_230034801895897_2047418229869857378_n.jpg?_nc_cat=100&ccb=2&_nc_sid=730e14&_nc_eui2=AeGai64yyOh5r9FgIOtM9Cr1e1Gu66BUPJt7Ua7roFQ8m4HyItf-r3OsKpUWnSLPZ1Yx9MrqY70bMhL6A-oxAt-h&_nc_ohc=ZTYkJJBwki8AX83i3y5&_nc_ht=scontent.fuio16-1.fna&oh=afac513ef0a68ef4d3fd535c9e6ff14a&oe=60212196)

**Segundo Paso** 

Asignar las corrientes de rama como I1 e I2 a las ramas o bucles respectivos y represente la dirección de las corrientes como se muestra a continuación:

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/137614816_230034861895891_2073436129002265023_n.jpg?_nc_cat=108&ccb=2&_nc_sid=730e14&_nc_eui2=AeHBc0gNeldlnzYFPv0K90i1NrXAYI00Ynw2tcBgjTRifKPY8zGg0lYIw1zjcsf0SRKzmgHelF6Vw7JdQKYRrzcN&_nc_ohc=ya_FcK75aTkAX9kHNil&_nc_ht=scontent.fuio16-1.fna&oh=1b2dea545587f40bb9b3f8c9fb9a3823&oe=6020AC1B)

**Tercer Paso**

Aplicar el KVL a cada malla en el circuito dado:

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/136071849_230034898562554_7797385723723454312_n.jpg?_nc_cat=111&ccb=2&_nc_sid=730e14&_nc_eui2=AeGK_BxFLw1uTg4u-E2SRLDOSZ_DKMFSTtZJn8MowVJO1pY2hXZnfWfkU0uuVurbSSGCF-MFhPUSWBmuWTGBw3-_&_nc_ohc=IR2f6VGMJrcAX-fM90V&_nc_ht=scontent.fuio16-1.fna&oh=349511d3d680e5098a25ad0687d42761&oe=60237E56)

### 1.3.	LISTA DE COMPONENTES

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/138645860_230034911895886_7873966081647543056_n.jpg?_nc_cat=109&ccb=2&_nc_sid=730e14&_nc_eui2=AeH0LUMr9xbDn6LZInG2lhA-fsCNzfR0JG9-wI3N9HQkb8iBt-7_0m1u-XPs-7JMD5vNZ6pl69W4qL93Q1wzprqi&_nc_ohc=TezR-ZPkTlYAX-SMFtt&_nc_ht=scontent.fuio16-1.fna&oh=94db346968d58d0ea17f5594db51e55d&oe=6023A8C6)

**1.4.1.	Implemente el circuito que se presenta en la ilustración 12.**
![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/138284468_230041185228592_2160927471841425329_n.jpg?_nc_cat=106&ccb=2&_nc_sid=730e14&_nc_eui2=AeHZnMP-PPi-tiXgOZfCQrtjEAGrEPLRw4gQAasQ8tHDiM8TOmUdEZQrfG5wx_XCOWhgjs79h2BMmdFi_XgNQoka&_nc_ohc=onF_MbMa5AcAX-y0u2W&_nc_ht=scontent.fuio16-1.fna&oh=b2c39132cae8cc64470ab3a08fff630f&oe=60234E86)

1.4.2.	Mida cada una de las corrientes de malla y anote los resultados en la tabla 1.

1.4.3.	Simule en el software Multisim, Proteus, o cualquier otro simulador, el circuito de la ilustración 12, obteniendo los valores de las corrientes de malla. Anote los resultados en la tabla 




![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/137380372_229600201939357_2958495623791442393_o.jpg?_nc_cat=104&ccb=2&_nc_sid=730e14&_nc_eui2=AeHmwQdGA9xuTuAPXjzw8YWun3TiZFtrWyefdOJkW2tbJ1haSh1Ef5N-K4RUwSaSmtSkTI2o3LeV0DzPDklh7eCi&_nc_ohc=zDTGGFJvTHAAX9TMZMC&_nc_ht=scontent.fuio16-1.fna&oh=660f691b63260da932588cbd7ec27e2f&oe=6022E030)


![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/138031073_229600158606028_5299347414744327574_n.jpg?_nc_cat=109&ccb=2&_nc_sid=730e14&_nc_eui2=AeFA_lKjqfY3b-pVCPSEmSGzLVgNayhr3l0tWA1rKGveXd_u3fzITTH-rotMRX2-vIGTgqrRtqwaWHOCFv4W8fOs&_nc_ohc=QmwYt1vh1nsAX-URks_&_nc_ht=scontent.fuio16-1.fna&oh=24ebcbee270ff79518b84c0dc7b2c8d3&oe=60222A49)


### 6.1 Explicación
El circuito lelectrico biene dado por 7 ramas las cuales son dos fuentes de voltaje de una de 18 V y otra de 5 V, 5 resistores de 820 Omh, 1.2 k Omh, 1 k Ohm, 2.2 k Ohm, 390 Ohm.
Se procede a conectar el circuito de tal manera que el polo positivo de la fuente de 18 V quede conectada a un terminal del resistor de 820 Ohm, la otra terminal del resistor se lo conecta simultaneamente a una de las terminales de los resistores 1.2k y 1k Ohm, de la terminal sobrante de la resistencia 1.2k se lo conecta en forma de divisor de correinte con las resistencias 390 y 2.2K Ohm.
Finalmente la terminal 2 de la resistencia de 390 se la conecta con el polo positivo de la fuente de voltaje de 5 V y se unen todas las teminales de los resistores sin conectar con la polaridad negativa de las dos baterias.

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/138066265_229600205272690_5963622553284429031_o.jpg?_nc_cat=108&ccb=2&_nc_sid=730e14&_nc_eui2=AeFItfsuppmfeqoSQFIZpUFlU-UKLyInXwxT5QovIidfDBALwZjjPKcUZFthP4xAj0PLUbUhnpj7NMjHNMREetYZ&_nc_ohc=7bPMOFLQ30UAX9Epqky&_nc_ht=scontent.fuio16-1.fna&oh=8764d573a675b9a9476218fd2eaefc50&oe=601F91E8)

RESOLUCIÓN

Se establecen las direcciones de corriente en cada malla, en este caso tenemos tres mallas, por lo tanto serán tres corrientes:

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/137522891_230048855227825_33363562638929839_n.jpg?_nc_cat=102&ccb=2&_nc_sid=730e14&_nc_eui2=AeH8ilGEH2aPHcJf01Q3ovRI4sX2-lvyWyzixfb6W_JbLFvZLBDGyYlRc_tcVHj4f6PaVaKLu6mQxJY49M0MkP5K&_nc_ohc=UCHGFQXsphAAX91_tPv&_nc_ht=scontent.fuio16-1.fna&oh=f2b4fe9f698b8d93f3c6597a52b70bb8&oe=602177FB)

Sabemos que en cada resistor hay una caída de tensión, asi que teniendo en mente eso, se procede a la aplicacion de la LVK en cada una de las mallas, como son tres marllas tendremos tres ecuaciones y tres incognitas, como sigue:

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/136373959_230619741837403_8433119129257303966_n.jpg?_nc_cat=108&ccb=2&_nc_sid=730e14&_nc_eui2=AeEAhlit3HlBIZ5iMxBFtZ5S-94lNtvi1zH73iU22-LXMZ85f9QWVufDvZL0Fqw_4BYX22SUlHY5smVnew4Jg51g&_nc_ohc=KGckMmG3W3kAX9dzLl7&_nc_ht=scontent.fuio16-1.fna&oh=c9e066b6d9293bea9f3d49e031b677c8&oe=60226F50)

Con nuestros datos obtenidos de las corrientes principales hacemos el análisis para las corrientes que pasan por los dos resistores entre las mallas.
En este caso para la resistencia de 1k se tiene que la correinte es igual a 8.868 mA
Y para el resistor de 2.2k Ohm se tiene una corriente de 2.78 mA

Finalmente expresamos  los datos en nuestra tabla

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/136439523_230620028504041_2268522197934194545_n.jpg?_nc_cat=108&ccb=2&_nc_sid=730e14&_nc_eui2=AeG5ieGW--p4f8E1RY9i1juTHkqs4Y0_2uEeSqzhjT_a4avF_mCs315Ed1X5O8ueVXHInJhxmNrv1EwMcD5e-3AO&_nc_ohc=zhs-0eW3yw4AX-Gy5NV&_nc_ht=scontent.fuio16-1.fna&oh=2b359a973ff0b7218b08b82e4942de6d&oe=60247404)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/137318842_230620038504040_1901209243334034231_n.jpg?_nc_cat=107&ccb=2&_nc_sid=730e14&_nc_eui2=AeFjToiEhbuWvECzULiIAv9YcLs11w8H7B5wuzXXDwfsHpL8CMRmqApkFpLP4enDeHhJV9r70Ev6x_UdonsQHgEM&_nc_ohc=lg4_sbDpzTcAX8hioVr&_nc_ht=scontent.fuio16-1.fna&oh=714616bf98ffe6db47c4da88004ebbb5&oe=6024E2CC)

Circuito desarrollado en software

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/138690824_230500981849279_3944093760062498007_n.jpg?_nc_cat=102&ccb=2&_nc_sid=730e14&_nc_eui2=AeEboWpy7vSIHNJC2AUyWSrkcGg0NCjgJPxwaDQ0KOAk_Dlql-aFo0vxu6FfUb54rDZYGMcBXfWCHt53VZ0fp9d5&_nc_ohc=zu7UgV1lgIkAX95VNKr&_nc_ht=scontent.fuio16-1.fna&oh=41a6e8a899cb2812a663a00485f2034a&oe=60217EAF)

Imagenes de las medidas tomadas en el simulador

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/137691605_229600178606026_7316919259038871256_o.jpg?_nc_cat=106&ccb=2&_nc_sid=730e14&_nc_eui2=AeE8GFaQtfEMXaxNlWdCYY-5AmfczcwwdI0CZ9zNzDB0jeR18cVMk1Wj7Nw3wUev-JvBcRSm3xvSxexfd_IYuv_z&_nc_ohc=HmD-rRbOIvEAX-mJNbb&_nc_ht=scontent.fuio16-1.fna&oh=744addaf96f16779c3484ffe96c15ef0&oe=60221AF2)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/137197956_229600268606017_8561184410340220002_o.jpg?_nc_cat=102&ccb=2&_nc_sid=730e14&_nc_eui2=AeHScPW47_bdLZTCPHBZD-95vy10FDj9aLm_LXQUOP1ouea_TnmPP-jGnBUQH_qw5y0k8v2mNU9EttS6HMF60FRK&_nc_ohc=VqG2N2SnJFEAX_5E44D&_nc_ht=scontent.fuio16-1.fna&oh=2092ac0a1797edcd7261b32e5d296838&oe=60215B12)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/138024362_229600285272682_3142300964597832483_o.jpg?_nc_cat=104&ccb=2&_nc_sid=730e14&_nc_eui2=AeEytyYueIORvpRMbwKW6jRwj10F1qHxwZKPXQXWofHBkiBa1AONXlsX-W7v0-l1n5VMFnwQtEMSIMiG97STAuOf&_nc_ohc=VRko52htY-YAX-ZE6IK&_nc_ht=scontent.fuio16-1.fna&oh=506b1ec992125684e6bb8a735046eb01&oe=6021EFE4)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/138043433_229600291939348_7914293762986160689_n.jpg?_nc_cat=110&ccb=2&_nc_sid=730e14&_nc_eui2=AeG4Ldhp0ktrLdsyUgrVqFE5hmiLQXpG1K6GaItBekbUrh7h3wItf20Nk118JzzXys5vum3M0CKV6wXcb0daLJ0V&_nc_ohc=Fb47VW_gzkAAX8tQygp&_nc_ht=scontent.fuio16-1.fna&oh=56c1b6d02375a697a691fb2273d8044d&oe=60202D34)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/138197856_229600315272679_6052716038280249946_o.jpg?_nc_cat=103&ccb=2&_nc_sid=730e14&_nc_eui2=AeENACV-tfllEQ4tpdqRFfHU8jaWoFwfD_XyNpagXB8P9RTkXzhEAjhIZEfHMVYIbtghrDgWj2_iG60BNLE0kW_x&_nc_ohc=m-mD62zj5xYAX_GU7VL&_nc_ht=scontent.fuio16-1.fna&oh=38ef76b10d55455de84e8ddb7bba8c34&oe=60204D15)
### 10. Descripción de prerrequisitos y configuración
Como conocimientos previos a esta practica tenemos la ley de los voltajes de Kirchhoff en un lazo cerrado que es funadamental en el método de mallas, si no se aprende primero dicha ley la enseñanza del método de mallas será en vano. Además de la ley de voltajes, debemos tener muy en cuenta una de las leyes que son el pilar fundamental de la electronica que es la ley de Ohm.
Ya en el circuito para poder medir cada una de las corrientes que pasan por los elementos del circuito, se debe tener en cuanta la forma de medir corrientes, la que es en serie con el elemento del cual se requiere saber el dato de la correinte, y asimismo con el voltaje.

### 11. Concluciones
**Concluciones específicas**
Comprobamos que en una malla, que es una trayectoria cerrada que no contiene ramas en su interior se puede hallar las corrientes principales usando la Ley de Krichhoff.
Determinamos la gramimportancia que tienen los conceptos basicos de los circuitos la importancia de la ley de Ohm para la resolucion de problemas complicados.
**Conclución general**
En definitiva, ya con los resultados en la mano de nuestros calculos aplicando el metodo en cada una de las mallas del circuito, nos damos cuenta que la teoría se hace realidad, realidad visible y palpalable aunque siempre debemos tener en caunta que todos los conceptos se basan en la idea de que los elementos del circuito son ideales.

12.**Bibliografía**

Alexander, S. M. (2006). Fundamento de Circuitos Eléctricos (Vol. 3ra Edición). The McGraw-Hill Companies Inc.
EcuRed. (s.f.). Método de las corrientes de mallas. Método de las corrientes de mallas. Recuperado el 6 de Enero de 2021, de https://www.ecured.cu/M%C3%A9todo_de_las_corrientes_de_mallas

FP, E. (18 de Noviembre de 2017). Método de las mallas. Método de las mallas. Recuperado el 5 de Enero de 2021, de https://www.youtube.com/watch?v=uaG_GPQxKhg

García González, A. (26 de Julio de 2013). Ley de los voltajes de Kirchhoff: Método de Mallas. Ley de los voltajes de Kirchhoff: Método de Mallas. Recuperado el 7 de Enero de 2021, de http://panamahitek.com/ley-de-los-voltajes-de-kirchhoff-metodo-de-mallas/

Llanos, S. (14 de Agosto de 2015). Leyes de Kirchhoff. Leyes de Kirchhoff. Curso de Electricidad - Clase 14. Recuperado el 13 de Diciembre de 2020, de https://www.youtube.com/watch?v=Ni37_i656RI

McAllister, W. (2016). Método de la Corriente de malla: https://es.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-dc-circuit-analysis/a/ee-mesh-current-method 

