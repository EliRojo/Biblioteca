# Biblioteca
Debido a su increíble desempeño como desarrolladora aprendiz en su primera asignación,
la universidad importante para la cual se está desarrollando el sistema bibliotecario, le ha
pedido a la empresa “ADA Software Technology”, que la incluya a Ud como apoyo en el
desarrollo del sistema gestor de préstamos de libros de la biblioteca. Entonces, su líder
técnico de desarrollo del equipo de “ADA Software Technology”, le ha asignado las
siguientes funcionalidades a desarrollar :
1. Registrar un libro de la biblioteca: deberá seleccionar una colección que le
permita almacenar los libros en el sistema bibliotecario, teniendo en cuenta lo
siguiente:
a. El libro en el sistema bibliotecario está compuesta por:
■ Título
■ Autor
■ Año de publicación
■ Código en la biblioteca
b. Para el proceso de etiquetado (definición del código) de los libros, será
importante mantener el orden en el que se van registrando en la biblioteca.
2. Etiquetar libros: se deberá implementar la lógica que permita recorrer la colección
de libros de la biblioteca, verificar por cada libro si ya fue etiquetado (si su código no
está nulo) y en caso de que no, poner la etiqueta (definir un valor para el campo
código) correspondiente al libro. La etiqueta se generará de la siguiente manera:
Título/Año de publicación/Consecutivo de la biblioteca
Ejm: Harry Potter y la piedra filosofal/2001/123

El consecutivo de la biblioteca, será un número único para toda la biblioteca,
que irá incrementando su valor en 1 cada vez que se registre un nuevo libro
en la biblioteca.
3. Buscar una libro: dado el título, tendrá que implementar la lógica que busque en la
colección de libros de la biblioteca, el o los libros que coincidan con el parámetro de
búsqueda y los retorne en una lista. En caso de no encontrarse el libro, la lista a
retornar, estará vacía.
4. Imprimir los libros de la biblioteca: tendrá que implementar la lógica que permita
imprimir todos los libros registrados en la biblioteca, imprimiéndolos en el siguiente
formato:

Título / Autor / Año de publicación / Código en la biblioteca

Para lo anterior deberá:
● Realizar el diagrama de clases que le permita implementar su asignación.
● Seleccionar el tipo de colección (de las vistas en clase), que convenga mejor de
acuerdo con la lógica que le están solicitando.
● Crear un nuevo proyecto llamado “Biblioteca”.
● Definir los paquetes que debería tener el proyecto y en cuál paquete deberá ir cada
una de las clases definidas en su diagrama de clases.

● A través de un método main, ejecutar pruebas para cada una de las funcionalidades
implementadas.
