PRODUCT BACKLOCK 

Vamos a realizar una calculadora, que ser� nuestro producto final.
Para ello, empezaremos dividi�ndolo en tres historias de usuario. As� tendremos:
1� Sumar
2�Multiplicar
3�Restar

Cada una de estas historias estar� compuesta por tres tareas, que son:
	-Dise�o de las pruebas.
	-Prueba.
	-C�digo. (El que no de fallo)

El cuarto punto en el que el usuario nos ha pedido que quiere saber cuando no se puede realizar una resta no lo hemos considerado como una historia de usuario m�s sino que est� incluido en la dentro de la tarea de prueba. 

Usamos TDD en el proyecto y realizaremos pruebas antes de refactorizar el c�digo y cuando ya est�n hechas todas las tareas de cada una de las tres historias se proceder� a realizar una prueba de integraci�n entre las mismas.  

En el proyecto hemos considerado que la suma es bloqueante para poder realizar la multiplicaci�n, pues la funcionalidad multiplicaci�n se basa en la suma, y sino funciona la suma la multiplicacion tampoco lo har�. Con la resta no ocurre esto pues se considera que se puede hacer en paralelo a las otras dos historias.  

Spring.
Hemos considerado para nuestro primer spring tres historias:
-Suma
-Multiplicaci�n
-Resta

Nuestro primer spring lo hemos estimado en 2 semanas.  


