Selenium Java Automation Tasks
Description:
This repository is created to upload Selenium Automation Tasks using Java.

Task 01 Description:
Go to "URL". Steps---
Task 02 Description:
Task 03 Description:
Note on This Selenium Java Automation Tasks
Added TestNG
Implemented Assert statements
Implemented WebDriverWait (explicit waits).
Required Software to Install:
# java version 17
java --version
# git version 2.40.1
git --version
# maven version 3.9.2
mvn --version
selenium version 4.11.0

testng version 7.8.0

# maven version 3.9.2
mvn --version

Required Dependency to run:
# WebDriverManager
# Selenium
# TestNG
Installations:
To clone the repository git clone https://github.com/donacj/TestFramework

Architecture of framework:
base package: base package contains code for lauching the browser and loading property file .
config package: This package is used to manage the test configurations like browsername and url.
Resources:
Utilities: This package contains screenshot utility to take evidences and extent report utility to generate report
extent report will be genearted and stored in src/main/java/reports
evidences will be stored in C:\SavedScreenshot
Instructions to Run the Code:
# to build the project
mvn build
# to run the project
mvn run
# to test the project
mvn test
