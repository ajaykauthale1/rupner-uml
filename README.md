# Rupner — Service Interaction Diagrams

PlantUML sequence diagrams for **Rupner**, a microservice-based classroom platform (users, classes, assignments, discussions, events, grades) built with Spring Boot services behind an API gateway.

## Diagrams
Each flow is defined in [`PlantUml.txt`](PlantUml.txt) and rendered to PNG:
FetchUserInfo · FetchClassesForUser · FetchStudentsForClass · FetchAssignmentInfo · FetchAssignmentsForClass · FetchGradesForAssignment · FetchGradesForStudent · FetchEventsForClass · FetchEventsForUser · FetchDiscussionsForUser · FetchHotDiscussionsForClass/User

They show how the User Data, Class, Assignment, Discussion and Event services, each owning its own database, collaborate to serve a request.

## Render
Paste any block into [plantuml.com](https://www.plantuml.com/plantuml) or run `plantuml PlantUml.txt`.
