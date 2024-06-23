# Student-Performance-Monitoring-System
This Student Performance Monitoring System is a comprehensive web application designed to track and analyze the academic progress of students. The project leverages robust technologies including Java, Angular, Spring Boot, and MySQL to deliver a seamless user experience.

**Technologies Used**
Backend: Java, Spring Boot
Frontend: Angular
Database: MySQL
APIs: RESTful services with Spring Boot

**Getting Started**
**Prerequisites**
Java 8 or higher
IntelliJ IDEA
Maven
MySQL

**Installation**

**Backend Setup:**

**Step 1: Clone the Repository**
- Open your terminal.
- Clone the repository:git clone https://github.com/yourusername/student-performance-monitoring-system.git
- Navigate to the backend directory:cd student-performance-monitoring-system/backend

**Step 2: Open the Project in IntelliJ IDEA**
- Open IntelliJ IDEA.
- Select File > Open.
- Navigate to the backend directory and click OK.

**Step 3: Import the Maven Project**
- IntelliJ IDEA should detect the pom.xml file and prompt you to import the Maven project. Click Import.
- If not, go to View > Tool Windows > Maven and click Refresh to load the project.

**Step 4: Configure the Database**
- Set up your MySQL database and create a new database.
- Update application.properties in src/main/resources:

spring.datasource.url=jdbc:mysql://localhost:3306/your_database_name
spring.datasource.username=your_database_username
spring.datasource.password=your_database_password
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

**Step 5: Run the Application**
- Locate the main class annotated with @SpringBootApplication, e.g., com.example.Application.
- Open this file in IntelliJ IDEA.
- Click the Run button (green play button) in the gutter next to the class declaration, or right-click the class and select Run 'Application'.

**Frontend Setup:**

**Step 1: Navigate to the Frontend Directory**
- Open your terminal.
- Navigate to the frontend directory:cd student-performance-monitoring-system/frontend
  
**Step 2: Install Dependencies**
- Ensure Node.js and Angular CLI are installed.
- Install dependencies:npm install
  
**Step 3: Run the Application**
- Start the Angular development server:ng serve -o
- Open your browser and go to http://localhost:4200/ to view the frontend.

**Screenshots**
**Login Page**
![login](https://github.com/MansiSachdev/Student-Performance-Monitoring-System/assets/93983135/a3cc181b-38c5-4088-a997-11ea1c498ead)

**Dashboard**
![Dashboard](https://github.com/MansiSachdev/Student-Performance-Monitoring-System/assets/93983135/a437fb74-1b27-4f58-a475-a1334d20efdb)

**Staff Management**
![staff](https://github.com/MansiSachdev/Student-Performance-Monitoring-System/assets/93983135/e69ac12c-ca75-4c62-a415-a114a306810f)

**Department Management**
![Department](https://github.com/MansiSachdev/Student-Performance-Monitoring-System/assets/93983135/fc55aeed-c38e-417e-b833-cc80ef3609da)

**Subject Management**
![subject](https://github.com/MansiSachdev/Student-Performance-Monitoring-System/assets/93983135/ef6f0e87-120f-4c8c-85ef-d88b9f096951)
