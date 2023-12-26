# Automation Exercise test project

## Overview
This framework implements a very basic webdriver autotests, that helps to reduce manual effort and improve quality of the product. More information in the [Automation Test Plan](https://docs.google.com/document/d/16E1LUr70FcihBtY8u14qlXIGEu0o_vpYkivhiLttwGY/edit)

## Design approach
The framework is structured into different components, following the Page Object Design pattern for better maintainability and scalability:

🔹[Maven](https://maven.apache.org/) - For project build and dependency maintenance.

🔹[TestNG](https://testng.org/doc/) - For testing organization structure.

🔹[Selenium Server](https://www.selenium.dev/downloads/) - For interactions with web browsers.

🔹Tests - Contain collection of all automated tests.

🔹Page Object - Locators, Constants and Methods for the tested pages.

🔹Utils - Different kind of helpers for testing.

🔹API utils - API calls to the server backend.

🔹Reports - Test results of script runs.

## Getting started
To run the project locally, use the following command
```
mvn clean test -DsuiteXmlFile=testng.xml
```
