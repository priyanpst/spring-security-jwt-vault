# 🔐 JWT Security Vault

A stateless authentication service providing secure access control for Fintech applications.

### 🚀 Implementation Details:
- **Spring Security 6:** Implemented with the latest `SecurityFilterChain` bean configuration (avoiding deprecated classes).
- **Stateless Auth:** Uses JSON Web Tokens (JWT) to manage user sessions, removing the need for server-side state.
- **Data Persistence:** User credentials and roles are stored in **MySQL** with **BCrypt** hashing to ensure data security.

### 🛠 Stack:
- Java 21, Spring Boot 3.3, Spring Security 6, JJWT, MySQL, Lombok.
