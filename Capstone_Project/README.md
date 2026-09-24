# 🚀 Capstone 2 — Selenium Python Automation Framework

### *by CHIRASHREE PAN*

<p align="center">

  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">

  <img src="https://img.shields.io/badge/Selenium-WebDriver-43B02A?style=for-the-badge&logo=selenium&logoColor=white" alt="Selenium">

  <img src="https://img.shields.io/badge/PyTest-Testing-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="PyTest">

  <img src="https://img.shields.io/badge/Unittest-Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Unittest">

  <img src="https://img.shields.io/badge/Page%20Object%20Model-POM-6C63FF?style=for-the-badge" alt="POM">

  <img src="https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">

</p>

<p align="center">

### 🧪 Modular Web Automation Framework for E-Commerce Testing

**Built with Python • Selenium WebDriver • PyTest • Unittest • Page Object Model**

</p>

---

## 📌 Project Information

| Details                     | Information                                       |
| --------------------------- | ------------------------------------------------- |
| 🎓 **Project**              | Capstone 2 – Selenium Python Automation Framework |
| 👩‍💻 **Student**           | **Chirashree Pan**                                |
| 🆔 **Enrollment No.**       | **12023002029030**                                |
| 🎓 **Degree**               | B.Tech – Computer Science & Engineering           |
| 🏫 **Institute**            | Institute of Engineering and Management, Kolkata  |
| 🧪 **Domain**               | Software Testing & Test Automation                |
| 🐍 **Programming Language** | Python                                            |
| 🌐 **Automation Tool**      | Selenium WebDriver                                |
| 🧪 **Testing Frameworks**   | PyTest & Unittest                                 |
| 🧱 **Design Pattern**       | Page Object Model                                 |
| 📦 **Project Type**         | Academic Capstone Project                         |

---

# 📖 About the Project

**Capstone 2 – Selenium Python Automation Framework** is a modular web automation testing framework developed using **Python and Selenium WebDriver**.

The framework is designed to automate functional workflows of an e-commerce application while following a structured and maintainable automation architecture.

The project combines:

* Selenium WebDriver automation
* PyTest test execution
* Python Unittest support
* Page Object Model (POM)
* CSV-based test data
* Configuration management
* Reusable PyTest fixtures
* Failure screenshot capture
* HTML test reporting
* Modular utility functions

The main objective is to demonstrate how Selenium test scripts can be organized into a reusable automation framework instead of maintaining independent and repetitive test scripts.

---

# 🎯 Project Objectives

### 🧪 1. Automate Functional Workflows

Automate important user workflows of an e-commerce application such as login, product search and cart operations.

### 🧱 2. Implement Page Object Model

Separate page locators and browser interactions from test cases to improve maintainability.

### ♻️ 3. Promote Reusability

Create reusable utilities, fixtures and page methods to reduce duplicate code.

### 📋 4. Implement Data-Driven Testing

Store test inputs separately in CSV files instead of hardcoding them directly into test cases.

### ⚙️ 5. Centralize Configuration

Maintain application and execution settings using a configuration file.

### 📸 6. Support Debugging

Capture screenshots during test failures for easier analysis.

### 📊 7. Generate Test Reports

Generate HTML reports to provide a readable summary of test execution.

### 🎥 8. Provide Project Demonstration

Include a recorded video demonstrating the Selenium Python automation framework and its execution.

---

# ✨ Key Features

| Feature                | Description                                             |
| ---------------------- | ------------------------------------------------------- |
| 🌐 Selenium Automation | Automates browser interactions using Selenium WebDriver |
| 🧪 PyTest              | Supports test execution and reusable fixtures           |
| 🧪 Unittest            | Includes Python Unittest implementation                 |
| 🧱 Page Object Model   | Separates UI interaction logic from test logic          |
| 📋 CSV Test Data       | Supports external test data                             |
| ⚙️ Configuration       | Uses `config.ini` for configuration management          |
| ♻️ Reusable Utilities  | Provides reusable helper functions                      |
| 📸 Screenshots         | Captures screenshots for failed scenarios               |
| 📊 HTML Reports        | Generates test execution reports                        |
| 🎥 Demo Video          | Includes a recorded demonstration of the project        |
| 📁 Modular Structure   | Organizes framework components into separate modules    |

---

# 🛠️ Technology Stack

