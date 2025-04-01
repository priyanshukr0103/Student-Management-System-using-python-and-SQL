# Student-Management-System-using-python-and-SQL
This Student Management System, built with Python and SQL, enables efficient management of student records. Users can add, update, delete, and view details like name, roll number, course, and grades. It connects to an SQL database (MySQL/PostgreSQL/SQLite) for secure storage and retrieval, ensuring data integrity and easy access.

Key Features:

✅ Student Registration – Add new students with details like name, contact, email, roll number, branch, teacher ID, and course ID.

✅ View Student List – Display all registered students in a structured table using Tkinter’s Treeview.

✅ Record Deletion – Easily remove unnecessary student records with a single click.

✅ Input Validation & Notifications – Ensures mandatory fields are filled and provides alerts for successful actions or errors.

✅ Secure Data Storage – Stores student records in a MySQL database for reliable and organized management.

Technologies Used:
Python – Primary programming language.
Tkinter – GUI toolkit for user-friendly interaction.
mysql-connector-python – Library for connecting Python with MySQL.
MySQL – Database system for structured data storage

![image](https://github.com/user-attachments/assets/9380e4ba-d9ea-403c-b5dd-c8c627e9156e)


How to Run

1️⃣ Install Dependencies
Clone the repository:
```
git clone https://github.com/yourusername/student-management-system.git  
cd student-management-system
```

Install MySQL connector:

```
pip install mysql-connector-python
```

2️⃣ Set Up MySQL Database
Install and start MySQL on your system.
Open the MySQL shell and create a new database:

```
CREATE DATABASE student_management_db;
```
Update the host, user, password, and database name in the Python script accordingly.

3️⃣ Run the Application
Execute the following command to start the program:


```
python your_file_name.py  
```

🔥 Future Enhancements

🔹 Edit & Update Student Records

🔹 Search & Filter Functionality

🔹 Improved UI with Tkinter Styles
