Barber Appointment Service

Description:
This is a learning project built with Spring MVC — a barber shop appointment system.
The project works and performs its main function: users can create barber appointments, and the data is stored in a database using JdbcTemplate.
Note: the project contains architectural issues, duplicated code, and non-ideal design choices. It was created for learning purposes and reflects my early experience with Spring MVC and database integration.

Features:
- Create barber appointments through a web form
- Input validation
- Display a list of all appointments
- Database interaction via JdbcTemplate

Technologies Used:
- Java 11+
- Spring MVC
- Thymeleaf
- Spring JDBC (JdbcTemplate)
- PostgreSQL / MySQL
- Maven

How to Run:
1. Clone the repository: git clone https://github.com/TigranSar/barber-appointment-spring-mvc.git
2. Configure your database and connection settings in application.properties
3. Build and run the project via IDE or Maven:
   mvn clean install
   mvn spring-boot:run
4. Open a browser and go to http://localhost:8080

Project Notes:
- The project contains duplicated code and does not fully follow SOLID principles.
- The application works, but the architecture is far from production-ready.
- This project demonstrates my initial skills with Spring MVC and JdbcTemplate, but significant refactoring would be needed for real-world use.
