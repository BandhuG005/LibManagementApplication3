# 📚 Library Management Application

A comprehensive Library Management System designed to streamline library operations such as book management, member management, issue/return tracking, and inventory monitoring.

## 🚀 Features

### Book Management
- Add new books
- Update book information
- Delete books
- Search books by title, author, category, or ISBN
- View book availability

### Member Management
- Register library members
- Update member details
- Remove members
- Track member borrowing history

### Issue & Return Management
- Issue books to members
- Return books
- Due date tracking
- Fine calculation (if applicable)

### Dashboard
- Library statistics
- Available books count
- Issued books count
- Registered members overview

### Authentication & Authorization
- Secure login system
- Role-based access control
- Admin and User roles

---

## 🛠️ Technology Stack

### Backend
- Java
- Spring Boot
- Spring Data JPA
- Hibernate

### Frontend
- HTML
- CSS
- JavaScript
- Bootstrap

### Database
- MySQL

### Tools
- Maven
- Git
- GitHub

---

## 📂 Project Structure

```
LibManagementApplication3/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   ├── resources/
│   │   └── static/
│   │
│   └── test/
│
├── pom.xml
├── README.md
└── application.properties
```

---

## ⚙️ Installation

### Prerequisites

- Java 17+ (or project version)
- Maven
- MySQL
- Git

### Clone Repository

```bash
git clone https://github.com/BandhuG005/LibManagementApplication3.git
cd LibManagementApplication3
```

### Configure Database

Update the database settings in:

```properties
src/main/resources/application.properties
```

Example:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/library_db
spring.datasource.username=root
spring.datasource.password=password

spring.jpa.hibernate.ddl-auto=update
```

### Build Project

```bash
mvn clean install
```

### Run Application

```bash
mvn spring-boot:run
```

Application will start at:

```text
http://localhost:8080
```

---

## 📖 Usage

### Admin Functions

- Manage books
- Manage members
- View issued books
- Generate reports

### User Functions

- Search books
- View available inventory
- Borrow books
- Return books

---

## 📸 Screenshots

Add screenshots here:

### Login Page

![Login](screenshots/login.png)

### Dashboard

![Dashboard](screenshots/dashboard.png)

### Book Management

![Books](screenshots/books.png)

---

## 🧪 Testing

Run tests using:

```bash
mvn test
```

---

## 🔒 Security

- Password encryption
- Authentication system
- Role-based authorization

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Add feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Create a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Bandhu G**

GitHub: https://github.com/BandhuG005

---

## ⭐ Support

If you found this project useful, please consider giving it a star on GitHub.
