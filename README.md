1.1: 
pregunta 1: Si, es necesario usar persistencia. esto asegura que los datos de las reservas se mantengan a lo largo del tiempo. 
pregunata 2: Si, seria util para los tipos de habitaciones disponibles.

1.2:
pregunta 1: Si, es necesario persistir los datos de los empleados para mantener un registro histórico y actualizado de la información del personal.
pregunta 2: No, no es necesario usar un diccionario si los departamentos son fijos y no cambian.

1.3:
pregunta 1: Si, es necesario almacenar los pedidos para llevar un control de las ventas.
pregunta 2: Si, esto permite definir de manera clara los tipos de pizza.

1.4: 
pregunta 1:Si, es neecsario usar persistencia para almacenar a los pacientes.
pregunta 2:Para los servicios medicos que ofrece la clinica, podrias usar una lista si solo necesitas almacenar los nombres de los servicios.
 Si necesitas asociar más informacion con cada servicio, como tarifas, podrias usar un diccionario.

2.1:
pregunta 1:la relacion es de uno a muchos (agregacion)
pregunta 2: la relacion es de muchos a muchos (composicion)
pregunta 3: la relacion es de agregacion

2.2:
pregunta 1:relacion de uno a muchos (asocioacion)
pregunta 2: relacion de uno a muchos (agregacion)
pregunta 3: es unidireccional

2.3:
pregunta 1: relacion uno a muchos (asociacion)
pregunta 2: relacion de muchos a muchos (agregacion)
pregunta 3: la relacion es de agregacion

2.4:
pregunta 1: public List(Producto) : ProductosSolicitados
pregunta 2: public List(Pedido) : Pedidos 
pregunta 3: public string Tipo 
pregunta 4: public TipoProducto Tipo 
pregunta 5: public void GenerarReporteDiario()


2.5: 
pregunta 1:public Propietario : Propietario 
pregunta 2:public List(Paciente) : Mascotas 
pregunta 3:public Paciente : Paciente 
pregunta 4:public List(Consulta) ObtenerConsultasRealizadas()
pregunta 5:public List(Paciente) ListarTodosLosPacientes()
           public List(Propietario) ListarTodosLosPropietarios()


2.6:
pregunta 1:public bool Disponibilidad 
pregunta 2:public List(Reserva) : ReservasActivas 
pregunta 3:public Libro LibroReservado 
pregunta 4:public void DevolverLibro(Reserva reserva)
pregunta 5: public List(Libro) ListarLibrosDisponibles()
            public List(Miembro) ListarMiembrosRegistrados()

3:
pregunta 1: Encapsulacion consiste en ocultar los detalles internos de un objeto y exponer solo lo necesario a través de metodos publicos.
Esto se logra mediante el uso de modificadores de acceso como private, protected y public.
Su proposito consiste en que evita el acceso no autorizado y la modificacion de datos, tambien facilita el mantenimiento del codigo sin afectar a otras partes.

pregunta 2:Herencia es un mecanismo que permite crear una nueva clase (subclase) basada en una clase existente (superclase).
La subclase hereda atributos y metodos de la superclase, y puede agregar nuevos atributos y metodos o sobrescribir los existentes.
Su proposito consiste en que permite la reutilizacion del codigo, mejor organizacion y extensibilidad
pregunta 3: Polimorfismo es la capacidad de un objeto de tomar muchas formas. Permite que una interfaz única sea utilizada para representar diferentes tipos de objetos.
Se aplica permitiendo definir multiples metodos con el mismo nombre pero diferentes parametros, tambien permite que diferentes clases implementen los mismos metodos de manera distinta
pregunta 4: Interfaz es un contrato que define un conjunto de métodos que una clase debe implementar, pero no proporciona ninguna implementacion de esos metodos.

Clase abstracta es una clase que puede contener tanto metodos abstractos (sin implementacion) como metodos concretos (con implementacion). No se puede instanciar directamente.

Diferencias:
Implementación: Una interfaz no puede contener implementación de métodos, mientras que una clase abstracta puede.
Herencia múltiple: Una clase puede implementar múltiples interfaces, pero solo puede heredar de una clase abstracta.
Propiedades y campos: Las interfaces no pueden tener campos o propiedades con implementación, mientras que las clases abstractas sí pueden.
