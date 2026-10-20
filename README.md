# EduEnroll
EduEnroll is a Java-based Student Management System developed to simplify the management of student information through a web-based application. It provides a structured way to manage student records using Java, JSP, JDBC, and PostgreSQL.

The project demonstrates the use of Java web development technologies, database connectivity, and server-side processing to build a dynamic web application.

## 📌 Project Overview

EduEnroll is designed to make student record management easier by providing a web interface connected to a PostgreSQL database. It helps organize student information and demonstrates how a Java web application interacts with a relational database.

## ✨ Features

- **Student Management:** Manage student information through the web application.
- **Database Connectivity:** Connects the application to PostgreSQL using JDBC.
- **Dynamic Web Pages:** Uses JSP to generate dynamic content.
- **User Interface:** Built using HTML and CSS.
- **Server-Side Processing:** Uses Java to handle application logic.
- **Web Application Deployment:** Runs on an Apache Tomcat server.

*Note: Keep only the features that are actually implemented in your project.*

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Java | Application logic |
| JSP (JavaServer Pages) | Dynamic web pages |
| JDBC | Database connectivity |
| PostgreSQL | Relational database |
| HTML | Web page structure |
| CSS | Styling and layout |
| Apache Tomcat | Web application server |
| Git & GitHub | Version control and source code hosting |

## ⚙️ How It Works

1. The user interacts with the application's web interface.
2. JSP pages display the required information and handle web requests.
3. Java processes the application logic.
4. JDBC connects the Java application to the PostgreSQL database.
5. PostgreSQL stores and retrieves the relevant student information.
6. The server returns the resulting page to the user through the browser.

## 🏗️ Application Architecture

The application follows a basic Java web application architecture:

*Presentation Layer*
- HTML
- CSS
- JSP
  
**Application Logic Layer*
- Java
*Database Connectivity Layer*
- JDBC

**Database Layer**
- PostgreSQL

**Web Server**
- Apache Tomcat

## 📋 Prerequisites

Before running the project, ensure you have installed:

- Java Development Kit (JDK)
- Apache Tomcat
- PostgreSQL
- A Java-compatible IDE, such as Eclipse or IntelliJ IDEA
- Git (optional, for cloning the repository)

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/saloni-blip/EduEnroll.git
```

Navigate to the project directory:

```bash
cd EduEnroll
```

### 2. Set Up PostgreSQL

- Start your PostgreSQL server.
- Create a database for the application.
- Create the required tables according to the SQL queries used in the project.
- Configure the database connection details in the application's JDBC connection code.

Example JDBC connection format:

java
String url = "jdbc:postgresql://localhost:5432/your_database";
String username = "your_username";
String password = "your_password";

Connection con = DriverManager.getConnection(
    url, username, password
);

Replace the example database name, username, and password with your own configuration.

# 3. Configure the Project

- Open the project in your Java IDE.
- Ensure the PostgreSQL JDBC driver is available in the project.
- Configure Apache Tomcat as the application server.
- Verify that the database connection settings match your local PostgreSQL configuration.

# 4. Run the Application

- Configure the project on your local Apache Tomcat server.
- Build and deploy the application.
- Start the Tomcat server.
- Open the application using the local URL configured for your deployment.

Example:

text
http://localhost:8080/EduEnroll/

The exact URL may vary depending on your Tomcat configuration and project context path.

# 📸 Screenshots

Screenshots of the application's interface can be added here to demonstrate how EduEnroll works.

# Application Interface

<img width="1920" height="1080" alt="Screenshot 2026-10-19 192337" src="https://github.com/user-attachments/assets/965e6837-5bc4-44c6-99f6-7d706ad9b267" />


# 🎯 Learning Outcomes

Through this project, I gained practical experience with:

- Developing Java-based web applications.
- Using JSP to build dynamic web pages.
- Connecting Java applications to PostgreSQL using JDBC.
- Working with relational databases.
- Deploying and running web applications on Apache Tomcat.
- Organizing source code and maintaining a project using GitHub.



