#  Testes Unitários e Mocking em Spring Boot
### Disciplina: Aplicações de Arquitetura Web  
### Autor: Arthur Henrique Fernandes

---

## Objetivo

Desenvolver testes unitários para o controlador de usuários utilizando **JUnit 5** e **Mockito**, garantindo a confiabilidade das operações REST em um projeto Spring Boot.

---

## Tecnologias Utilizadas

- **Java 11+**
- **Spring Boot** (Web, Data JPA, DevTools)
- **MariaDB**
- **JUnit 5**
- **Mockito**

---

## 📁 Estrutura do Projeto

```bash
TesteUnitario-main/
│
├── src/
│   ├── main/
│   │   └── java/com/user/users/
│   │       ├── controller/
│   │       │   └── Usercontroller.java
│   │       ├── model/
│   │       │   └── User.java
│   │       ├── repository/
│   │       │   └── UserRepository.java
│   │       ├── services/
│   │       │   └── UserService.java
│   │       └── UsersApplication.java
│   │
│   └── test/
│       └── java/com/user/users/
│           ├── UserControllerTest.java
│           └── UsersApplicationTests.java
│
├── pom.xml
└── README.md
