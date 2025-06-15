# 💰 Expense Tracker (Spring MVC + Spring Boot)

A Java web application to track personal expenses using Spring Boot, Spring MVC, Thymeleaf, and H2 database.

---

## 🚀 Features

- Add new expenses
- View list of all expenses
- Delete expenses
- Filter by category and date (extendable)

---

## 🛠 Tech Stack

- Java 17+
- Spring Boot
- Spring MVC
- Thymeleaf (templating engine)
- Spring Data JPA (Hibernate)
- H2 in-memory database
- Maven

---

## 📂 Folder Structure

```
expense-tracker/
├── controller/      # Handles HTTP requests
├── model/           # Defines Expense entity
├── repository/      # Spring Data JPA interfaces
├── service/         # Business logic layer
├── templates/       # Thymeleaf views
├── static/          # Static resources (CSS, JS)
└── application.properties
```

---

## ⚙️ Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/expense-tracker-springmvc.git
cd expense-tracker-springmvc
```

2. Open in IntelliJ or VS Code (Java support required)

3. Run the application:
```bash
mvn spring-boot:run
```

4. Open your browser:
```
http://localhost:8080/expenses
```

---

## 🗃 Example Data

| Description | Amount | Category | Date       |
|-------------|--------|----------|------------|
| Groceries   | 50.00  | Food     | 2024-01-01 |
| Uber Ride   | 20.00  | Travel   | 2024-01-02 |

---

## ✅ Future Enhancements

- User authentication
- Expense filtering and charts
- MySQL/PostgreSQL database
- REST API version

---

## 📄 License

MIT License
