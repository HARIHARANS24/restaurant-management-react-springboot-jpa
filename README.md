# 🍽️ Restaurant Management System

A full-stack Restaurant Management application that allows administrators and staff to manage menu items, table reservations, orders, and customer information efficiently. Built using React for the frontend and Spring Boot with JPA and MySQL for the backend, the app is optimized for responsiveness and smooth data interaction.
## 📚 Overview

This system is designed for restaurant owners or staff to: 
    
- Manage menu items (CRUD)         
- Handle table bookings and customer information               
- Track and update order statuses           
- Maintain all data in a structured MySQL database          
- Use a clean, responsive UI for both desktop and mobile views       
       
  
### Key Features    
- 🍽️ **Menu Management**: Add, edit, and manage food items with categories and pricing   
- 📅 **Table Booking**: Handle customer reservations with real-time availability
- 📦 **Order Management**: Track orders from placement to delivery
- 👥 **Customer Management**: Maintain customer profiles and order history
- 📊 **Admin Dashboard**: Monitor restaurant performance and manage staff
- 🔒 **Secure Authentication**: Role-based access control for staff and admin

## 🛠️ Tech Stack

### Frontend
- React.js - Modern UI library
- React Router - Page navigation
- Axios - REST API integration
- Material UI - UI styling
- Context API - State management

### Backend
- Spring Boot - Java-based REST API framework
- Spring Data JPA - ORM for database operations
- MySQL - Relational database for persistent storage
- Lombok - Boilerplate reduction for entities and services
- Spring Security - User roles and authentication

## 📁 Project Structure

### Backend Structure
```
Directory structure:
└── hariharans24-restaurant-management-react-springboot-jpa/
    ├── README.md
    ├── LICENSE.txt
    ├── Backend/
    │   ├── mvnw
    │   ├── mvnw.cmd
    │   ├── pom.xml
    │   └── src/
    │       ├── main/
    │       │   ├── java/
    │       │   │   └── com/
    │       │   │       └── example/
    │       │   │           ├── Controller/
    │       │   │           │   └── RestaurantController.java
    │       │   │           ├── Demo/
    │       │   │           │   └── RestaurantApplication.java
    │       │   │           ├── Exception/
    │       │   │           │   └── RestaurantNotFoundException.java
    │       │   │           ├── Model/
    │       │   │           │   └── Restaurant.java
    │       │   │           ├── Repository/
    │       │   │           │   └── RestaurantRepository.java
    │       │   │           └── Service/
    │       │   │               └── RestaurantService.java
    │       │   └── resources/
    │       │       └── application.properties
    │       └── test/
    │           └── java/
    │               └── com/
    │                   └── example/
    │                       └── demo/
    │                           └── RestaurantApplicationTests.java
    └── Frontend/
        ├── package.json
        ├── public/
        │   ├── ab.avif
        │   ├── as.avif
        │   ├── bb.avif
        │   ├── index.html
        │   ├── manifest.json
        │   └── robots.txt
        └── src/
            ├── App.css
            ├── App.js
            ├── App.test.js
            ├── index.css
            ├── index.js
            ├── reportWebVitals.js
            ├── setupTests.js
            ├── layout/
            │   └── Navbar.js
            ├── pages/
            │   ├── Home.css
            │   ├── Home.js
            │   ├── login.css
            │   ├── login.js
            │   ├── Signup.css
            │   └── Signup.js
            └── users/
                ├── AddUser.css
                ├── AddUser.js
                ├── EditUser.css
                ├── EditUser.js
                ├── ViewUser.css
                └── ViewUser.js
```

## 🚀 Getting Started

### Prerequisites
- Java JDK 17 or higher
- Node.js and npm
- MySQL Server
- Maven

### Backend Setup
1. Navigate to the Backend directory
2. Configure MySQL database in `application.properties`
3. Run `mvn spring-boot:run`

### Frontend Setup
1. Navigate to the Frontend directory
2. Run `npm install`
3. Run `npm start`

## 🤝 Contributing

We welcome contributions to improve the Restaurant Management System! Here's how you can contribute:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE.txt](LICENSE.txt) file for details.

## 👥 Authors

- **HARIHARANS24** - *Initial work* - [GitHub Profile](https://github.com/HARIHARANS24)

## 🙏 Acknowledgments

- Thanks to all contributors who have helped shape this project
- Special thanks to the open-source community for their invaluable tools and libraries



