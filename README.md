# 🎓 College Management System (Spring Boot)

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-2.7.0-brightgreen?logo=springboot&logoColor=white)  ![Java](https://img.shields.io/badge/Java-17-orange?logo=java&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-Database-blue?logo=mysql&logoColor=white)  ![Postman](https://img.shields.io/badge/Postman-API%20Testing-orange?logo=postman&logoColor=white)  ![Maven](https://img.shields.io/badge/Maven-Build%20Tool-red?logo=apachemaven&logoColor=white)  ![Eclipse](https://img.shields.io/badge/Eclipse-IDE-purple?logo=eclipseide&logoColor=white)  ![GitHub repo size](https://img.shields.io/github/repo-size/Rohitlakha/College-Management-System-SpringBoot)  ![GitHub stars](https://img.shields.io/github/stars/Rohitlakha/College-Management-System-SpringBoot?style=social)  

---

This is a **College Management System** project developed using **Spring Boot** and **Eclipse IDE**, with API testing via **Postman** and database integration using **WAMP Server** (MySQL).  

The project was conducted under **ExcelR Training Program** and focuses on building a scalable and efficient backend system to manage core college operations such as students, faculty, courses, and user roles.

---

## 🚀 Features
- 👨‍🎓 Student Management (CRUD operations)
- 👩‍🏫 Faculty Management
- 📚 Course Management
- 👥 Role-based User Management (Admin, Student, Faculty)
- 🌐 RESTful APIs tested via **Postman**
- 💾 Database support with **MySQL (WAMP Server)**

---

## 🛠️ Tech Stack
- **Backend:** Spring Boot  
- **IDE:** Eclipse  
- **Database:** MySQL (via WAMP Server)  
- **Testing:** Postman  
- **Dependency Management:** Maven  
- **Tools:** Lombok, JPA/Hibernate  

---

## 📂 Project Structure
```bash
College-Management-System-SpringBoot
│── src/main/java/com/cms/ # Application source code
│── src/main/resources/ # Configurations (application.properties)
│── pom.xml # Maven dependencies
│── README.md # Project documentation
```
---

## ⚙️ Installation & Setup
1. Clone this repository:
   ```bash
   https://github.com/Rohitlakha/College-Management-System-SpringBoot.git
   ```
2. Open in Eclipse IDE.
3. Configure the database in application.properties:
   ```bash
   spring.datasource.url=jdbc:mysql://localhost:3306/college_db
   spring.datasource.username=root
   spring.datasource.password=yourpassword
   ```
4. Run the project as Spring Boot Application.
5. Test APIs using Postman.

---

## 📌 API Endpoints (Examples)

- `POST /api/students` → Add a new student  
- `GET /api/students` → Fetch all students  
- `PUT /api/students/{id}` → Update student by ID  
- `DELETE /api/students/{id}` → Delete student  

(Similar endpoints exist for Faculty, Courses, and Roles)

---

## 📜 Acknowledgment
This project was conducted as part of the **ExcelR Training Program**.  
Special thanks to mentors and instructors for guidance.  

---

## 👨‍💻 Author
**Rohit Lakha**  

- 🌐 [LinkedIn](https://www.linkedin.com/in/rohit-lakha/)  
- 💻 MCA Student | Data Analyst | Full Stack Enthusiast  


