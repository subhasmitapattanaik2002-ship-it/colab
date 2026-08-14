# 🐍 Python Programming & OOP Practice

A structured collection of **Python programming practice notebooks** created using **Google Colab / Jupyter Notebook**. This repository documents my learning journey from Python fundamentals to collections and Object-Oriented Programming (OOP).

The repository contains practical examples, exercises, outputs, and problem-solving programs covering important Python concepts that are useful for software development, data analytics, and further learning in Data Science and Machine Learning.

---

## 📌 About This Repository

This repository was created to practice and strengthen my Python programming fundamentals through hands-on coding.

The notebooks cover:

* Python basics
* Variables and data types
* Input and output
* Type conversion
* Operators
* Strings and string methods
* Conditional statements
* Loops
* Lists
* Tuples
* Sets
* Dictionaries
* Instance methods
* Class methods
* Static methods
* Constructors
* Class variables
* Alternative constructors
* Basic problem solving

The repository is primarily intended as a **learning and practice repository**, with examples and exercises demonstrating how different Python concepts work.

---

## 🎯 Objectives

The main objectives of this repository are:

1. Build a strong foundation in Python.
2. Understand Python syntax and programming logic.
3. Practice problem-solving using Python.
4. Understand Python's built-in data structures.
5. Learn Object-Oriented Programming concepts.
6. Practice writing reusable Python code.
7. Understand the difference between instance, class, and static methods.
8. Develop programming skills required for advanced topics such as Data Analytics, Data Science, and Machine Learning.

---

# 🛠️ Technologies Used

| Technology           | Purpose                                            |
| -------------------- | -------------------------------------------------- |
| **Python 3**         | Main programming language                          |
| **Google Colab**     | Cloud-based environment used for running notebooks |
| **Jupyter Notebook** | Notebook format used for Python practice           |
| **Git**              | Version control                                    |
| **GitHub**           | Source-code hosting and repository management      |
| **Markdown**         | Documentation                                      |

### Python Concepts Used

The repository uses Python's built-in language features, including:

* Variables
* Data types
* Input/output
* Operators
* Type conversion
* Strings
* Conditional statements
* `for` loops
* `while` loops
* `break`
* Lists
* Tuples
* Sets
* Dictionaries
* Functions/methods
* Classes
* Objects
* Constructors
* Instance methods
* Class methods
* Static methods
* Class variables
* Basic exception/error demonstrations

### External Python Libraries

**No external Python libraries are required for the current notebooks.**

The examples primarily use Python's built-in features and functionality.

---

# 📂 Repository Structure

```text
colab/
│
├── README.md
│
├── first.ipynb
│
├── subha_.ipynb
│
├── task_by_shiv_sir_in_list.ipynb
│
└── 26_06_2026.ipynb
```

---

# 📓 Notebook Details

## 1. `first.ipynb`

This is the introductory Python notebook.

### Topics

* First Python program
* `print()`
* Basic Google Colab/Jupyter usage

### Example

```python
print("subha")
```

This notebook represents the beginning of the Python learning journey.

---

# 2. `subha_.ipynb`

This notebook contains practice programs covering Python fundamentals, strings, conditions, loops, and basic problem-solving.

### Topics Covered

### 🔹 Input and Output

* `input()`
* `print()`

Example:

```python
student_name = input("Enter student name: ")
print(student_name.upper())
```

### 🔹 Strings

Practice includes:

* `upper()`
* `lower()`
* `title()`
* `len()`
* indexing
* `count()`
* `replace()`
* `endswith()`
* `isdigit()`
* `isalpha()`
* `split()`

### 🔹 Conditional Statements

Practice includes:

```python
if
elif
else
```

Examples include:

* Voting eligibility
* Even/odd checking
* Finding the greater number
* Grading systems
* Password validation
* Login checking
* Calculator operations
* Leap-year checking

### 🔹 Loops

Practice includes:

* `for`
* `while`
* `break`
* nested loops
* pattern printing

Example:

```text
*
**
***
****
*****
******
```

---

# 3. `task_by_shiv_sir_in_list.ipynb`

This notebook contains a collection of practical exercises focused on Python's major collection data types.

### 📋 Topics Covered

* Lists
* Tuples
* Sets
* Dictionaries
* Indexing
* Updating data
* Adding elements
* Removing elements
* Searching
* Iteration
* Basic collection operations

---

## 🔹 Lists

Examples include:

```python
students = ["subha", "kutun", "kiran", "swati", "Rohan"]
```

Operations practiced include:

```python
append()
insert()
pop()
```

