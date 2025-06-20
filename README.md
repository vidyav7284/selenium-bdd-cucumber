# 🧪 Selenium-BDD-Cucumber

A Proof of Concept (POC) for end-to-end **web automation testing** using **Selenium**, **Cucumber BDD**, **TestNG**, and the **Page Object Model (POM)**. This project simulates a real-world e-commerce flow — validating the *Add to Cart* functionality — and is structured to be readable, reusable, and scalable.

🔗 **GitHub Repository:** [selenium-bdd-cucumber](https://github.com/vidyav7284/selenium-bdd-cucumber)

---

## 📸 Project Execution Report

![reoprt](https://github.com/user-attachments/assets/0b4c84c4-2f4e-4a85-a1fb-96471a233742)


## 🎥 Automation Flow (GIF)

![demoVideo](https://github.com/user-attachments/assets/bfe93208-65d1-4b19-a433-6e76c8c41510)



---

## 🚀 Features


✅ Automates an end-to-end Amazon Add to Cart user journey

✅ Built using Page Object Model (POM) for better code organization

✅ Uses Cucumber to define test scenarios in plain English (Gherkin)

✅ Uses TestNG for test execution and reporting

✅ Reusable components and modular test steps

✅ Includes assertions and validations for robustness

✅ Easily integrates into CI/CD pipelines

✅ Simple to set up and run using Maven

✅ Structured for cross-browser compatibility 

✅ Clean code and naming conventions for readability

---

## 🔧 Technologies Used

| Tool/Library     | Purpose                       |
| ---------------- | ----------------------------- |
| **Java**         | Programming Language          |
| **Selenium**     | Web Automation Framework      |
| **Cucumber BDD** | Behavior Driven Testing       |
| **TestNG**       | Test Framework                |
| **Maven**        | Dependency & Build Management |
| **Eclipse IDE**  | Development Environment       |
| **Gherkin**      | Feature File Language         |

---

🗂️ Project Structure


![ProStruc](https://github.com/user-attachments/assets/303a3498-5ec1-43ca-8a43-13a2dea3f335)

---

## 📋  Feature File

```gherkin
Feature: Add to Cart Functionality

  Scenario: Validate adding an item to the cart from start to end
    Given the user is on the home page
    When the user selects "Kindle Store" from the category
    And clicks on the search icon
    And selects the checkbox for KindleUnlimitedEligible
    And sorts the results by "Best Sellers"
    Then the user adds the first item to the cart
    And verifies the item is added successfully
```

---

## 🧪 How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/vidyav7284/web-automation-poc.git
```

### 2. Import into Eclipse

* Open Eclipse.
* File → Import → Existing Maven Project → Select folder.

### 3. Install dependencies

Maven will automatically resolve dependencies from `pom.xml`.

### 4. Execute Tests

* Run the `TestNG` suite or a specific runner class.
* You can also run via command line:

```bash
mvn test
```

---

## ✅ Best Practices Followed

* ✅ Page Object Model (POM)
* ✅ Layered architecture (Test → Steps → Pages)
* ✅ Reusable selectors and methods
* ✅ Descriptive method and class names
* ✅ Gherkin language for human-readable tests

---

## 📎 Resources

* [Selenium Documentation](https://www.selenium.dev/documentation/)
* [Cucumber Docs](https://cucumber.io/docs/)
* [TestNG Docs](https://testng.org/doc/)
* [Maven Guide](https://maven.apache.org/guides/index.html)

---

## 📄 License

This project is licensed under the [Apache 2.0 License](LICENSE).

---

## 👤 Author

**Vidya Vanjare**  
📧 v.vanjare@gmail.com
📎 [LinkedIn](https://www.linkedin.com/in/vidya-vanjare)  
