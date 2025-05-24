# User Access Management System

> ⚠️ **Important**: Please review the demo video for a complete walkthrough of the project features and functionality.

## Project Overview
A Java-based User Access Management System built using Jakarta Servlet and PostgreSQL. This project provides user authentication and authorization functionality with a secure database backend.

## Technologies Used
- Java 23
- Jakarta Servlet 5.0.0
- PostgreSQL 42.2.18
- Maven

## Prerequisites
- JDK 23 or higher
- PostgreSQL Database
- Maven installed
- A Servlet container (like Apache Tomcat)

## Project Structure
```
UserAccessManagement/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── [Java source files]
│   │   ├── resources/
│   │   └── webapp/
│   │       └── [Web resources]
└── pom.xml
```

## Database Setup
1. Install PostgreSQL
2. Create a new database
3. Run the necessary SQL scripts (provided in the project)

## Building the Project
```bash
mvn clean install
```

## Running the Application
1. Deploy the generated WAR file to your servlet container
2. Access the application through your web browser

## Features
- User Authentication
- Access Control Management
- [Add other features you've implemented]

## Configuration
Update the database connection properties in your configuration file:
```properties
db.url=jdbc:postgresql://localhost:5432/your_database
db.username=your_username
db.password=your_password
```



## Contributing
Feel free to fork this project and submit pull requests.

## Developer Contact Information
- **Name:** Nikhil G
- **Email:** nikhilreddyagr@gmail.com

## License
This project is licensed under the MIT License - see the LICENSE.md file for details
