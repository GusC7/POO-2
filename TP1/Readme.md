## Consigna:
Para los siguientes enunciados se solicita realizar su respectivo diagrama de Clases UML
### Sistema de Biblioteca
Se desea modelar un sistema simplificado para una biblioteca. La biblioteca tiene libros que pueden 
ser prestados a los usuarios registrados. Cada usuario puede prestar varios libros, pero un libro solo 
puede estar en posesión de un usuario a la vez. Si el libro no está prestado, está disponible para el 
próximo usuario.
Requisitos:
- Cada libro tiene un título, autor, número de páginas y un estado (prestado o disponible).
- Los usuarios se identifican por un ID único, un nombre y pueden tener varios libros 
prestados.
- La biblioteca debe conocer todos los libros que posee y a los usuarios registrados.
- Cuando un libro es prestado, el sistema debe registrar la fecha de préstamo y la fecha de 
devolución.
### Sistema de Gestión de Pedidos de Restaurante
Se desea desarrollar un sistema para gestionar los pedidos de un restaurante. El sistema debe 
permitir registrar los pedidos que realizan los clientes, asociarlos a las mesas y hacer un seguimiento 
del estado de cada pedido.
Requisitos:
- Un pedido contiene uno o varios platos, y cada plato tiene un nombre, un precio y una 
categoría (entrada, plato principal, postre).
- Un cliente puede hacer varios pedidos, y un pedido puede estar asociado a una mesa del 
restaurante.
- Las mesas tienen un número de identificación único.
- Los pedidos tienen un estado (pendiente, en preparación, servido) y una hora de creación.
### Sistema de Reservas de Vuelos 
Se desea modelar un sistema de reservas de vuelos. El sistema permite a los clientes buscar y 
reservar vuelos, que conectan aeropuertos específicos en determinadas fechas y horas.
Requisitos:
- Un vuelo tiene un número de vuelo, una aerolínea, una fecha y una hora de salida y llegada, 
y está asociado a un avión.
- Los clientes pueden reservar asientos en los vuelos, y cada reserva tiene un número de 
confirmación, la fecha de la reserva y el asiento asignado.
- Cada avión tiene un modelo, una capacidad máxima de pasajeros y pertenece a una 
aerolínea.
- Los aeropuertos tienen un código único, un nombre y una ciudad.

Punto 1:

![Diagrama 1](/TP1/punto1.png)

Punto 2:

![Diagrama 2](/TP1/punto2.png)

Punto 3:

![Diagrama 3](/TP1/punto3.png)