| Technology                | Purpose                     |
| ------------------------- | --------------------------- |
| 🐍 **Python**             | Programming language        |
| 🌐 **Selenium WebDriver** | Browser automation          |
| 🧪 **PyTest**             | Test execution and fixtures |
| 🧪 **Unittest**           | Python testing framework    |
| 🧱 **Page Object Model**  | Automation framework design |
| 📄 **CSV**                | Test data management        |
| ⚙️ **ConfigParser**       | Configuration management    |
| 📊 **PyTest HTML**        | HTML test reporting         |
| 🌐 **Chrome WebDriver**   | Browser automation          |
| 🔧 **Git**                | Version control             |
| 🐙 **GitHub**             | Repository management       |

---

# 🏗️ Framework Architecture

The framework follows a modular automation architecture.

```text
                    ┌──────────────────────────┐
                    │       Test Cases         │
                    │     PyTest / Unittest    │
                    └────────────┬─────────────┘
                                 │
                                 ▼
                    ┌──────────────────────────┐
                    │       Page Objects       │
                    │                          │
                    │ Login / Home / Product   │
                    │          / Cart          │
                    └────────────┬─────────────┘
                                 │
                                 ▼
                    ┌──────────────────────────┐
                    │    Selenium WebDriver    │
                    └────────────┬─────────────┘
                                 │
                                 ▼
                    ┌──────────────────────────┐
                    │    E-Commerce Web App    │
                    └──────────────────────────┘
```

---

# 📁 Project Structure

```text
Capstone-2-Selenium-Python-Automation-Framework/
│
├── config/
│   └── config.ini
│
├── data/
│   └── test_data.csv
│
├── pages/
│   ├── login_page.py
│   ├── home_page.py
│   ├── product_page.py
│   └── cart_page.py
│
├── tests/
│   ├── test_login.py
│   ├── test_product.py
│   ├── test_cart.py
│   └── unittest_tests.py
│
├── utilities/
│   ├── config_reader.py
│   ├── screenshot.py
│   └── test_data_reader.py
│
├── screenshots/
│
├── reports/
│
├── Video/
│   └── Project Demonstration Video Link
│
├── conftest.py
├── requirements.txt
├── pytest.ini
└── README.md
```

---

# 🎥 Project Demonstration Video

The **Video** folder contains the recorded demonstration of the Selenium Python Automation Framework.

The video demonstrates the project execution and automation workflow.

### ▶️ Watch the Project Demonstration

[**View Project Demonstration Video on Google Drive**](https://drive.google.com/file/d/1mx3hb9Mv5mVNHMc2-r6uyRhJoG29tikf/view?usp=drivesdk)

The video is also referenced in the project repository under:

```text
Video/
```

---

# 🚀 How to Run the Project

## 1. Clone the Repository

```bash
git clone <your-github-repository-url>
```

## 2. Navigate to the Project Directory

```bash
cd Capstone-2-Selenium-Python-Automation-Framework
```

## 3. Install Dependencies

```bash
pip install -r requirements.txt
```

## 4. Run PyTest Tests

```bash
pytest
```

## 5. Generate HTML Report

```bash
pytest --html=reports/report.html --self-contained-html
```

---

# 📊 Test Execution

The framework supports:

* Functional test execution
* Data-driven testing
* PyTest fixtures
* Unittest test cases
* Failure screenshot capture
* HTML test reporting

Test results and generated reports can be stored in the `reports/` directory.

---

# 📸 Failure Screenshots

When a test case fails, the framework captures a screenshot to help identify the cause of the failure.

Screenshots are stored in:

```text
screenshots/
```

This improves debugging and makes test failure analysis easier.

---

# 📋 Data-Driven Testing

The framework uses CSV files to store test data separately from the automation logic.

```text
data/
└── test_data.csv
```

This allows multiple test inputs to be executed without modifying the test scripts.

---

# 🧱 Page Object Model

The project follows the **Page Object Model (POM)** design pattern.

Each important application page is represented by a separate Python class containing:

* Page locators
* Page interaction methods
* Reusable actions

This keeps test cases clean and improves framework maintainability.

---

# 🧪 Testing Frameworks

## PyTest

PyTest is used for:

* Test execution
* Fixtures
* Test organization
* HTML reporting
* Failure handling

## Unittest

Python's built-in Unittest framework is also included to demonstrate support for different testing approaches.

---

# 📈 Benefits of the Framework

The framework provides:

* Better test organization
* Reusable automation components
* Reduced code duplication
* Easier maintenance
* Data-driven testing
* Centralized configuration
* Failure debugging through screenshots
* Automated HTML reporting
* Scalable project structure

---

# 👩‍💻 Author

### **Chirashree Pan**

**B.Tech – Computer Science & Engineering**
Institute of Engineering and Management, Kolkata

**Enrollment No.: 12023002029030**

---

# 📌 Project Type

**Academic Capstone Project – Selenium Python Automation Framework**

Developed as part of practical learning and implementation in **Software Testing and Test Automation**.
