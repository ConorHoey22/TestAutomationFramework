# Test Automation Framework


Project Name: Test Automation Framework

🖥 Language: C#

🧪 Testing Approach: BDD (Behavior-Driven Development)

🎯 Purpose:

A robust and maintainable test automation framework designed to support Behavior-Driven Development using Cucumber syntax via SpecFlow alternatives, given SpecFlow is no longer actively maintained. 
This framework enables seamless collaboration between developers, testers, and non-technical stakeholders by using human-readable feature files to define system behavior.

🧱 Core Features:

BDD-style test automation using Gherkin syntax

Page Object Model (POM) for scalable and maintainable UI tests

Cross-browser support with automatic driver management

NUnit for test execution and reporting

📦 NuGet Packages Used:

NUnit – Test framework for structuring and executing tests

WebDriverManager – Automatically manages browser driver binaries

Selenium.WebDriver – Core library for browser automation

Selenium.Support – Provides additional support for advanced WebDriver capabilities

Reqnroll - open-source .NET BDD framework
Reqnroll is an open-source Cucumber-style BDD test automation framework for .NET. It has been created as a reboot of the SpecFlow project.


---
GUIDE - 
Install Reqnroll within Extenstion Manager
Install Nuget packages 
Create projects  - Scalablity by using multiple projects within one solution 

what does each file do 

----

Folder/File Structure 

Solution: TestAutomationCVExample


Project : TestAutomationCVExample.Core
Summary : Used for interfaces , Framework utilties 

TestAutomationCVExample.Core
│
├── Interfaces/                  # Interfaces for abstraction
│
├── LocalWebDriver/             # Browser driver setup and management
│
├── Logging/                    # Custom logging logic
│
├── Reports/                    # Report generation (e.g., HTML, ExtentReport)

Project : TestAutomationFramework.UI 
Summary : Feature Classes , Test cases , POM , Step Classes

Project : TestAutomationFramework.Tests 
Summary : Feature Classes  , Resources 





Structure diagram 


----------------------------
TEST CASES
----------------------------



