# 📝 Fullstack Todo List Application

This is a modern fullstack Todo List application built with **Spring Boot**, **Spring Security JWT**, **Angular**, and **MySQL**. It provides a seamless experience for users to manage tasks securely and efficiently.

---

## 🚀 Features

- 🔐 **Authentication & Authorization**  
  Secure user login with **JWT-based authentication** powered by Spring Security.

- ✅ **Task Management (CRUD)**  
  Add, update, and delete tasks with real-time feedback.

- 📧 **Email Notifications**  
  Sends emails using **Thymeleaf templates**.

- 🗂️ **Task Categorization**  
  Easily distinguish between **completed** and **pending** tasks.

- 🌐 **Single Page Application**  
  Intuitive UI built with **Angular 17**.

- 💾 **Data Persistence**  
  All data is stored securely in a **MySQL** database.

---

## 🧠 Concepts Covered

### 🔷 Angular Concepts
- Dependency Injection  
- Observables & Subscribers  
- HTTP Client  
- OnInit Lifecycle Hook  
- Component Data Binding  
- Parent and Child Components  
- Component Interaction (`@Input`)  
- Event Binding (`(event)`)  
- Property Binding (`[property]`)  
- Template Reference Variables (`#ref`)  
- `*ngFor`, `ngClass` Directives  
- RxJS Operators  
- Angular CLI Commands  
- TypeScript Best Practices  

### ☕ Spring Boot Concepts
- Spring Security (JWT Authentication)  
- Spring Data JPA & Hibernate  
- Java Persistence API (JPA)  
- Spring Web (REST APIs)  
- Dependency Injection  
- Service Layer Architecture  
- HTTP Methods (GET, POST, PUT, DELETE)  
- `@PathVariable`, `@RequestBody`  
- Exception Handling  
- `CorsConfiguration` for CORS setup  
- Custom Security Configuration  

---

## 🛠️ Technologies Used

- **Backend:** Spring Boot 3, Spring Security 6, JWT, Thymeleaf  
- **Frontend:** Angular 17 (TypeScript)  
- **Database:** MySQL  

---

## ⚙️ Installation

### 1. Clone the repository
```bash
git clone <repo-url>
```

### 2. Run the Backend
```bash
cd todo-backend
./mvnw spring-boot:run
```

### 3. Run the Frontend
Open a new terminal:
```bash
cd ../todo-frontend
npm install
ng serve
```

---

## 📱 Usage

Visit [http://localhost:4200](http://localhost:4200) in your browser.

- Log in or register.
- Start managing your tasks.
- Use the interface to add, edit, complete, or delete tasks.
