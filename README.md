# Laboratorio-5_-Dilan-Porras_Yeshua-Chiliquinga_Steven-Loza

![image](https://user-images.githubusercontent.com/105320981/169589146-23574580-d5de-43cb-825d-f510a2e4c035.png)

UNIVERSIDAD DE LAS FUERZAS ARMADAS
ESPE


ASIGNATURA:

FUNDAMENTOS DE CIRCUITOS ELÉCTRICOS

INGENIERO:

 DARWIN ALULEMA

ESTUDIANTES:

DILAN PORRAS
STEVEN LOZA
YESHUA CHILIQUINGA

TEMA DEL LABORATORIO:

TEOREMA DE SUPERPOSICIÓN 

FECHA
8 de julio del 2022

## 1. OBJETIVOS:

#### 1.1 OBJETIVO GENERAL:

•	Analizar y desarrollar ejercicios de circuitos eléctricos aplicados a el teorema de Thevenin para la descomposición de sus características las cuales permiten a las personas calcular de mejor manera y mas simplificada la variable desconocida mediante el uso de información teórica.
#### 1.2 OBJETIVO ESPECIFICOS:

•	Describir y descubrir las caracteristicas del teorema de Thevenin orrespondientes para lo cual se hace uso de la información teóricas proporcionada mediante el uso de sitios web y videos tutoriales.

•	Analizar y calcular diferentes ejemplos de circuitos aplicando el teorema de Thevenin aprendido anteriormente en clases para lo cual se realizarán ejercicios experimentales para la comprobación mediante simuladores virtuales.
## 2 MARCO TEÓRICO:

### ¿QUÉ ES THEVENIN?

Todo circuito lineal, o una parte de él, situado entre dos puntos A y B, puede sustituirse por un circuito equivalente, entre A y B, formado por un generador de tensión y una resistencia en serie con dicho generador.

![image](https://user-images.githubusercontent.com/104863870/177915032-e64b6e5b-ce25-489a-a3fd-da09b1696b5b.png)


### ¿Cómo calculo la resistencia de Thevenin?

La resistencia Thevenin es la resistencia equivalente del circuito vista desde los puntos A y B. Para obtener el valor de dicha resistencia procederemos de la siguiente manera:

Desconectaremos los generadores independientes que haya en el circuito. Si hubiese generadores dependientes el procedimiento sería el descrito en el vídeo que puedes ver al final de este artículo. Al desconectar los generadores, los sustituiremos por su circuito equivalente:
+ Si desconectamos un generador de tensión, su tensión será cero. Por lo tanto su circuito equivalente será un cortocircuito entre sus terminales.
+ Sin embargo, si desconectamos un generador de corriente, la intensidad será cero. El circuito equivalente del generador en este caso es un circuito abierto.

![image](https://user-images.githubusercontent.com/104863870/177915286-710bf955-55e5-4e98-95a4-ba96b31070d5.png)

+ Una vez desconectados los generadores, procederemos a calcular la resistencia equivalente entre los puntos A y B. Para ello, utilizaremos las técnicas de asociación de resistencias ya conocidas.

+ Finalmente, ya podremos sustituir el circuito original entre los puntos A y B por su circuito equivalente de Thevenin entre dichos puntos.

3 PROCEDIMIENTO

3.3.1. Arme el circuito que se muestra en la figura 5.1.

![image](https://user-images.githubusercontent.com/104999420/177917179-58119ccf-1eec-4566-9aa1-2ffc1dd643c7.png)

Figura 3.1. Circuito para comprobar el Teorema de Thévenin.

3.3.2Circuito armado en tinkercad 

![image](https://user-images.githubusercontent.com/104999420/177917230-4271bd0a-42af-43c6-9621-05de0e6b8e8e.png)

Figura 3.2. Circuito con la medición de voltaje con sus fuentes de voltaje y su resistencia.

![image](https://user-images.githubusercontent.com/104999420/177917270-6c8a2677-a092-44d7-9249-db0e318d89d7.png)

Figura 3.3. Circuito con la medición de su corriente, con las fuentes de voltaje y sus resistencias.
 
![image](https://user-images.githubusercontent.com/104999420/177917296-e4cc96ee-2de0-40f7-86b9-401903e1c549.png)

Figura 3.4. Circuito con la medición del voltaje Thévenin sin la resistencia R3.

![image](https://user-images.githubusercontent.com/104999420/177917328-3ac7546b-d296-4181-beb2-e1185331c61f.png)

Figura 3.5. Circuito con la medición de la resistencia equivalente Thévenin sin la resistencia R5 y sin sus fuentes de voltaje.

![image](https://user-images.githubusercontent.com/104999420/177917362-1f56564f-b852-457d-99cb-8d7b3296f64f.png)

Figura 3.6. Circuito equivalente de Thévenin con la medición del voltaje en la resistencia R_5

![image](https://user-images.githubusercontent.com/104999420/177917392-5b97198c-1d50-45a5-816d-ba78c1fc406a.png)

Figura 3.7. Circuito equivalente de Thévenin con la medición de la corriente en la resistencia R_5

3.3.3. Mida el voltaje y la corriente en el resistor R5, anote los resultados en la tabla 3.2.

<img width="415" alt="image" src="https://user-images.githubusercontent.com/104999420/177917461-e21be08b-a2b0-434a-83d8-f866c0625b8e.png">

<img width="236" alt="image" src="https://user-images.githubusercontent.com/104999420/177917473-22d3c4ea-197f-418a-b650-478776521310.png">

<img width="195" alt="image" src="https://user-images.githubusercontent.com/104999420/177917490-85f7009a-73bd-4875-9316-0f49f96d7fd3.png">

3.3.4. Desconecte el resistor R5 y mida el voltaje en el circuito abierto. Anote el valor medido en la tabla 5.1.

<img width="396" alt="image" src="https://user-images.githubusercontent.com/104999420/177917559-ced0a9a9-eb67-4027-b6a3-7c1c604d2920.png">

<img width="210" alt="image" src="https://user-images.githubusercontent.com/104999420/177917631-9ab18e25-b181-44ed-9d5a-be3d40dd0deb.png">

<img width="384" alt="image" src="https://user-images.githubusercontent.com/104999420/177917662-91a282e3-3cc3-40be-b238-03a53274421d.png">

3.3.5. Anule el efecto de las fuentes de alimentación. Desconecte R5 y desde el circuito abierto resultante mida la resistencia equivalente. Anote el valor medido en la tabla 3.1.

<img width="374" alt="image" src="https://user-images.githubusercontent.com/104999420/177917797-1ce6ee8a-bae6-471d-85d1-54e3df48af9a.png">

<img width="330" alt="image" src="https://user-images.githubusercontent.com/104999420/177917821-a962581b-e53d-48b0-9655-7ae02908a5a0.png">

3.3.6. Implemente el circuito equivalente de Thévenin agregue el resistor R5 y mida la
corriente y el voltaje en el mismo, anote los resultados en la tabla 3.2. 

<img width="387" alt="image" src="https://user-images.githubusercontent.com/104999420/177917880-c461d53b-3cc8-414e-b8c4-27f164ea0c70.png">

<img width="200" alt="image" src="https://user-images.githubusercontent.com/104999420/177917897-b5dc952f-f879-4077-ad4c-960c918e6662.png">


Tabla 3.1. Valores del Circuito Equivalente de Thévenin

<img width="436" alt="image" src="https://user-images.githubusercontent.com/104999420/177917956-ce64029b-6005-4979-a051-2f09b5a0efa6.png">

Tabla 3.2. Comprobación del Teorema de Thévenin.

<img width="437" alt="image" src="https://user-images.githubusercontent.com/104999420/177917991-289abf06-d66f-4ca5-b591-509e88497b69.png">

3.1.4. Verifique el cumplimiento del Teorema de Thévenin y compare los resultados obtenidos prácticamente con los obtenidos analíticamente. Realice sus
conclusiones.

Después de haber aplicado el teorema de Thévenin en el circuito propuesto, pues se pudo comprobar que, si se cumple, ya que al comparar con los resultados obtenidos del simulador nos damos cuenta de que los valores no tienen una gran diferencia y es por eso que a continuación se ha realizado el cálculo de margen de error para saber cuánto es el porcentaje que estas varían.

Cálculo de error del voltaje de Thévenin 

<img width="439" alt="image" src="https://user-images.githubusercontent.com/104999420/177918088-46facb5f-34f1-48ad-ab2f-d7a6261719e1.png">

<img width="488" alt="image" src="https://user-images.githubusercontent.com/104999420/177918104-fe83cfe9-883a-4305-ae95-bbfeb7436980.png">

## 4. VIDEO:


## 5. CONCLUSIONES:

•	El teorema de Thevenin comprende una rama importante en la realizacion de ejercicios de fundamientos de circuitos lo cual se compone de caracteristicas aprendidas anterioremente es importante tomar en cuaenta cuando se tenga dudas de las resoluciones de ejercicios de circuitos paralelos.

•	La resolución de ejercicios aplicando el teorema de Thevenin es tambien tener en cuenta los metodos aprendidos aplicados en las leyes de kirchoff el teorema indica que debes separar por partes cada malla del circuito.

## 6. RECOMENDACIONES:

• Al momento de realizar los cálculos tener en cuenta el tipo de multímetro y en que parte del multímetro se desea hacer la consulta ya que si se hace mal uso de este se podría perder el multímetro las protoboards tratar de distribuir bien sus funciones y no poner todo en un solo lugar.

• En los cálculos tener muy en cuenta la formula del teorema de Thevenin ya que se desean los cálculos aplicando ese método tomar en cuenta la interrogante que nos pide encontrar y realizar cálculos preciosos, los componentes de experimento tener en cuenta y revisarlos antes de ponerlos en usa controlar el voltaje de entrada y realizar el trabajo con las indicaciones correspondientes.

## 7. BIBLIOGRAFÍA:

Floyd, T. L. (2007). Principios de Circuitos Electronicos. Mexico: Pearson educación.
















