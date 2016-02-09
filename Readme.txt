PRODUCT BACKLOCK 

Vamos a realizar una calculadora, que será nuestro producto final.
Para ello, empezaremos dividiéndolo en tres historias de usuario. Así tendremos:
1º Sumar
2ºMultiplicar
3ºRestar

Cada una de estas historias estará compuesta por tres tareas, que son:
	-Diseño de las pruebas.
	-Prueba.
	-Código. (El que no de fallo)

El cuarto punto en el que el usuario nos ha pedido que quiere saber cuando no se puede realizar una resta no lo hemos considerado como una historia de usuario más sino que está incluido en la dentro de la tarea de prueba. 

Usamos TDD en el proyecto y realizaremos pruebas antes de refactorizar el código y cuando ya estén hechas todas las tareas de cada una de las tres historias se procederá a realizar una prueba de integración entre las mismas.  

En el proyecto hemos considerado que la suma es bloqueante para poder realizar la multiplicación, pues la funcionalidad multiplicación se basa en la suma, y sino funciona la suma la multiplicacion tampoco lo hará. Con la resta no ocurre esto pues se considera que se puede hacer en paralelo a las otras dos historias.  

Spring.
Hemos considerado para nuestro primer spring tres historias:
-Suma
-Multiplicación
-Resta

Nuestro primer spring lo hemos estimado en 2 semanas.  


