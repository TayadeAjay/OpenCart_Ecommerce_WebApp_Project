# OpenCart_Framework


This repository contains a Java-based automated testing project for OpenCart using Selenium, TestNG, and a Page Object Model (POM) design. It also integrates Allure and Extent Reports for comprehensive test reporting.

## Project Overview

The goal of this project is to automate testing of the OpenCart web application, ensuring its functionality and reliability. We use Selenium for web automation, TestNG for test management, and a POM design pattern for a more maintainable and organized test suite.

## Prerequisites

Make sure you have the following software installed before running the tests:

- Java (JDK)
- Maven
- WebDriver (e.g., ChromeDriver, GeckoDriver)
- Any modern web browser (e.g., Chrome, Firefox)

## Getting Started

1. Clone this repository to your local machine.

```shell
git clone (https://github.com/TayadeAjay/OpenCart_Framework.git)
Navigate to the project directory.
shell
Copy code
cd OpenCart_Framework.git
Configure the web driver path and other settings in the src/test/resources/config.properties file.

Run the tests using Maven.

shell
Copy code
mvn clean test
Test Execution
TestNG is used to manage and execute test cases. You can find the test classes in the src/test/java directory.

Allure and Extent Reports provide detailed test reporting. You can access the reports after running the tests.

shell
Copy code
allure serve target/allure-results
Project Structure
The project follows the Page Object Model (POM) design pattern, separating the pages and tests for better organization. Here's the project structure:

src/main/java: Page classes and utility functions.
src/test/java: Test classes.
src/test/resources: Test data and configuration files.
target: Test reports (Allure and Extent).
Reporting
This project uses both Allure and Extent Reports for test reporting. You can find the reports in the target directory after running the tests.

Contribution
Contributions are welcome! If you'd like to contribute to this project, please follow these guidelines:

Fork the repository.
Create a new branch for your feature or bug fix.
Commit your changes and push to your fork.
Create a pull request with a detailed description of your changes.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
For any questions or suggestions, please contact Ajaytayade759@gmail.com

Happy Testing!
