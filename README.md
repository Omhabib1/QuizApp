# Quiz Application 🎯

A full-stack **Quiz Platform** built using **React.js**, **Spring Boot**, **Hibernate**, and **MySQL**.  
It allows users to take quizzes, manage categories, view results, and authenticate securely using JWT-based authentication.

---

## 🧩 Features

### Frontend (React.js)
- Interactive and responsive UI for quiz-taking
- JWT token-based authentication
- Dashboard for users and quiz management
- Timer-based quiz functionality
- REST API integration with the backend

### Backend (Spring Boot)
- RESTful APIs for user, quiz, category, and question management
- Spring Security with JWT authentication
- MySQL database integration via Hibernate ORM
- Layered architecture (Controller → Service → Repository)
- Role-based access (Admin/User)

---

## 🏗️ Project Structure

```
QuizApp/
├── exam-portal-backend/     # Spring Boot backend
│   ├── src/
│   ├── pom.xml
│   └── application.properties
└── exam-portal-frontend/    # React frontend
    ├── src/
    ├── package.json
    └── public/
```

---

## ⚙️ Tech Stack

| Layer | Technology |
|-------|-------------|
| Frontend | React.js, Axios, CSS |
| Backend | Spring Boot, Spring Security, Hibernate |
| Database | MySQL |
| Authentication | JWT (JSON Web Token) |
| Build Tools | Maven, npm |

---

## 🚀 Getting Started

### Prerequisites
Make sure you have installed:
- **Node.js** (v16 or above)
- **npm** or **yarn**
- **Java 17+**
- **Maven 3.8+**
- **MySQL Server**

---

## 🖥️ Backend Setup (Spring Boot)

1. Navigate to the backend folder:
   ```bash
   cd exam-portal-backend
   ```

2. Configure database credentials in `src/main/resources/application.properties`:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/quizdb
   spring.datasource.username=your_username
   spring.datasource.password=your_password
   spring.jpa.hibernate.ddl-auto=update
   jwt.secret=your_secret_key
   ```

3. Build and run the backend:
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```

4. The backend will start on:
   ```
   http://localhost:8080
   ```

---

## 🌐 Frontend Setup (React.js)

1. Navigate to the frontend folder:
   ```bash
   cd exam-portal-frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file (optional) to configure API URL:
   ```env
   REACT_APP_API_BASE_URL=http://localhost:8080
   ```

4. Start the development server:
   ```bash
   npm start
   ```

5. Access the frontend on:
   ```
   http://localhost:3000
   ```

---

## 🧠 Key Modules

- **User Authentication:** Login & Signup using JWT
- **Quiz Management:** Create, update, delete, and list quizzes
- **Question Management:** Add questions dynamically
- **Results:** Store and display user quiz results

---

## 📸 Screenshots
_Add screenshots or demo GIFs here once available._

---

## 🧾 License
This project is open source and available under the [MIT License](LICENSE).

---

## 👨‍💻 Author
**Om A Habib**  
📧 [Omhabib1234@gmail.com](mailto:Omhabib1234@gmail.com)  
💼 [GitHub Profile](https://github.com/)
