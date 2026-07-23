# E-Mart

E-Mart is a full-stack e-commerce web application developed as a CDAC major project. The application allows customers to browse products, manage their cart, place orders, and make payments. It also provides separate modules for administrators and sellers to manage products, orders, and users.

## Tech Stack

### Frontend
- React.js
- React Router
- Bootstrap 5
- Axios
- HTML, CSS, JavaScript

### Backend (Spring Boot)
- Java
- Spring Boot
- Spring Security
- Spring Data JPA
- Hibernate
- Maven

### Backend (.NET)
- ASP.NET Core Web API
- Entity Framework Core
- C#

### Database
- MySQL

## Project Structure

```
E-Mart/
│── frontend/          # React application
│── backend-spring/    # Spring Boot backend
│── backend-dotnet/    # ASP.NET Core backend
│── database/          # Database scripts
└── README.md
```

## Features

- User Registration & Login
- Product Management
- Category Management
- Shopping Cart
- Wishlist
- Checkout
- Online Payment
- Order Management
- Seller Dashboard
- Admin Dashboard
- Responsive UI

## Getting Started

### Clone the Repository

```bash
git clone <repository-url>
cd E-Mart
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

### Spring Boot Backend

```bash
cd backend-spring
mvn clean install
mvn spring-boot:run
```

### .NET Backend

```bash
cd backend-dotnet
dotnet restore
dotnet run
```

## Database Setup

1. Install MySQL.
2. Create a database.
3. Import the SQL script from the `database` folder.
4. Update the database configuration in the backend projects.
   

## License

This project is developed for educational purposes.