Other concepts:

* List indexing
* Negative indexing
* Membership checking
* Iterating through lists
* Building lists using loops

---

## 🔹 Tuples

Examples include:

```python
numbers = (10, 20, 30, 40, 50)
```

Practice includes:

* Tuple indexing
* Negative indexing
* `count()`
* `max()`
* `min()`
* `len()`
* Tuple immutability

Example of tuple immutability:

```python
t = (10, 20, 30, 40)

t[0] = 100
```

This demonstrates that tuple elements cannot be changed after creation.

---

## 🔹 Sets

Practice includes:

* Creating sets
* Adding elements
* Removing elements
* Removing duplicate values
* Union
* Intersection

Examples:

```python
A | B
```

for union and:

```python
A & B
```

for intersection.

---

## 🔹 Dictionaries

Practice includes:

* Creating dictionaries
* Accessing values
* Adding key-value pairs
* Updating values
* Removing values
* `keys()`
* `values()`
* `items()`
* Dictionary iteration
* Searching for values

Example:

```python
student = {
    "name": "Situ",
    "age": 24
}
```

---

# 4. `26_06_2026.ipynb`

This is the main **Object-Oriented Programming (OOP)** practice notebook.

It contains practical examples demonstrating different types of methods and class behavior.

---

## 🔹 Classes and Objects

Example:

```python
class Student:

    def __init__(self, name, age):
        self.name = name
        self.age = age

    def display(self):
        print("Name:", self.name)
        print("Age:", self.age)
```

Objects can then be created:

```python
s1 = Student("Kiran", 20)
s2 = Student("Jitu", 22)
```

---

## 🔹 Constructor

The notebooks demonstrate the use of:

```python
__init__()
```

The constructor is used to initialize object data when an object is created.

---

## 🔹 Instance Methods

Instance methods operate on individual objects.

Example:

```python
def display(self):
    print(self.name)
```

Practice examples include classes such as:

* Student
* Employee
* Car
* Mobile
* Bank Account
* Laptop

---

## 🔹 Class Methods

The repository also demonstrates:

```python
@classmethod
```

Class methods operate using the class itself through `cls`.

Example:

```python
@classmethod
def change_company(cls, new_company):
    cls.company = new_company
```

The notebook also demonstrates class methods for:

* Changing shared class information
* Counting objects
* Alternative constructors
* Updating shared values

---

## 🔹 Class Variables

Example:

```python
class Car:

    total_cars = 0

    def __init__(self):
        Car.total_cars += 1
```

This demonstrates how a variable can be shared by all objects of a class.

---

## 🔹 Alternative Constructor

The repository demonstrates creating objects using a class method.

Example:

```python
@classmethod
def from_string(cls, data):
    name, age = data.split(",")
    return cls(name, int(age))
```

This allows an object to be created from a string representation.

---

## 🔹 Static Methods

The repository also demonstrates:

```python
@staticmethod
```

Examples include:

* Addition
* Even/odd checking
* Temperature conversion
* Voting eligibility
* Finding maximum values
* Mathematical operations

Example:

```python
@staticmethod
def add(a, b):
    return a + b
```

---

# ✨ Features

The repository provides the following learning features:

* ✅ Beginner-friendly Python examples
* ✅ Hands-on coding exercises
* ✅ Python fundamentals
* ✅ String manipulation
* ✅ Conditional logic
* ✅ Loop-based problem solving
* ✅ List operations
* ✅ Tuple operations
* ✅ Set operations
* ✅ Dictionary operations
* ✅ Object-Oriented Programming
* ✅ Constructors
* ✅ Instance methods
* ✅ Class methods
* ✅ Static methods
* ✅ Class variables
* ✅ Alternative constructors
* ✅ Practical examples with outputs
* ✅ Google Colab compatible notebooks

---

# 💻 Requirements

There are two ways to run this repository.

## Option 1 — Google Colab

Recommended for beginners.

Requirements:

* A Google account
* Internet connection
* Web browser

No local Python installation is required when using Google Colab.

---

## Option 2 — Run Locally

If you want to run the notebooks on another computer, install:

### Required

* Python 3.x
* Jupyter Notebook

Git is recommended for cloning the repository.

---

# 🚀 How to Run on Another Computer

## Step 1 — Install Python

Download and install Python 3 from the official Python website:

https://www.python.org/downloads/

During Windows installation, make sure to select:

```text
Add Python to PATH
```

---

## Step 2 — Verify Python

Open Command Prompt or Terminal and run:

```bash
python --version
```

You should see something similar to:

