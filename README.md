# **Ecommerce Web Application**  

## **📌 Overview**  
This **Spring Boot-based eCommerce web application** is a robust platform designed to facilitate seamless product browsing, purchasing, and inventory management. It incorporates advanced features such as **JWT authentication, role-based access control, product and category management, secure file uploads, and efficient data retrieval through pagination and sorting**. The application is built with scalability and security in mind, ensuring a smooth user experience for administrators, sellers, and customers alike.

## **🚀 Key Features**  
- **User Authentication & Authorization:**  
  - JWT-based authentication for secure user login.  
  - Role-based access control (Admin, Seller, User) to ensure proper authorization.  
- **Product & Category Management:**  
  - Full CRUD (Create, Read, Update, Delete) operations for products and categories.  
  - Admin and Seller roles can manage inventory effectively.  
- **Efficient Data Retrieval:**  
  - Pagination and sorting for optimized product listing.  
- **Secure File Uploads:**  
  - Upload and manage product images securely.  
- **Exception Handling:**  
  - Centralized error management for consistent and user-friendly error responses.  
- **Spring Security Integration:**  
  - Robust security implementation to protect sensitive data and endpoints.  

## **🛠️ Technology Stack**  
- **Backend:**  
  - Spring Boot, Spring Security, JWT, Hibernate, JPA  
- **Database:**  
  - MySQL for reliable data storage and management.  
- **Security:**  
  - JWT-based authentication and role-based authorization.  
- **Tools:**  
  - Postman for API testing and Swagger for API documentation.  

## **🔑 Roles and Permissions**  
- **Admin:**  
  - Full access to manage products and categories (add, update, delete).  
- **Seller:**  
  - Manage their own products (add, update, delete).  
- **User:**  
  - Browse products, view details, and make purchases.  

## **🛠️ Installation and Setup**  
1. **Clone the Repository:**  
   ```bash
   git clone https://github.com/SaumyaVerma20/Ecommerce.git
   cd Ecommerce
   ```

2. **Configure MySQL Database:**  
   - Update the `application.properties` file with your MySQL database credentials.  

3. **Run the Application:**  
   ```bash
   mvn spring-boot:run
   ```

4. **Access the Application:**  
   - Use Postman or Swagger UI to interact with the API endpoints.  

## **🌐 API Endpoints**  
| **Method** | **Endpoint**               | **Description**                              | **Access**       |  
|------------|----------------------------|----------------------------------------------|------------------|  
| POST       | `/api/auth/signup`         | Register a new user.                         | Public           |  
| POST       | `/api/auth/login`          | Authenticate user and generate JWT token.    | Public           |  
| GET        | `/api/products`            | Retrieve all products with pagination.       | Public           |  
| POST       | `/api/products`            | Add a new product.                           | Admin, Seller    |  
| PUT        | `/api/products/{id}`       | Update product details.                      | Admin, Seller    |  
| DELETE     | `/api/products/{id}`       | Delete a product.                            | Admin, Seller    |  

## **🔧 Future Enhancements**  
- **OAuth2 Integration:**  
  - Enable login via Google, Facebook, and GitHub for enhanced user convenience.  
- **Payment Gateway Integration:**  
  - Seamless payment processing for a complete eCommerce experience.  
- **Microservices Architecture:**  
  - Transition to a microservices-based architecture for improved scalability and maintainability.  

This project demonstrates my ability to design and implement a secure, scalable, and feature-rich eCommerce application using modern technologies and best practices. It highlights my expertise in Spring Boot, Spring Security, RESTful APIs, and database management, making it a strong addition to my professional portfolio.
