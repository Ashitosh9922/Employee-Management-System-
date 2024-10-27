# Employee Management System (Backend)

## Overview

The Employee Management System is a backend application designed to manage employee records through basic Create, Read, Update, and Delete (CRUD) operations. This project is built using Django and provides a simple web interface to manage employee data.

## Features

- **Create Employee**: Add new employee records through a web form.
- **Read Employees**: View a list of all employees and their details.
- **Update Employee**: Edit existing employee information through a form.
- **Delete Employee**: Remove employee records from the system.

## Technologies Used

- Python
- Django
- SQLite (or any database of your choice)

## Installation

### Prerequisites

- Python 3.x
- pip (Python package installer)

### Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/Employee-Management-System.git
   cd Employee-Management-System
   ```

2. **Create a Virtual Environment**

   ```bash
   python -m venv venv
   ```

3. **Activate the Virtual Environment**

   - For Windows:

     ```bash
     venv\Scripts\activate
     ```

   - For macOS/Linux:

     ```bash
     source venv/bin/activate
     ```

4. **Install Required Packages**

   ```bash
   pip install -r requirements.txt
   ```

5. **Run Migrations**

   ```bash
   python manage.py migrate
   ```

6. **Run the Development Server**

   ```bash
   python manage.py runserver
   ```

7. **Access the Application**

   Open your browser and go to `http://127.0.0.1:8000/` to interact with the Employee Management System.

## Functionality

### Create Employee

- Navigate to the "Add Employee" page to fill out the form with employee details.

### Read Employees

- The homepage will display a list of all employees, including their names and roles.

### Update Employee

- Click on an employee's name to view their details, where you can update their information.

### Delete Employee

- On the employee detail page, there will be an option to delete the employee record.


## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request.

