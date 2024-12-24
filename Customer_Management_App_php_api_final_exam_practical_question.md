Here’s a revised and simplified version of the question without foreign key references:

---

## **Question: Develop a PHP API with CRUD Operations**

### **Objective:**
Create a PHP-based project to demonstrate RESTful APIs for performing CRUD operations on three independent tables in a database. The process should be documented and submitted as a video showcasing your implementation.

---

### **Requirements:**

1. **Database Schema:**
   - Design a database with at least three independent tables. Example:
     - **Users**: (id, name, email, phone)
     - **Products**: (id, product_name, price)
     - **Orders**: (id, order_date, status)

2. **API Requirements:**
   - Create a total of **6 APIs**, with **2 APIs per table**:
     - **Users Table**:
       1. Add a new user (Insert).
       2. Retrieve all users (Read).
     - **Products Table**:
       3. Add a new product (Insert).
       4. Update a product price (Update).
     - **Orders Table**:
       5. Add a new order (Insert).
       6. Delete an order by ID (Delete).

3. **Project Structure:**
   - Use proper folder organization (`index.php`, `routes`, `models`, `controllers`, etc.).
   - Follow REST principles:
     - Use `POST`, `GET`, `PUT`, and `DELETE` methods.
     - Provide responses in JSON format.
   - Implement error handling (e.g., validation, missing parameters, server errors).

4. **Video Submission:**
   - Record a video showcasing:
     - Database structure and schema explanation.
     - Step-by-step API development.
     - Testing all APIs using Postman.
     - Explanation of the folder structure and code organization.

---

### **Marking Criteria**

| **Criteria**                 | **Marks** | **Description**                                                                                      |
|-------------------------------|-----------|------------------------------------------------------------------------------------------------------|
| **Database Design**           | 10        | Well-designed and normalized database schema with clear table structures and proper data types.     |
| **API Functionality**         | 20        | Fully functioning APIs for CRUD operations using correct HTTP methods and error handling.           |
| **Code Organization**         | 5         | Proper folder structure and modular, maintainable code.                                             |
| **Video Submission**          | 10        | Clear and concise explanation of the database, APIs, and testing process.                           |
| **Error Handling and Testing**| 5         | Effective error handling (e.g., validation, error codes) and comprehensive testing using Postman.   |

---

### **Mark Allocation for APIs (20 Marks)**

| **API**                  | **Marks** | **Details**                                                                                          |
|--------------------------|-----------|------------------------------------------------------------------------------------------------------|
| **Add User**             | 4         | Creates a new user and validates required fields (e.g., name, email).                               |
| **Get Users**            | 3         | Retrieves all users and presents them in JSON format.                                               |
| **Add Product**          | 4         | Adds a product with required fields (e.g., name, price) and handles errors.                         |
| **Update Product Price** | 3         | Updates the price of a product by ID and validates the input.                                       |
| **Add Order**            | 4         | Creates a new order with order details and ensures the data is saved correctly.                     |
| **Delete Order**         | 2         | Deletes an order by ID and confirms the operation with a success/error response.                    |

---

### **Submission Guidelines:**

1. **Code Files**:
   - Submit a GitHub URL of your project in the Student Portal, including:
     - All PHP code.
     - SQL script for creating the database and tables.
     - A `README.md` file with instructions to set up the project.

2. **Video Submission**:
   - The video should not exceed **10 minutes** and must cover:
     - Database schema and table design.
     - Explanation of API functionality and folder structure.
     - Testing of APIs in Postman.

3. **Deadline**:
   - Submission is due **within 2 hours and 30 minutes**.
