# Automation_Testing_Using_Junit
This repository contains three automated test cases implemented using Java, Selenium, and JUnit:

**1.** [**Webform Automation for Digital Unite**](https://www.digitalunite.com/practice-webform-learners)<br>
**2.** [**Guest Registration Automation for WP Everest**](https://demo.wpeverest.com/user-registration/guest-registration-form/)<br>
**3.** [**Web Scraping for DSEBD Stock Prices**](https://dsebd.org/latest_share_price_scroll_by_value.php)

# Project Description

**Webform Automation for Digital Unite**
- Automating the form submission process, including file upload (≤ 2 MB) and validating the success message.

**Guest Registration Automation for WP Everest**
- Automating the guest registration form by filling out mandatory fields, submitting the form, and verifying successful registration.

**Web Scraping for DSEBD Stock Prices**
- Scraping stock market table data, printing all cell values, and storing them in a text file for further reference.

## Prerequisites
Ensure you have the following installed:
- Java Development Kit (JDK) 8 or higher.
- A Selenium-compatible web browser (e.g., Chrome, Firefox).
- ChromeDriver or GeckoDriver (match your browser version).

## Tools & Technologies
- **Programming Language**: Java
- **Framework**: JUnit
- **Browser Automation**: Selenium WebDriver
- **IDE**: IntelliJ IDEA or Eclipse

## Project Reports
### 1. Webform Automation for Digital Unite
- Automated field inputs.
- Implemented file upload functionality.
- Asserted the expected success message: "Thank you for your submission!".
#### Report
![image](https://github.com/user-attachments/assets/9a56248b-5b76-4643-86bb-47fc18addd62)




### 2. Guest Registration Automation for WP Everest
- Automated field inputs for First Name, Last Name, Email, Password, Gender, DOB, Nationality, Phone, Country, and acceptance of Terms & Conditions.
- Asserted successful registration upon submission.
#### Report 
![Junittask2](https://github.com/user-attachments/assets/21f27a8f-c3a9-4d21-9ed9-87731f92309a)




### 3. Web Scraping for DSEBD Stock Prices
- Scraped table data from the provided webpage using Selenium.
- Printed all table cell values in the console.
- Stored the scraped data into a text file for reference. 
#### Report
![image](https://github.com/user-attachments/assets/9fb16fc1-5b2e-455a-bb73-922632fde327)

# How to Execute the Tests **Configuration and Setup**
Install the JDK and configure Eclipse or IntelliJ IDEA as your IDE.
Include the JUnit and Selenium libraries in the build path for your project.
Make sure you have the browser driver installed and configured in your PATH, such as ChromeDriver.

Executing the Tests
You can download or clone the project files to your computer.
To begin the automation task, open the appropriate Java test class:

     -Task1WebSubmissionFrom.java
     -Task2RegistrationFromForUser.java
     -Task3DhakaStockExchangeScarpTable
- Use the terminal command or the IDE to run the test classes:

  

**Confirmation**

-Look for success or failure signals in the assertion logs for the online forms.

-Check the resulting text file (such as store.txt) and the terminal output for the table scraping.



**Output Documents**

- Logs: The console contains logs of test results and execution information.
- Text File: Scraped table data is stored in ```store.txt```.

#### Text File
![image](https://github.com/user-attachments/assets/9e526b83-c2e2-4911-b9e4-b389dbcd44ce)


  
