# C4 model - Hotel Management System 🛌🛎
This project aims to automate the management of room bookings, guest registrations, and stays for a hotel using a monolithic system. The system is represented through the C4 model and non-functional class diagrams, demonstrating the architecture and functionality.

The C4 model (Context, Containers, Components, and Code) is a framework for visualizing the architecture of software systems. Developed by Simon Brown, it helps software architects and developers create clear and concise diagrams to communicate the structure and design of a system. The model emphasizes simplicity and focuses on four hierarchical levels of abstraction, which provide different views of the system:

The monolithic architecture is based on the C4 model, as outlined on the website https://c4model.com/ in the section “C4 and UML.”

## Level 1: Context 
* 	Purpose: Provides a high-level view of the system and its interactions with external entities (users, external systems, etc.).
* 	Content: Shows the system as a single box, along with its external actors and the relationships between them.
* 	Audience: This diagram is suitable for stakeholders who need to understand how the system fits into the broader ecosystem.
<br><img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Nivel%201.jpg" /><br>
## Level 2: Containers
*  Since this is a monolithic system, the diagram contains only the web application and the database that stores the hotel’s information.
* 	Purpose: Details the major containers (applications, services, databases) that make up the system and how they interact with each other.
* 	Content: Illustrates the different containers, their responsibilities, and their relationships. Containers can be web applications, mobile apps, databases, etc
* 	Audience: Useful for developers and architects who need to understand the high-level architecture of the system.
<br><img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Nivel-2.jpg" /> <br>
## Level 3: Components: 
*  This section expands on the web application using a 3-layer monolithic model to represent this part.
*  Since this is a monolithic system, the diagram contains only the web application and the database that stores the hotel’s information.
* 	Purpose: Breaks down a specific container into its internal components, detailing their interactions and responsibilities.
* 	Content: Shows the main components of a particular container and how they communicate with each other. Components can be classes, modules, or services within a container.
* 	Audience: Aimed at developers who need to understand the internal structure of a container.

<br><img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/modelo%203%20capas.jpg" /> <br>
* Diagram:
<br> <img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Nivel%203.jpg" /> <br>
* Below is Level 3 with the three layers distinguished by color: <img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/detalle-Nivel%203.jpg" /> <br>
* Additionally, the database has been expanded in this section.
<br><img src="https://github.com/DussanFreire/SistemaDeHotel/blob/main/Modelo%20c4/Modelo%20ER.jpg" /> <br>
## Level 4: Code and Class Diagrams
*  Purpose: Provides a detailed view of the code within a component, focusing on classes and their relationships.
* 	Content: May include UML class diagrams or similar representations, showcasing methods, attributes, and relationships between classes.
* 	Audience: Primarily for developers who need to work on or maintain the codebase.
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
