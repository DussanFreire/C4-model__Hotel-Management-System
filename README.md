# SistemaDeHotel

En este proyecto se puede ver la representación de un sistema monolítico de un hotel a través del modelo c4 y clases no funcionales.

Como base del presente trabajo, se utilizo el modelo monolítico representado en la pagina https://c4model.com/ , en la sección “C4 and UML”

## Nivel 1, Contexto: 
Esta capa esta diseñada para dar un vistazo a muy alto nivel del sistema, es diagrama debe poder ser mostrado al cliente. 
<img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Nivel%201.jpg" />

## Nivel 2, Contenedores: 
Al ser un sistema monolítico este diagrama solo contiene la aplicación web y la base de datos que sirve para almacenar la información del hotel. <img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Nivel-2.jpg" /> 


## Nivel 3, Contenedores: 
En esta sección se amplió la aplicación web, se utilizo un modelo monolítico basado en 3 capas para representar esta sección. 
<img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/modelo%203%20capas.jpg" /> 
Diagrama:
<img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Nivel-3.jpg" /> 
En la siguiente imagen se puede observar el nivel 3 pero con las secciones de las 3 capas distinguidas por un color. <img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/detalle-Nivel%203.jpg" /> 
En esta sección, adicionalmente, también se expandió la base de datos. <img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Modelo%20ER.jpg" /> 
Nivel 4, Código o Diagrama de Clases: En esta sección se expandieron los contenedores 
### Capa de presentacion:
Vista:
<img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Page-12.jpg" /> 
### Capa de logica de negocio:
Controladores:
* Controlador de huespedes:. <img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Page-4.jpg" /> 
* Controlador de hospedaje:. <img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Page-6.jpg" /> 
* Controlador de habitacion:. <img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Page-5.jpg" /> 
Servicios:
* Servicio de huespedes:. <img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Modelo%20ER.jpg" /> 
* Servicio de hospedaje:. <img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Page-9.jpg" /> 
* Servicio de habitacion:. <img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Page-10.jpg" /> 
### Capa de logica de acceso a datos:
Repositorio:
<img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/page-7.jpg" /> 

El nivel 4 también esta implementado de una manera no funciona alto nivel a través de código dentro de este repositorio 
