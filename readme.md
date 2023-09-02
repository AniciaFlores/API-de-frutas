## API-de-frutas
Documentación de la API RESTFUL de Frutas

## Tabla de Contenidos
***
- [API-de-frutas](#api-de-frutas)
- [Tabla de Contenidos](#tabla-de-contenidos)
- [Introducción](#introducción)
- [Instalación](#instalación)
- [Uso](#uso)
- [Tabla General de endpoint](#tabla-general-de-endpoint)

***

¡Bienvenid@! Aquí encontrarás toda la información necesaria para comprender y utilizar la API.

## Introducción
El proyecto se encuentra disponible en la siguiente URL base: http://localhost:3008/api/v1/

***
## Instalación
**Clona el repositorio**:
git clone https://github.com/AniciaFlores/API-de-frutas.git

**Instala las dependencias**:
npm intall

**Configura las variables de entorno en un archivo .env**:

PORT=3008
MONGODB_URLSTRING=mongodb+srv://admin:admin123@nube0.bq7gxyp.mongodb.net/?retryWrites=true&w=majority

***
## Uso
A continuación, te presentamos ejemplos de uso y de respuestas para cada uno de los métodos disponibles:

**GET**
http://localhost:3000

**POST**
http://localhost:3000/frutas

Ejemplo del cuerpo del mensaje:
{
"_id": "64f39ca882f7347f1baafee3"
}

**PUT**
 http://localhost:3000/frutas/1
Ejemplo del cuerpo del mensaje:
{
"descripcion": "Fruta actualizado ID : 1",
"objeto": {}
}

**DELETE**
http://localhost:3000/frutas/1


***
## Tabla General de endpoint

| Método | Endpoint                       | Ruta Base  | Descripción                                 |
| ------ | ------------------------------ | ---------- | ------------------------------------------- |
| GET    | `/frutas`                      | `/`        | Obtener todas las frutas                    |
| GET    | `/frutas/:id`                  | `/`        | Obtener una fruta por ID                   |
| GET    | `/frutas/nombre/:nombre`       | `/`        | Buscar frutas por nombre                   |
| GET    | `/frutas/precio/:precio`       | `/`        | Buscar frutas por precio                   |
| POST   | `/frutas`                      | `/`        | Crear una nueva fruta                       |
| PUT    | `/frutas/:id`                  | `/`        | Actualizar una fruta por ID                |
| DELETE | `/frutas/:id`                  | `/`        | Eliminar una fruta por ID                  |
