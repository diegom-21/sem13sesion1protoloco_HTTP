# Protocolo HTTP

HTTP es un protocolo de comunicación utilizado para transferir información en la web. Define cómo se formatean y transmiten los mensajes y cómo los servidores y navegadores deben responder a diversas solicitudes.

## Request

Un request (solicitud) es un mensaje enviado desde un cliente (normalmente un navegador web) a un servidor. Incluye:

- **Método HTTP:** Define la acción a realizar (GET, POST, PUT, DELETE).
- **URL:** La dirección del recurso solicitado.
- **Headers:** Información adicional sobre la solicitud (tipo de contenido, autenticación, etc.).
- **Body:** Datos enviados con la solicitud (principalmente en POST y PUT).

## Response

Un response (respuesta) es el mensaje enviado desde un servidor al cliente en respuesta a una solicitud. Incluye:

- **Código de estado:** Indica el resultado de la solicitud (200 OK, 404 Not Found, etc.).
- **Headers:** Información adicional sobre la respuesta (tipo de contenido, longitud, etc.).
- **Body:** Los datos solicitados o un mensaje de error.

## API REST

Una API REST (Representational State Transfer) es una interfaz que sigue los principios REST y permite interactuar con recursos del servidor a través de operaciones estándar HTTP. Los recursos son identificados por URLs y pueden ser manipulados usando los métodos HTTP.

## Métodos HTTP

- **GET:** Recupera información de un recurso.
- **POST:** Envía datos al servidor para crear un nuevo recurso.
- **PUT:** Envía datos al servidor para actualizar un recurso existente.
- **DELETE:** Elimina un recurso existente.

## Códigos de Respuesta

- **100(Informativo):** La solicitud fue recibida y el proceso continúa.
- **200 (Éxito):** La solicitud fue recibida, entendida y procesada correctamente (200 OK, 201 Created).
- **300 (Redirección):** Se requiere una acción adicional para completar la solicitud (301 Moved Permanently, 302 Found).
- **400 (Error del Cliente):** La solicitud contiene sintaxis incorrecta o no puede ser procesada (400 Bad Request, 401 Unauthorized, 404 Not Found).
- **500 (Error del Servidor):** El servidor falló al cumplir una solicitud válida (500 Internal Server Error, 502 Bad Gateway).

## Cliente-Servidor

El modelo cliente-servidor describe la interacción entre dos programas: el cliente, que solicita recursos o servicios, y el servidor, que proporciona esos recursos o servicios.

## Formato 

Se usa el formato JSON (JavaScript Object Notation) es un formato ligero para el intercambio de datos, fácil de leer y escribir para humanos, y fácil de parsear y generar para máquinas.

