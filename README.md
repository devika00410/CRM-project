# CRM Backend System

A complete backend solution for Customer Relationship Management with secure authentication and RESTful APIs.

##  Features
- **JWT Authentication** - Secure user login system
- **Role-Based Access** - Admin and User permissions
- **Customer Management** - Full CRUD operations
- **Case Tracking** - Support case management
- **MongoDB Database** - NoSQL data storage
- **RESTful APIs** - Clean and structured endpoints

##  API Endpoints

###  Authentication
- `POST /api/auth/register` - Create new user account
- `POST /api/auth/login` - User login with JWT token
- `GET /api/auth/profile` - Get user profile

###  Customer Management
- `GET /api/customers` - Get all customers
- `POST /api/customers` - Add new customer
- `PATCH /api/customers/:id` - Update customer
- `DELETE /api/customers/:id` - Delete customer

###  Case Management
- `GET /api/cases` - Get all support cases
- `POST /api/cases` - Create new case
- `PATCH /api/cases/:id` - Update case status
- `DELETE /api/cases/:id` - Delete case

##  Security Features
- Password hashing with bcrypt
- JWT token authentication
- Role-based authorization
- Protected API routes

##  Testing
The system has been thoroughly tested with Postman:
-  User registration and login
-  JWT token authentication
-  Customer CRUD operations
-  Case CRUD operations
-  Role-based access control
-  Error handling scenarios
-  Password security verification

##  Assignment Requirements Met
1. **Project Structure** - Organized folder structure with proper separation of concerns
2. **JWT Authentication** - Secure login system with token-based authentication
3. **Database Design** - MongoDB collections for users, customers, and cases
4. **RESTful APIs** - Complete CRUD operations for all resources
5. **Error Handling** - Comprehensive error handling and validation

##  Database Collections
- **users** - User accounts and authentication
- **customers** - Customer information
- **cases** - Support cases and issues

##  Conclusion
This CRM backend system successfully demonstrates robust backend development practices with secure authentication, efficient data management, and well-structured APIs. All assignment requirements have been implemented including JWT authentication, role-based access control, and complete CRUD operations for customer and case management.


**Base URL:** `http://localhost:3000/api`  
**Authentication:** Add `Authorization: Bearer <token>` header to protected routes
