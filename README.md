# 📚 Student Management System (Console-Based Java Project)

## 🧾 Project Overview

This project is a **console-based Student Management System** built using the Java programming language, designed to demonstrate the use of **Object-Oriented Programming (OOP)** concepts like inheritance, abstraction, encapsulation, and polymorphism.

It supports two types of users: **Admin** and **Student** with distinct functionalities.

---

## 👤 User Roles and Functionalities

### 👩‍💼 Admin
- Add and manage **Courses**
- Add and manage **Subjects** under each Course
- View list of all **Registered Students**
- View **Exam Results** of students

### 👨‍🎓 Student
- Register with personal details (name, age, email)
- View and select available **Courses**
- Choose **Subjects** under selected course
- Take an **MCQ Exam** (5 questions minimum)
- View their **Exam Results**

---

## 🛠️ Technologies Used

- Java (JDK 8+)
- Java Collections Framework (`ArrayList`, `HashMap`)
- Java OOP Concepts
- Console I/O using `Scanner`
- Optional: File I/O (can be added for persistence)

---

## 🗂️ Project Structure

├── Main.java
├── users
│ ├── User.java (abstract)
│ ├── Admin.java
│ └── Student.java
├── models
│ ├── Course.java
│ ├── Subject.java
│ └── Exam.java
├── services
│ ├── CourseService.java
│ ├── StudentService.java
│ └── ExamService.java
└── util
└── InputUtil.java
## 🚀 How to Run

1. **Clone or Download** the project files.
2. Open the project in any Java IDE (e.g., IntelliJ IDEA, Eclipse) or compile via terminal.
3. Run the `Main.java` file.
4. Use the console menu to operate as Admin or Student.

---

## 🧠 Key Features Demonstrated

- Abstract classes and interfaces
- Data encapsulation
- Dynamic polymorphism
- Real-life role-based operations
- Simple in-memory data management



## 📌 Notes

- You can extend this project with **File I/O**, **Database (JDBC)**, or even **GUI using JavaFX or Swing** to make it more advanced.
- Default admin does not need login credentials for simplicity.

---

## 👨‍💻 Author

**Arham Syed**  
Student, B.Tech  
Sharda University

