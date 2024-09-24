# Software Systems Construction Project

This project focuses on building a management platform for master's theses at a university. The platform supports both project-based and dissertation-based theses, streamlining the management process for both students and supervisors. Students can register for thesis topics, submit their proposals, and schedule both their proposal defense and final defense. Supervisors can assign thesis topics to students, evaluate defenses, and assign grades accordingly.

The project includes two main components: a web application for supervisors and a JavaFX desktop application for students.

Key technologies used include object-oriented programming (OOP) principles and object-relational mapping (ORM) standards to map OOP relationships to relational databases. We employed the Spring framework to manage ORM, REST APIs, and other essential functionality.

## How to Run the Web Application:

- Docker is required on Linux.
- Use the command `docker compose --up build`.
- Access the web app at: http://localhost:8080.

## How to Run the JavaFX Application:

- Ensure the web application is running first.
- Navigate to the `desktop-app` folder.
- Execute the command `mvn clean javafx:run`.

## Important Notes:

- It’s recommended to test only one application at a time, as mock data conflicts might occur during testing.
  
- The project received a final score of 21.54 out of 24.

## Authors
João Miguel Real Pereira - fc58189

Martim Cabral Rocha Pereira - fc58223

Daniel de Lima Nunes - fc58257
