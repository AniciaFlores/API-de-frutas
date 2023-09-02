# API-de-frutas
Documentación de la API RESTFUL de Frutas

## Tabla de contenido
- [API-de-frutas](#api-de-frutas)
  - [Tabla de contenido](#tabla-de-contenido)
  - [Introducción](#introducción)
  - [Instalación](#instalación)
  - [Uso](#uso)
      - [GET](#get)
      - [POST](#post)
      - [PUT http://localhost:3000/frutas/1](#put-httplocalhost3000frutas1)
      - [DELETE](#delete)

¡Bienvenid@! Aquí encontrarás toda la información necesaria para comprender y utilizar la API.

## Introducción
El proyecto se encuentra disponible en la siguiente URL base: http://localhost:3008/api/v1/

## Instalación

1. Clona el repositorio:
git clone https://github.com/AniciaFlores/API-de-frutas.git


2. Instala las dependencias:
npm intall


1. Configura las variables de entorno en un archivo .env:

PORT=3008
MONGODB_URLSTRING=aquí-va-la-direccio-de-tu-base-de-datos

<a name="uso"></a>
## Uso

A continuación, te presentamos ejemplos de uso y de respuestas para cada uno de los métodos disponibles:

#### GET
http://localhost:3000


#### POST 
http://localhost:3000/frutas

Ejemplo del cuerpo del mensaje:
{
  "_id": "64f39ca882f7347f1baafee3"
}

#### PUT http://localhost:3000/frutas/1

Ejemplo del cuerpo del mensaje:
{
  "descripcion": "Fruta actualizado ID : 1",
  "objeto": {}
}

#### DELETE 
http://localhost:3000/frutas/1

