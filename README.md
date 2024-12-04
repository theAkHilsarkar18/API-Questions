## **1. User Management System API**
**Question:**  
Create a RESTful API for managing users with CRUD operations. The `User` table should have the following fields:  
- `id` (Primary Key)  
- `name`  
- `email` (unique)  
- `password` (hashed)  
- `created_at` and `updated_at`  

**Requirements:**  
- Implement endpoints for creating, reading, updating, and deleting users.  
- Use JSON for request and response payloads.  
- Passwords must be securely hashed.

---

## **2. Product Inventory Management API**
**Question:**  
Create a RESTful API to manage a product inventory. The `Product` table should have:  
- `id` (Primary Key)  
- `name`  
- `description`  
- `price`  
- `stock`  

Implement CRUD operations and ensure that stock updates are properly handled.


---

## **3. Task Management System API**
**Question:**  
Build a RESTful API for a task management system. The `Task` table should have:  
- `id` (Primary Key)  
- `title`  
- `description`  
- `status` (Pending, In Progress, Completed)  
- `due_date`

---

## **4. Order Management API**
**Question:**  
Create an API for managing orders and customers. The database should have two tables: `Order` and `Customer`.  
- Implement CRUD operations for both entities.  
- Ensure orders can only be created for existing customers.

---

## **5. Blog Management API**
**Question:**  
Develop a RESTful API to manage blog posts and comments. The `Post` table should have:  
- `id` (Primary Key)  
- `title`  
- `content`  
- `author`  
- `created_at`

The `Comment` table should have:  
- `id`  
- `post_id`  
- `commenter`  
- `comment_text`

---

## **6. Employee Management API**
**Question:**  
Create an API to manage employees and departments. The `Employee` table should include:  
- `id`  
- `name`  
- `email`  
- `department_id`  

The `Department` table should include:  
- `id`  
- `name`

---

## **7. E-Commerce Cart API**
**Question:**  
Develop an API to handle shopping cart operations. The `Cart` should support:  
- Adding products to a cart  
- Viewing the cart contents  
- Updating product quantities  
- Deleting items from the cart  

---

## **8. Event Management API**
**Question:**  
Build a RESTful API for managing events and participants. The `Event` table should have:  
- `id`  
- `title`  
- `description`  
- `event_date`

The `Participant` table should include:  
- `id`  
- `name`  
- `email`  
- `event_id`

---

## **9. Library Management API**
**Question:**  
Create a REST API for managing books and borrowers.  
- Implement CRUD operations for books and borrowers.  
- Ensure that a borrower can only borrow a book if it is available.

---

## **10. Feedback System API**
**Question:**  
Develop a RESTful API for collecting user feedback on various products. The `Feedback` table should have:  
- `id`  
- `user_id`  
- `product_id`  
- `rating`  
- `comments`

---

## **11. Authentication & Authorization API**
**Question:**  
Create a RESTful API with user authentication (login, register) and role-based access control (RBAC).  
- Implement JWT (JSON Web Token) for secure authentication.  
- Provide role-based access for different API endpoints.

---

## **12. File Upload & Management API**
**Question:**  
Develop a RESTful API to upload, retrieve, and delete files.  
- Implement file validation (size, type).  
- Store file metadata in the database.

---

## **13. Social Media API**
**Question:**  
Create a RESTful API for a simple social media platform that allows users to:  
- Create posts  
- Like or comment on posts  
- Retrieve posts and their associated comments and likes

---

## **Marking Criteria (Out of 20 Marks)**

### **1. Code Structure & Readability (5 Marks)**
- **2 Marks** for following PSR (PHP Standard Recommendations).  
- **1 Mark** for proper indentation and clean code.  
- **2 Marks** for using meaningful variable and function names.

---

### **2. Database Design (3 Marks)**  
- **1 Mark** for designing normalized tables.  
- **1 Mark** for using appropriate primary and foreign keys.  
- **1 Mark** for creating necessary relationships between tables.

---

### **3. CRUD Operations (6 Marks)**  
- **1 Mark** for implementing Create (POST).  
- **1 Mark** for implementing Read (GET).  
- **1 Mark** for implementing Update (PUT/PATCH).  
- **1 Mark** for implementing Delete (DELETE).  
- **2 Marks** for handling database operations securely (prepared statements/ORM).

---

### **4. Security (3 Marks)**  
- **1 Mark** for validating and sanitizing input.  
- **1 Mark** for using secure password hashing (`password_hash` or equivalent).  
- **1 Mark** for implementing authentication/authorization (if required).

---

### **5. API Response & Error Handling (3 Marks)**  
- **1 Mark** for using proper HTTP status codes.  
- **1 Mark** for returning meaningful error messages.  
- **1 Mark** for handling edge cases and validation errors.
