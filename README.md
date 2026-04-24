## Project: Selenium Login Test (POM Example)

This is a simple **Maven-based Selenium project** created using **Eclipse IDE** to demonstrate the **Page Object Model (POM)** design pattern.

### Project Structure

```
src/test/java
│
├── LoginTest.java
├── LoginPage.java      (Without PageFactory)
└── LoginPage2.java     (With PageFactory)
```

### Description

* **LoginTest.java**

  * Contains test cases for login functionality
  * Can use either of the page classes (`LoginPage` or `LoginPage2`)

* **LoginPage.java**

  * Page Object class implemented **without PageFactory**
  * Uses `By` locators and direct WebDriver calls

* **LoginPage2.java**

  * Page Object class implemented **with PageFactory**
  * Uses `@FindBy` annotations and `PageFactory.initElements()`

### Tech Stack

* Java
* Selenium WebDriver
* Maven
* Eclipse IDE
* TestNG 

### How to Run

1. Import project into Eclipse as a Maven Project
2. Update dependencies (Maven → Update Project)
3. Run `LoginTest.java` as a TestNG Test

### Purpose

* Understand POM design pattern
* Compare:

  * Without PageFactory vs With PageFactory
* Learn basic Selenium test structure

