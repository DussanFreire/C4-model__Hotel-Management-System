# SistemaDeHotel 🛌🛎
El siguiente sistema busca automatizar el registro de habitaciones, huéspedes y hospedajes de un hotel a través de un sistema monolítico. En este proyecto se puede ver la representación del sistema monolítico del sistema, a través del modelo C4 y clases no funcionales.

Como base del presente trabajo, se utilizo el modelo monolítico representado en la pagina https://c4model.com/ , en la sección “C4 and UML”

## Nivel 1, Contexto: 
* Esta capa esta diseñada para dar un vistazo a muy alto nivel del sistema, es diagrama debe poder ser mostrado al cliente. 
<br><img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Nivel%201.jpg" /><br>
## Nivel 2, Contenedores: 
* Al ser un sistema monolítico este diagrama solo contiene la aplicación web y la base de datos que sirve para almacenar la información del hotel. 
<br><img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Nivel-2.jpg" /> <br>
## Nivel 3, Contenedores: 
* En esta sección se amplió la aplicación web, se utilizo un modelo monolítico basado en 3 capas para representar esta sección. 
<br><img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/modelo%203%20capas.jpg" /> <br>
* Diagrama:
<br> <img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Nivel%203.jpg" /> <br>
* En la siguiente imagen se puede observar el nivel 3 pero con las secciones de las 3 capas distinguidas por un color. <img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/detalle-Nivel%203.jpg" /> <br>
* En esta sección, adicionalmente, también se expandió la base de datos. 
<br><img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Modelo%20ER.jpg" /> <br>
## Nivel 4, Código o Diagrama de Clases: En esta sección se expandieron los contenedores 
### Capa de presentacion:
* Vista:
<br><img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Page-12.jpg" /> <br>
### Capa de logica de negocio:
Controladores:
* Controlador de huespedes: 
<br><img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Page-4.jpg" /> <br>
* Controlador de hospedaje: 
<br><img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/page-6.jpg" /> <br>
* Controlador de habitacion:
<br><img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Page-5.jpg" /> <br>
Servicios:
* Servicio de huespedes:
<br><img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Page-10.jpg" /> <br>
* Servicio de hospedaje:
<br><img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Page-9.jpg" /> <br>
* Servicio de habitacion:
<br><img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Page-10.jpg" /> <br>
### Capa de logica de acceso a datos:
* Repositorio:
<br><img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/page-7.jpg" /> <br>
* El nivel 4 también esta implementado de una manera no funciona alto nivel a través de código dentro de este repositorio 
