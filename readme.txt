Hoja de trabajo "M06_02_FT_03 - Programació estructurada"

	- El primer ejercicio es un ejercicio es un intento de calculadora. Se ha hecho haciendo una tabla, con filas y columnas. El objetivo
es mostrar la funcionalidad del if, switch y for each. Se recoge el primer número que teclea el usuario, se recoge el signo que teclea y se recoge el 
segundo número que teclea el usuario, con los if comprobamos si el usuario se ha dejado algo por teclear y con el switch mostramos el resultado dependiendo
del operador aritmético elegido. Con el for each mostramos todos los resultados guardados de las operaciones que ha ido haciendo el usuario.
También se ha añadido una pregunta al usuario al ejecutar el programa, dependiendo de su respuesta podrá probar la calculadora o no, esta pregunta la hemos
con un bucle do...while para que solo haya una respuesta válida.

	- El segundo ejercicio consta de 2 formularios, uno para registrarse y el segundo para iniciar sesión
· Se ha linkado bootstrap en el código html y se ha usado bootstrap para el diseño de las casillas de entrada de datos.
· Si dejas campos vacios te muestra mensajes de error, si al registrarte la contraseña no coincide con la repetición de la contraseña salta un error, 
  si todo esta correcto se guarda el usuario en un array, pero si el usuario y contraseña ya están registrados salta un mensaje de error. 
  Y si no estas registrado no puedes iniciar sesión, te salta un mensaje de error pero si estas registrado te da la bienvenida.
· Si todo está correcto antes de añadir los datos en el array se pide una confirmación al usuario con un window.confirm()
· NUEVO: Se muestran todos los datos de un usuario al iniciar sesion con un bucle for...in y también se muestra a todos los usuarios que 
se han registrado con un bucle for...of. 