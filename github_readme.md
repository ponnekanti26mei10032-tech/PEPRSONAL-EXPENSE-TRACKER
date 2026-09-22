# Personal Expense Tracker

## Project Overview

**Personal Expense Tracker** is a Python-based application developed to help users record, organize, and monitor their daily expenses in a simple and efficient way. Managing expenses manually can be difficult when there are many transactions, so this application provides a basic digital solution for maintaining expense records.

The application allows users to add new expenses by entering the amount, category, and description. Users can also view all recorded expenses, calculate total spending, check category-wise expenditure, search for expenses based on category, and delete unwanted records.

The project uses JSON file storage to save expense information. This allows the data to remain available even after the program is closed and restarted.

---

## Objectives

The main objectives of the Personal Expense Tracker are:
- To provide a simple system for recording daily expenses.
- To organize expenses according to different categories.
- To calculate the total amount spent by the user.
- To display category-wise spending information.
- To provide an option to search for expenses.
- To allow users to delete unwanted expense records.
- To store expense information permanently using a JSON file.
- To demonstrate practical implementation of Python programming concepts.

---

## Features

### 1. Add Expense
Users can add a new expense by entering the amount, category, and description. The application automatically assigns a unique ID and records the current date.

### 2. View All Expenses
Users can view all saved expense records in a structured table containing the expense ID, amount, category, description, and date.

### 3. Expense Summary
The application calculates the total amount spent and displays the total number of expense records.

### 4. Category-wise Spending
Expenses are grouped according to their categories. This helps users understand where most of their money is being spent.

### 5. Search by Category
Users can search for expenses by entering a category such as Food, Travel, Shopping, Bills, or Other.

### 6. Delete Expense
Users can remove an existing expense by entering its unique expense ID.

### 7. Data Storage
All expense information is stored in a JSON file. This provides simple and persistent data storage without requiring an external database.

---

## Technologies Used

The project is developed using the following technologies and concepts:
- **Python 3** – Main programming language
- **JSON** – Used for storing expense data
- **File Handling** – Used to read and write expense information
- **Date and Time Module** – Used to record expense dates
- **Functions** – Used to organize the program into reusable sections
- **Lists and Dictionaries** – Used to manage expense records
- **Exception Handling** – Used for handling invalid user input

---

## Project Structure

```text
Personal-Expense-Tracker/
│
├── main.py
├── expenses.json
└── README.md
```

### File Descriptions

- **`main.py`**: This is the main Python program containing the application logic, menu system, expense management functions, calculations, and input validation.
- **`expenses.json`**: This file stores all expense records in JSON format. The file is automatically updated whenever an expense is added or deleted.
- **`README.md`**: This file contains information about the project, its features, technologies, usage instructions, and learning outcomes.

---

## How the Application Works

1. When the program starts, the user is presented with a menu containing different options.
2. The user can select an option based on the required operation.
3. For example, when the user selects **Add Expense**, the application asks for the expense amount, category, and description. After receiving the details, the application generates a unique ID and records the current date. The information is then stored in the JSON file.
4. When the user selects **View All Expenses**, all stored records are displayed in a table format.
5. The **Expense Summary** option calculates the total amount spent and displays category-wise spending.
6. The **Search by Category** option allows users to find expenses belonging to a particular category.
7. The **Delete Expense** option allows users to remove an expense record using its ID.

---

## Sample Expense Categories

The application can be used to record different types of expenses, such as:
- Food 
- Travel 
- Shopping 
- Bills 
- Education 
- Entertainment 
- Medical 
- Other 

*Users can enter categories according to their requirements.*

---

## Sample Output

```text
=========================================
        PERSONAL EXPENSE TRACKER
=========================================
1. Add Expense
2. View All Expenses
3. Expense Summary
4. Search by Category
5. Delete Expense
6. Exit

Enter your choice:
```

### Example Expense Records

| ID | Amount | Category | Description | Date |
| :--- | :--- | :--- | :--- | :--- |
| **1** | 250.00 | Food | Lunch | 2026-09-22 |
| **2** | 500.00 | Travel | Bus Ticket | 2026-09-22 |
| **3** | 1200.00 | Shopping | Clothing | 2026-09-22 |

---

## Data Storage

The application uses a JSON file named `expenses.json` to store expense records.

**Example structure:**
```json
[
    {
        "id": 1,
        "amount": 250.0,
        "category": "Food",
        "description": "Lunch",
        "date": "2026-09-22"
    }
]
```

JSON makes the stored data easy to read, update, and manage using Python.

---

## Installation and Requirements

To run this project, the following requirements are needed:
- **Python 3.x**
- Any code editor such as **Visual Studio Code**, **IDLE**, or **PyCharm**
- **Command Prompt** or **Terminal**

> **Note:** No external Python libraries are required because the project uses Python's built-in modules.

---

## How to Run the Project

### Step 1: Install Python
Download and install Python 3 from the official Python website.

### Step 2: Download the Project
Clone the repository or download the project files.

### Step 3: Open the Project Folder
Open Command Prompt or Terminal inside the project folder.

### Step 4: Run the Application
Use the following command:
```bash
python main.py
```

### Step 5: Use the Menu
Select the required option and follow the instructions displayed by the application.

---

## Advantages

- Simple and easy to use.
- Helps maintain daily expense records.
- Reduces manual calculation.
- Provides automatic total spending calculation.
- Displays category-wise spending.
- Provides search functionality.
- Allows deletion of unwanted records.
- Stores data permanently using JSON.
- Does not require an external database.
- Uses only standard Python modules.

---

## Limitations

The current version is a console-based application and does not include a graphical user interface. It is designed mainly for basic personal expense tracking and uses a local JSON file instead of a database.

---

## Future Enhancements

The project can be improved in the future by adding:
- Graphical User Interface using **Tkinter**.
- Monthly and yearly expense reports.
- Budget planning and budget alerts.
- Income and savings tracking.
- Graphs and charts for expense analysis.
- Export reports to Excel or PDF.
- **SQLite** or **MySQL** database integration.
- User login and authentication.
- Date-based expense filtering.
- Monthly spending comparisons.

---

## Learning Outcomes

This project provides practical experience with several Python programming concepts, including:
- Variables and data types
- Functions
- Conditional statements
- Loops
- Lists and Dictionaries
- User input validation
- Exception handling
- File handling
- JSON data storage
- Date and time operations
- Data processing and calculations
- Menu-driven application development

---

## Conclusion

The **Personal Expense Tracker** is a simple and useful Python application designed to help users maintain their daily expense records. It provides important features such as adding, viewing, searching, summarizing, and deleting expenses.

The project demonstrates how Python programming concepts can be combined to create a practical real-world application. The use of JSON file storage makes the application simple while allowing expense data to be maintained between different program executions.

Overall, this project provides a strong practical demonstration of Python fundamentals, file handling, data management, and problem-solving.

---

## Author

- **Name:** P. Hema Sanjana
- **Register Number:** 26MEI10032
- **Project:** Personal Expense Tracker
- **Programming Language:** Python