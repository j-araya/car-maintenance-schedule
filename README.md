# car-maintenance-schedule
An app to manage the car mantenance 

Aplicación que permita llevar el mantenimiento de un carro

Con Kilometrajes y lapsos de tiempo

Agregar mantenimientos periódico por lapsos de tiempo y/o kilometrajes. Ejemplo: cambio de aceite cada 6 meses / 5000 kilometros

Al llegar la hora debe notificar y hacer cambio de estado de estos mantenimientos de "pendiente" a "vencido" y si se completa a "completado". 

Debe llevar registro de cuando se han completado los mantenimientos tanto en fechas como en kilometraje del carro. Y permitirle al usuario ver el historial de mas reciente a mas antiguo. 

Debe almacenar toda la información en una base de datos en internet. Gracias a un servidor web se podrá acceder a la información. 

Las herramientas a usar serán Django para realizar la app web y un gestor de base de datos MySQL o PostgreSQL. 

Mas adelante se podrá reutilizar la app web en Django para realizar una Api rest la cual pueda ser utilizada por una app movil desarrollada en Flutter (framework de aplicaciones multiplataforma). 