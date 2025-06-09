# 📚 Bibliotek – Smart Library Management System (Java + Swing + MySQL)

**Bibliotek** is a desktop-based Integrated Library System (ILS) developed in Java. It streamlines library operations such as managing books, tracking issued/returned items, calculating fines for overdue returns, and maintaining user roles (Admin/Student). Built using Java Swing and JDBC, it provides a clean user interface and reliable backend integration.

---

## 🚀 Features

- 🔐 **Login System** – Separate roles for Admin and Students
- 📖 **Book Management** – Add, update, delete, and search for books (Admin only)
- 👥 **User Management** – Manage student records (Admin only)
- 📚 **Issue & Return System** – Track which books are borrowed by whom
- ⏰ **Fine Calculation** – Automatically calculates late return fines
- 📅 **Due Date Tracking** – Highlights overdue books
- 🧩 **Interactive GUI** – Built using Java Swing components
- 🛡️ **Input Validation** – Ensures secure and error-free data entry

---

## 🧑‍💻 Technologies Used

| Component   | Technology            |
|------------|------------------------|
| Language    | Java                  |
| UI Library  | Java Swing            |
| Database    | MySQL or SQLite       |
| Connectivity| JDBC                  |
| IDE         | IntelliJ / Eclipse    |

---

## 🖥️ Screenshots

- 📌 Staring Page
  ![start](https://github.com/user-attachments/assets/ceae99d7-f9f4-4259-a82a-d5c3cfa26104)

- 📌 Login Page
 ![login](https://github.com/user-attachments/assets/a470df6e-c87d-49a6-a260-2657a48cb88f)

- 📌 Dashboard
  ![dashboard](https://github.com/user-attachments/assets/c0df037b-2856-47d3-b06c-9960d89c4076)

- 📌 Book Issue/Return Interface
  ![issue-return](https://github.com/user-attachments/assets/3685bfbd-125b-46f7-8d79-28ff04996c9b)

---

## 🏗️ Project Structure
  ![project structure](https://github.com/user-attachments/assets/943625a6-cd6a-4fcd-9cd7-c61c10bc38de)

---

## 🛠️ How to Run the Project

1. **Clone the Repository**  
git clone https://github.com/adityanaithani1/Bibliotek-Library-Management-System.git

2. **Open in IDE (Eclipse/IntelliJ)**  
- Import as a Java project.
- Add JDBC library to classpath (`mysql-connector.jar` if using MySQL).

3. **Set up the Database**  
- Use the provided SQL script to create tables and initial data.
- Update DB credentials in `DatabaseUtil.java`.

4. **Run `Main.java`**  
- Launch the application and use default credentials to login.

---

## 🧪 Default Credentials

| Role   | Username | Password |
|--------|----------|----------|
| Admin  | admin    | admin123 |
| Student| student1 | pass123  |

> *(You can modify these in the database)*

---

## 📃 License

This project is open-source and available under the [MIT License](LICENSE).

---

🤝 Contribution Guidelines
--
Contributions are welcome! 🚀 To contribute:

- Fork this repository.
- Create a feature branch.
- Commit your changes.
- Open a Pull Request with a brief description.<br>

You can also open issues for bugs or enhancement ideas.


