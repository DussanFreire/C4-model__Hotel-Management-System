# C4 model - Hotel Management System 🛌🛎
This project aims to automate the management of room bookings, guest registrations, and stays for a hotel using a monolithic system. The system is represented through the C4 model and non-functional class diagrams, demonstrating the architecture and functionality.

The monolithic architecture is based on the C4 model, as outlined on the website https://c4model.com/ in the section “C4 and UML.”

## Level 1: Context
* This layer provides a very high-level view of the system, which can be presented to the client. 
<br><img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Nivel%201.jpg" /><br>
## Level 2: Containers
* Since this is a monolithic system, the diagram contains only the web application and the database that stores the hotel’s information.
<br><img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Nivel-2.jpg" /> <br>
## Level 3: Components: 
* This section expands on the web application using a 3-layer monolithic model to represent this part.
<br><img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/modelo%203%20capas.jpg" /> <br>
* Diagram:
<br> <img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Nivel%203.jpg" /> <br>
* Below is Level 3 with the three layers distinguished by color: <img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/detalle-Nivel%203.jpg" /> <br>
* Additionally, the database has been expanded in this section.
<br><img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Modelo%20ER.jpg" /> <br>
## Level 4: Code and Class Diagrams
In this section, the containers are further expanded. 
### Presentation Layer
* View
<br><img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Page-12.jpg" /> <br>
### Business Logic Layer
#### Controllers:
* Guest Controller: 
<br><img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Page-4.jpg" /> <br>
* Stay Controller: 
<br><img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/page-6.jpg" /> <br>
* Room Controller:
<br><img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Page-5.jpg" /> <br>
#### Services:
 * Interfaces were used in this section to follow the Liskov Substitution Principle, allowing for extensions rather than modifications.
 * Additionally, patterns like the Factory Method could be applied here.
* Guest Service:
<br><img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Page-10.jpg" /> <br>
* Stay Service:
<br><img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Page-9.jpg" /> <br>
* Room Service:
<br><img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Page-10.jpg" /> <br>
### Data Access Layer
* Repository:
  * A Singleton pattern was used for the repository to ensure that the database is shared across all components.
  * If working with an older database, the Adapter pattern could be applied. In this case, however, as the database is being implemented from scratch, this is not necessary.
<br><img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/page-7.jpg" /> <br>
* Level 4 is also implemented through high-level, non-functional code available within this repository.
