# AnilKumar_liftu.tech_Assignment

This repository contains a comprehensive **Automation Testing Framework** designed for web applications using **Java** and **Selenium WebDriver**. The framework is built to be highly modular, scalable, and maintainable. It incorporates advanced features such as detailed reporting with **Extent Reports** and **TestNG** integration for efficient test execution and management.

---

## Key Features

### Web Automation with Java and Selenium:
- Automates various browser interactions and validations using Selenium WebDriver.
- Supports multiple browsers (Chrome, Firefox, etc.) for cross-browser testing.

### TestNG Integration:
- Enables grouping, parallel execution, and prioritization of test cases.
- Allows easy configuration of test suites via `testng.xml`.

### Detailed Reporting:
- Uses **Extent Reports** for enhanced, visually appealing reports.
- Reports include detailed logs, screenshots of failed tests, and test execution summaries.

### Listener Support:
- Custom listeners handle test lifecycle events (e.g., logging test results, capturing screenshots on failure).

### Data-Driven Testing:
- Extendable for testing with dynamic data using external files (e.g., Excel, CSV).

### Maintainable Design:
- Implements the **Page Object Model (POM)** for reusability and separation of concerns.
- Modular structure for easy addition of new test cases and features.

### Parallel Execution:
- Configured for parallel test execution, optimizing test run times.

---

## Project Structure
AnilKumar_liftu.tech_Assignment
├── src
│   ├── main
│   │   ├── java
│   │   │   ├── com.liftu.tech.base       # Base classes (e.g., WebDriver initialization)
│   │   │   ├── com.liftu.tech.pages      # Page Object Model classes
│   │   │   ├── com.liftu.tech.utils      # Utility classes (e.g., Listeners, Helpers)
│   │   │   └── com.liftu.tech.reports    # Extent Reports integration
│   ├── test
│   │   ├── java
│   │   │   ├── com.liftu.tech.tests      # Test case classes
│   │   └── testng.xml                    # TestNG configuration file
├── reports                               # Extent report output files
├── pom.xml                               # Maven configuration file
├── README.md  


---

## Prerequisites

Before running the project, ensure you have the following installed:

- **Java Development Kit (JDK)** (Version 8 or higher)
- **Maven** (For dependency management and build execution)
- **Selenium WebDriver** (Included via Maven dependencies)
- **TestNG** (Integrated via Maven dependencies)
- **Git** (For cloning the repository)
- **Browser Drivers**:
  - ChromeDriver, GeckoDriver, or others depending on the browsers you plan to use.

---

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/Anilkumarsm28/AnilKumar_liftu.tech_Assignment.git
cd AnilKumar_liftu.tech_Assignment





