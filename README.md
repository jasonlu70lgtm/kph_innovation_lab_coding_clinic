# 🚀 KPH Innovation Lab: Coding Clinic (Session 2)
Welcome to the repository for **Coding Clinic Session 2**, hosted by BlueDuckyLu for the KPMG Performance Hub (KPH) Innovation Lab.

This session provides hands-on, practical guidance designed to elevate Python engineering standards across data, analytics, and automation workflows. Session 2 focuses on transitioning from procedural scripting to robust software development practices: **Object-Oriented Programming (OOP)**, **Test-Driven Development (TDD)**, and **Visual Debugging**.

---

## 📌 Session Overview & Objectives

In this clinic, participants explore:
- **Object-Oriented Programming (OOP) in Python:** Structuring reusable code using classes, encapsulation, inheritance, polymorphism, and magic/dunder methods.
- **Test-Driven Development (TDD):** Writing predictable unit tests with `pytest`, mocking external dependencies, and adhering to the *Red-Green-Refactor* lifecycle.
- **Visual Debugging Workflows:** Mastering breakpoint inspection, step-through debugging, variable watches, and call stack analysis within VS Code and Jupyter Notebook environments.
- **Clean Code & Architecture:** Refactoring complex data processing logic into clean, modular, and maintainable Python components.

---

## 🛠️ Prerequisites & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/jasonlu70lgtm/kph_innovation_lab_coding_clinic.git
cd kph_innovation_lab_coding_clinic
```

### 2. Set Up a Virtual Environment
```bash
# Using Python venv
python -m venv venv

# Activate on macOS/Linux:
source venv/bin/activate

# Activate on Windows:
.\venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install --upgrade pip
pip install -r requirements.txt
```

---

## 📓 Running the Notebooks

Launch JupyterLab or VS Code to step through the interactive session exercises:

```bash
jupyter lab
```

1. **`kph_innovation_lab_20260916.ipynb`**: Learn test driven development, object oriented programming, and graphics for client engagement work.
2. **`kph_innovation_lab_20260916_solution.ipynb`**: Solution for the lab. 

---

## 🧪 Running the Test Suite

Execute the unit tests via `pytest` from the root directory:

```bash
# Run all tests
pytest

# Run tests with verbose output
pytest -v

# Run tests with code coverage report
pytest --cov=src tests/
```

---

## 🔍 Visual Debugging Quick-Guide

### Debugging in VS Code
1. Open the project root in VS Code.
2. Set breakpoints by clicking to the left of the line numbers in any `.py` file or `.ipynb` notebook cell.
3. Open the **Run and Debug** panel (`Ctrl+Shift+D` or `Cmd+Shift+D`) and select **Python: Current File** (or click **Debug Cell** in Jupyter Notebooks).
4. Inspect the **Variables**, **Watch Expressions**, and **Call Stack** panels to trace variable state transitions.

---

## 👤 Session Host & Maintainer

* **Host & Instructor:** Jason Lu (jasonlu7@KPMG.com)
* **Organization:** KPMG Performance Hub (KPH) Innovation Lab

---

## 📄 License & Attribution

Internal training materials developed for the KPH Innovation Lab Coding Clinic series. Distributed for educational and professional development purposes.