```text
Python 3.x.x
```

---

## Step 3 — Install Jupyter Notebook

Run:

```bash
pip install notebook
```

---

## Step 4 — Clone the Repository

Install Git if it is not already installed.

Then run:

```bash
git clone https://github.com/subhasmitapattanaik2002-ship-it/colab.git
```

Move into the repository:

```bash
cd colab
```

---

## Step 5 — Start Jupyter Notebook

Run:

```bash
jupyter notebook
```

Jupyter Notebook will open in your web browser.

You will see the repository files:

```text
first.ipynb
subha_.ipynb
task_by_shiv_sir_in_list.ipynb
26_06_2026.ipynb
```

Open any notebook and run the cells.

---

# ☁️ How to Run Using Google Colab

Google Colab is the easiest option for this repository.

### Step 1

Open:

https://colab.research.google.com/

### Step 2

Sign in with your Google account.

### Step 3

Open the GitHub repository or upload the `.ipynb` file.

### Step 4

Select the notebook you want to run.

### Step 5

Run cells using:

```text
Shift + Enter
```

No local Python installation is required when using Colab.

---

# 🧪 Running the Notebooks

Each notebook contains independent examples and exercises.

You can execute a cell using:

```text
Shift + Enter
```

or use the **Run** button in Jupyter/Google Colab.

Some programs require user input.

For example:

```python
name = input("Enter your name: ")
```

When this cell runs, enter the requested value in the input area.

---

# 📦 Dependencies

The current repository does not require third-party Python packages.

The primary dependency is:

```text
Python 3.x
```

For the Jupyter/Colab environment:

```text
Jupyter Notebook
```

Google Colab can be used without manually installing Python or Jupyter.

---

# 🖥️ Compatibility

The notebooks can be used with:

* Windows
* macOS
* Linux
* Google Colab
* Jupyter Notebook
* JupyterLab

Because the exercises primarily use standard Python functionality, they are designed to be easy to run across different environments.

---

# 📚 Learning Path

The notebooks can be studied in the following order:

```text
Python Basics
      ↓
Strings
      ↓
Conditional Statements
      ↓
Loops
      ↓
Lists
      ↓
Tuples
      ↓
Sets
      ↓
Dictionaries
      ↓
Classes & Objects
      ↓
Constructors
      ↓
Instance Methods
      ↓
Class Methods
      ↓
Static Methods
      ↓
Class Variables
      ↓
Alternative Constructors
```

This progression builds a foundation for more advanced Python programming.

---

# 🎓 Skills Demonstrated

This repository demonstrates my practical understanding of:

### Python Programming

* Python syntax
* Variables
* Data types
* Operators
* Input/output
* Type conversion
* Strings
* Conditions
* Loops

### Data Structures

* Lists
* Tuples
* Sets
* Dictionaries

### Object-Oriented Programming

* Classes
* Objects
* Constructors
* Instance variables
* Class variables
* Instance methods
* Class methods
* Static methods
* Alternative constructors

### Development Tools

* Google Colab
* Jupyter Notebook
* Git
* GitHub
* Markdown documentation

---

# 🔮 Future Improvements

The repository can be extended with additional Python topics and projects.

Planned areas include:

* Functions
* `*args` and `**kwargs`
* Lambda functions
* `map()`
* `filter()`
* Recursion
* Exception handling
* File handling
* Modules and packages
* Regular expressions
* NumPy
* Pandas
* Data visualization
* SQL integration
* Python-based Data Analytics projects

---

# 🤝 Contributing

This repository is primarily a personal learning repository.

However, suggestions, corrections, and improvements are welcome.

If you find an issue:

1. Open an issue on GitHub.
2. Explain the problem clearly.
3. Provide the relevant notebook or code section.
4. Suggest a possible improvement if available.

---

# 📄 License

This repository is intended primarily for educational and learning purposes.

The notebooks contain personal practice work and examples created while learning Python.

If you reuse or modify the content, please provide appropriate attribution to the original repository.

---

# 👩‍💻 Author

**Subhasmita Pattanaik**

Python Programming | Data Analytics | Machine Learning

GitHub:

https://github.com/subhasmitapattanaik2002-ship-it

---

# ⭐ Acknowledgement

This repository represents my practical learning journey in Python programming, from basic syntax and data structures to Object-Oriented Programming.

The goal is to continuously improve programming skills through hands-on practice, problem solving, and progressively building more advanced projects.

---

## ⭐ If You Find This Repository Useful

Consider giving the repository a ⭐ on GitHub.

Thank you for visiting my Python learning repository! 🐍
