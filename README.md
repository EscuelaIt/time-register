# Registro de tiempo de proyectos

Backend basado en API REST para el registro de tiempo dedicado a proyectos.

El desarrollo de este proyecto se explicó en el [Curso de API REST con Laravel](https://escuela.it/cursos/curso-laravel-api). El código del proyecto del API se encuentra en <https://github.com/EscuelaIt/timer-back>.

## Dominio

![Dominio](/docs/domain.svg)

## Casos de uso

Paquetes de casos de uso:

![Paquetes de casos de uso](/docs/usecase-packages.svg)

### Auth

![Autenticación](/docs/auth-usecases.svg)

### Customer

![Clientes](/docs/customer-usecases.svg)

### Project

![Projects](/docs/project-usecases.svg)

### Category

![Categorías](/docs/category-usecases.svg)

### Interval

![Intervalos](/docs/interval-usecases.svg)
 
## Estados de intervalo

Solamente es posible tener un intervalo de trabajo abierto a la vez.

![Estados de intervalo](/docs/interval-opened-closed-states.svg)

## Diagrama de despliegue

![Diagrama de despligue API REST](/docs/deploy-diagram.svg)
