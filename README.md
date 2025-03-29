Requirements for Building and Deploying a Simple API
To build and deploy a simple API with the specified endpoints, you will need to follow several steps. Below is a detailed breakdown of the requirements and tasks involved.
Choose Your Technology Stack
Programming Language: Select a programming language for your API development. Common choices include:

Python (with Flask or FastAPI)
Relational Database Management System (RDBMS): Choose an RDBMS to store your data. Popular options include:

MySQL
Set Up Your Development Environment
Install Required Software:

Install the chosen programming language runtime.
Install the necessary libraries or frameworks for building APIs.
Install the selected RDBMS and set up a database instance.
Create a Project Directory: Organize your project files in a dedicated directory.
Design Your Database Schema
Students Table:

Create a table named students with at least the following columns:
id: Primary key (integer).
name: Student’s name (string).
program: Enrolled program (string).
Subjects Table:

Create a table named subjects with at least the following columns:
id: Primary key (integer).
name: Subject name (string).
year: Academic year associated with the subject (integer).
Step 4: Populate Your Database
Insert Sample Data:
Add at least 10 student records into the students table.
Insert subjects related to the Software Engineering program spanning from Year 1 to Year 4 into the subjects table.
Step 5: Develop Your API Endpoints
Endpoint 1: /students

Implement a GET request handler for /students.
Query the database to retrieve all student records.
Format the response as JSON, including each student’s name and enrolled program.
Endpoint 2: /subjects
Add at least 10 student records into the students table.
Insert subjects related to the Software Engineering program spanning from Year 1 to Year 4 into the subjects table.
Step 5: Develop Your API Endpoints
Endpoint 1: /students

Implement a GET request handler for /students.
Query the database to retrieve all student records.
Format the response as JSON, including each student’s name and enrolled program.
Endpoint 2: /subjects
Conclusion
By following these steps, you will be able to successfully create and deploy an API that meets the specified requirements of returning student information and subjects related to Software Engineering programs.


