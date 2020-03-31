PaymentService

Developed in ASP.NET Core.
The funcionality of the project, is to return a unique Transaction ID when receiving a card number.

The format of the request body:
{
  "TargetNumber": "string",
  "TotalToPay": 0
}

Response body is similar to:
127655431032020123257

_________________

Desarrollado en ASP:NET Core
El proyecto regresa un número único de transacción cuando recibe un número de tarjeta en formato json en el body:
{
  "TargetNumber": "string",
  "TotalToPay": 0
}

La respuesta es similar a lo siguiente:
127655431032020123257





