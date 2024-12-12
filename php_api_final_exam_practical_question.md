
## **Question: Develop a PHP API with CRUD Operations**

### **Objective:**
Develop a PHP-based project demonstrating the creation of RESTful APIs to perform CRUD operations on three different tables in a database. The process should be documented and submitted as a video showcasing the following:

### **Requirements:**

1. **Database Schema:**
   - Design a database with at least three tables. Example:
     - **Students**: (id, name, email, phone)
     - **Courses**: (id, course_name, description)
     - **Enrollments**: (id, student_id, course_id, enrollment_date)

2. **API Requirements:**
   - Create a total of **6 APIs**, ensuring at least **2 APIs per table**:
     - **Students Table**:
       1. Create a student (Insert).
       2. Retrieve all students (Read).
     - **Courses Table**:
       3. Create a course (Insert).
       4. Update a course description (Update).
     - **Enrollments Table**:
       5. Enroll a student in a course (Insert).
       6. Delete an enrollment (Delete).

3. **Project Structure**:
   - Use proper folder structure (`index.php`, `routes`, `models`, `controllers`, etc.).
   - Use `POST`, `GET`, `PUT`, and `DELETE` HTTP methods for API calls.
   - Include proper error handling (e.g., validation, missing parameters, server errors).

4. **Video Submission**:
   - Record a video of the following:
     - Database design explanation.
     - API development process.
     - Testing APIs using tools like Postman.
     - Brief explanation of how your code is organized.

---

## **Marking Criteria**

| **Criteria**                 | **Marks** | **Description**                                                                                      |
|-------------------------------|-----------|------------------------------------------------------------------------------------------------------|
| **Database Design**           | 10        | Clear and normalized database schema, relationships defined between tables, and correct data types. |
| **API Creation**              | 20        | Properly functioning APIs for CRUD operations with correct HTTP methods and error handling.          |
| **Code Organization**         | 5         | Logical folder structure, modular code, and appropriate use of MVC pattern or structured approach.   |
| **Video Submission**          | 10        | Clear explanation of the database, API development, testing process, and demonstration.             |
| **Error Handling and Testing**| 5         | Proper error handling (validation, 404 handling) and thorough testing in Postman or similar tools.  |

---

### **Mark Allocation for APIs (20 Marks)**

| **API**                  | **Marks** | **Details**                                                                                          |
|--------------------------|-----------|------------------------------------------------------------------------------------------------------|
| **Create Student**       | 4         | Correctly adds a student to the database and handles errors such as duplicate entries.              |
| **Retrieve Students**    | 3         | Successfully retrieves a list of students in JSON format.                                           |
| **Create Course**        | 4         | Adds a course to the database and validates input data.                                             |
| **Update Course**        | 3         | Updates the description of a course and returns success/failure response.                           |
| **Enroll Student**       | 4         | Handles the enrollment of a student in a course, ensuring valid foreign key references.             |
| **Delete Enrollment**    | 2         | Deletes an enrollment by ID and confirms success or error.                                          |

---

### **Submission Guidelines:**
1. **Code Files**:
   - Submit a Github URL of your project in Student Portal, including all PHP files, database schema, and README instructions for setting up the project.
  

2. **Video**:
   - The video should not exceed **10 minutes** and must cover:
     - Database explanation.
     - API creation and folder structure.
     - Testing each API in Postman.

3. **Deadline**:
   - Submission is due by **2 Hours & 30 Minutes, Dt. 12/12/2022**.
