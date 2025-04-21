💼 Robust End-to-End Test Automation Suite for Financial Application
🔍 Project Description
This repository contains an end-to-end test automation suite developed in Java, designed to comprehensively validate both the user interface (UI) and backend services (REST APIs) of a financial application. The main goal is to ensure software quality, guarantee proper functionality, and support continuous delivery through reliable automated tests.

🧩 Technologies & Tools Used

Java – Main language of the project

Maven – Build automation and dependency management

Selenium WebDriver + WebDriverManager – Browser-based UI automation

REST Assured – RESTful API validation

JUnit 5 – Base testing framework

Cucumber + Gherkin – BDD approach for readability and collaboration

Jackson – JSON/XML data handling

Log4j / SLF4j – Logging and execution traceability

JavaFaker – Generation of realistic test data

Maven Cucumber Reporting Plugin – Visual and detailed HTML report generation

⚙️ Automated Functionalities

UI (Selenium):

New customer registration

Opening different types of accounts

Complex fund transfer scenarios (validating both successful and failed flows)

API (REST Assured):

Verification of Customer and Account APIs

Transaction history validation

New account creation

API contract verification (status codes, response structures, etc.)

📈 Best Practices & Quality

Validations using JUnit assertions within Cucumber step definitions

Use of custom tags (@smoke, @regression, @API, @UI) for targeted test executions

Integration with CI/CD pipelines for continuous automated testing

Clear and comprehensive HTML reports for coverage tracking and results
