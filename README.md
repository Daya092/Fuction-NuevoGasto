# Fuction-NuevoGasto

Creamos una funcion llamada NuevoGasto con tres parametros de entrada 

![image](https://github.com/user-attachments/assets/957f09e8-ebc3-477e-9137-c6895d750498)

Aqui especificamos que la funcion nos devolvera un valos de tipo VARCHAR(20) 
Como vamos a hacer uso de la funcion CURRENT_DATE() debemos indicar que esta NOT DETERMINISTIC
ya que los argumentos que nos va a devolver pueden cambiar en cada ejecucion.

![image](https://github.com/user-attachments/assets/f0aa86ba-9152-4269-9b42-8f5a2b4ddf26)

Utilizamos INSERT INTO para ingresar los valores en cada campo de la tabla gastos y, seguido,
VALUES con los valores. El P_idpresupuesto nos indica a qué persona queremos asignar el nuevo
gasto, y la función CURRENT_DATE() se utiliza para que la fecha sea del día en el cual se está
ingresando el gasto. Finalmente, utilizamos return 'Exitoso' una vez que la inserción se haya 
realizado con éxito.

![image](https://github.com/user-attachments/assets/db5a18f8-ace8-4b08-b44b-d216bf0c9504) 


El propósito de la función NuevoGasto es lograr la inserción de un nuevo gasto en la tabla gastos de una forma
más automatizada y rápida, ingresando únicamente a quién va dirigido, el valor y el tipo de monto.






