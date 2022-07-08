# Laboratorio-5_-Dilan-Porras_Yeshua-Chiliquinga_Steven-Loza

## MARCO TEÓRICO:

### ¿QUÉ ES THEVENIN?

Todo circuito lineal, o una parte de él, situado entre dos puntos A y B, puede sustituirse por un circuito equivalente, entre A y B, formado por un generador de tensión y una resistencia en serie con dicho generador.

![image](https://user-images.githubusercontent.com/104863870/177915032-e64b6e5b-ce25-489a-a3fd-da09b1696b5b.png)


### ¿Cómo calculo la resistencia de Thevenin?

La resistencia Thevenin es la resistencia equivalente del circuito vista desde los puntos A y B. Para obtener el valor de dicha resistencia procederemos de la siguiente manera:

+ Desconectaremos los generadores independientes que haya en el circuito. Si hubiese generadores dependientes el procedimiento sería el descrito en el vídeo que puedes ver al final de este artículo. Al desconectar los generadores, los sustituiremos por su circuito equivalente:
+ Si desconectamos un generador de tensión, su tensión será cero. Por lo tanto su circuito equivalente será un cortocircuito entre sus terminales.
+ Sin embargo, si desconectamos un generador de corriente, la intensidad será cero. El circuito equivalente del generador en este caso es un circuito abierto.

![image](https://user-images.githubusercontent.com/104863870/177915286-710bf955-55e5-4e98-95a4-ba96b31070d5.png)

+ Una vez desconectados los generadores, procederemos a calcular la resistencia equivalente entre los puntos A y B. Para ello, utilizaremos las técnicas de asociación de resistencias ya conocidas.

+ Finalmente, ya podremos sustituir el circuito original entre los puntos A y B por su circuito equivalente de Thevenin entre dichos puntos.
