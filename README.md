# ShobKaaj Web Automation Testing Framework

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)
![TestNG](https://img.shields.io/badge/TestNG-FF0000?style=for-the-badge&logo=TestNG&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white)

An automated web application testing framework for **ShobKaaj** – a location-based service platform connecting clients and local workers in Bangladesh.

---

## 📋 Project Overview

This project implements a robust **Selenium WebDriver** automation framework using **Java**, **TestNG**, and **Maven**. It focuses on automating critical user flows such as user login, homepage validation, and other core functionalities of the ShobKaaj web application.

---

## ✨ Features

- **Page Object Model (POM)** design pattern for better maintainability
- **TestNG** for test management and reporting
- **Maven** for dependency management and build automation
- Cross-browser testing support (Chrome, Firefox, Edge)
- Detailed test reports with screenshots on failure
- Reusable utilities and base classes
- Parameterized testing support

---

## 🛠️ Technologies Used

| Technology       | Version    | Purpose                        |
|------------------|------------|--------------------------------|
| Java             | 17+        | Programming Language           |
| Selenium WebDriver | 4.x      | Browser Automation             |
| TestNG           | 7.x        | Testing Framework              |
| Maven            | 3.x        | Build & Dependency Management  |
| Extent Reports   | -          | Advanced Reporting (Optional)  |

---

## 📁 Project Structure

```bash
ShobKaaj-web-technology-project-automation/
├── src/
│   └── main/java/
│       └── com/shobkaaj/
│           ├── base/           # BaseTest class
│           ├── pages/          # Page Object Classes
│           ├── tests/          # Test Classes (LoginTest, HomePageTest, etc.)
│           └── utils/          # Utilities & Helpers
├── pom.xml                     # Maven configuration
├── testng.xml                  # TestNG suite configuration
└── README.md
