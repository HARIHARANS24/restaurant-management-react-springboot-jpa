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
Backend/
├── 📂 src/
│   ├── 📂 main/
│   │   ├── 📂 java/
│   │   │   └── 📂 com/
│   │   │       └── 📂 example/
│   │   │           ├── 📂 Controller/
│   │   │           │   ├── 📄 BookingController.java
│   │   │           │   ├── 📄 CustomerController.java
│   │   │           │   ├── 📄 MenuController.java
│   │   │           │   └── 📄 OrderController.java
│   │   │           ├── 📂 Model/
│   │   │           │   ├── 📄 Booking.java
│   │   │           │   ├── 📄 Customer.java
│   │   │           │   ├── 📄 Menu.java
│   │   │           │   └── 📄 Order.java
│   │   │           ├── 📂 Repository/
│   │   │           │   ├── 📄 BookingRepository.java
│   │   │           │   ├── 📄 CustomerRepository.java
│   │   │           │   ├── 📄 MenuRepository.java
│   │   │           │   └── 📄 OrderRepository.java
│   │   │           ├── 📂 Service/
│   │   │           │   ├── 📄 BookingService.java
│   │   │           │   ├── 📄 CustomerService.java
│   │   │           │   ├── 📄 MenuService.java
│   │   │           │   └── 📄 OrderService.java
│   │   │           ├── 📂 Exception/
│   │   │           │   └── 📄 ResourceNotFoundException.java
│   │   │           └── 📂 Demo/
│   │   │               └── 📄 RestaurantApplication.java
│   │   └── 📂 resources/
│   │       └── 📄 application.properties
│   └── 📂 test/
├── 📄 pom.xml
├── 📄 mvnw
└── 📄 mvnw.cmd
```

### Frontend Structure
```
Frontend/
├── 📂 src/
│   ├── 📂 pages/
│   │   ├── 📄 Home.js
│   │   ├── 📄 Home.css
│   │   ├── 📄 login.js
│   │   ├── 📄 login.css
│   │   ├── 📄 Signup.js
│   │   └── 📄 Signup.css
│   ├── 📂 layout/
│   │   └── 📄 Navbar.js
│   ├── 📂 users/
│   │   ├── 📄 AddUser.js
│   │   ├── 📄 AddUser.css
│   │   ├── 📄 EditUser.js
│   │   ├── 📄 EditUser.css
│   │   ├── 📄 ViewUser.js
│   │   └── 📄 ViewUser.css
│   ├── 📄 App.js
│   ├── 📄 App.css
│   ├── 📄 App.test.js
│   ├── 📄 index.js
│   ├── 📄 index.css
│   ├── 📄 logo.svg
│   ├── 📄 reportWebVitals.js
│   └── 📄 setupTests.js
├── 📂 public/
│   ├── 📄 index.html
│   ├── 📄 favicon.ico
│   └── 📄 manifest.json
└── 📄 package.json
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



