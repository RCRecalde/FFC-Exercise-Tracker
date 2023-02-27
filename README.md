# [Exercise Tracker](https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/exercise-tracker)

- POST REQUEST /api/users : Crea un nuevo usuario y la guarda en la base de datos.

- POST REQUEST /api/users/:id/exercises : Busca un usuario por ID, si lo encuentra agrega los nuevos datos ingresados, de lo contrario muestra un error. 

- GET REQUEST /api/users/:id/logs : Busca un usuario por ID, si lo encuentra muestra todos sus registros, con la posibilidad de filtrar por el req.query: mostrar un limite de registros o mostrar registros en un intervalo de fechas. Si no encuentra al usuario muestra un error

- GET REQUEST /api/users : Muestra todos los usuarios de la base de datos.