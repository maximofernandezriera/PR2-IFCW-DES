Desarrollar una aplicación sencilla utilizando Laravel para gestionar un rastreador de gastos, siguiendo el enfoque del proyecto "Expense Tracker" en [Expense Tracker Project](https://roadmap.sh/projects/expense-tracker). La aplicación deberá cumplir con los siguientes requisitos:

# REQUISITOS GENERALES

Pantalla de inicio: Implementa una interfaz donde se muestren todos los gastos registrados. Cada gasto deberá incluir:

- Un título.

- Una descripción breve.

- Un total.

- Una fecha de registro.

Agregar nuevos gastos: La aplicación debe permitir al usuario agregar nuevos gastos mediante un formulario.

editar y eliminar gastos: Cada gasto debe tener opciones para ser editado o eliminado.

Persistencia de datos: Los datos de los gastos deben almacenarse en una base de datos SQLite tal y como hemos visto en clase.

#  REQUISITOS MÍNIMOS ESPECÍFICOS DE LARAVEL

Rutas y controladores:

Define rutas para listar, agregar, editar y eliminar gastos.

* Implementa controladores correspondientes para manejar las acciones de cada ruta.

* Migraciones: Crea migraciones para configurar la estructura de la base de datos SQLite.

#  REQUISITOS OPCIONALES ESPECÍFICOS DE LARAVEL (PARA OPTAR A MÁS NOTA)

* Validación de datos: Implementa validaciones para asegurarte de que los campos requeridos se completen al agregar o editar un gasto.

* Implementa autenticación de usuarios para que cada usuario pueda gestionar sus propios gastos.

# CONSIDERACIONES ADICIONALES

* El diseño de las interfaces no es importante, eso es temario de otros módulos.
  
* Proporciona instrucciones claras sobre cómo instalar, ejecutar y probar la aplicación en un archivo README. Básicamente utilizaré github codespaces para probar la aplicación.

# NOTAS

Podéis tomar como referencia estos proyectos:

- [Todo list project](https://github.com/maximofernandezriera/todo-list-sqlite)

- [Solución NodeJs - Expense Tracker Project](https://github.com/roadmap-mini-projects/expense-tracker-cli)
- [Solución Java - Expense Tracker Project](https://github.com/roadmap-mini-projects/expense-tracker-cli)

# FECHA DE ENTREGA: 26-01-2025
