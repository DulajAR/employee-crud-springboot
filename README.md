# 🧑‍💼 Employee CRUD Application

A simple and responsive **CRUD web application** for managing employees, built using:

- **Java 17**
- **Spring Boot**
- **Thymeleaf (HTML/CSS)**
- **MySQL**

---

## 📋 Features

- View all employees
- Add new employee (dynamic form toggle using ➕ icon)
- Edit employee details
- Delete employee with confirmation
- Clean UI using HTML, CSS, and icons

---

## ⚙️ Requirements

- Java 17
- Maven
- MySQL 5.7+ or 8.0+

---

## 🛠️ Setup Instructions

1. **Clone or download** this repository:
   ```bash
   git clone https://github.com/your-username/employee-crud-app.git
   cd employee-crud-app
   ```

2. **Create MySQL database**:
   ```sql
   CREATE DATABASE employees_db;
   ```

3. **Configure database credentials** in `src/main/resources/application.properties`:
   ```properties
   spring.datasource.username=your_mysql_username
   spring.datasource.password=your_mysql_password
   spring.datasource.url=jdbc:mysql://localhost:3306/employees_db
   ```

4. **Run the application**:
   ```bash
   mvn spring-boot:run
   ```

5. **Access the app** in your browser at:
   ```
   http://localhost:8080/
   ```

---

## 📁 Folder Structure

```
src/
├── main/
│   ├── java/
│   │   └── com.example.employee/
│   │       ├── controller/
│   │       ├── model/
│   │       ├── repository/
│   │       └── EmployeeCrudApplication.java
│   └── resources/
│       ├── templates/
│       │   ├── index.html
│       │   └── edit.html
│       └── application.properties
```

---

## 📝 Technologies Used

- Spring Boot (Web, Thymeleaf, Data JPA)
- Maven
- MySQL
- HTML + CSS

---

## 📸 Screenshots (Optional)
_Add screenshots of your app UI here if needed._

---

## 🧑‍💻 Author

- **Dulaj Ranasinghe**
- [YouTube Channel: Dulaj TV](https://www.youtube.com/@DulajTV)