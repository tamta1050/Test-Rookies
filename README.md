
# Automation and Manual Testing of PracticeSoftwareTesting.com

# Objective:

To ensure the reliability, functionality, and user experience of the PracticeSoftwareTesting.com platform by employing both manual testing and Selenium-based automation testing techniques.

# Project Scope:

Manual Testing:

* Analyze the functionality of key features and workflows.
* Perform exploratory testing to uncover hidden bugs.
* Validate usability, compatibility, and performance of the website.

Selenium Automation Testing:

* Automate regression and repetitive test cases using Selenium WebDriver.
* Utilize the Page Object Model (POM) framework for maintainability and scalability
* Execute test cases across multiple browsers to ensure cross-browser compatibility.

# "Mind Map:

 Testing Overview for PracticeSoftwareTesting.com"

 ![image](https://github.com/user-attachments/assets/4836fda7-5270-4105-a449-66d45859a3fd)


# Key Features Tested
This project focused on ensuring the functionality and reliability of the following key features of the PracticeSoftwareTesting.com platform:

* Login Functionality
Purpose: To validate user authentication and ensure only authorized users can access secure sections.

Test Cases:
Login with valid credentials (positive scenario).

Login with invalid credentials (negative scenario).

Error message verification for empty username/password fields.

Password recovery functionality.

Automation: Automated positive and negative login scenarios for rapid regression testing.

* Search Bar
Purpose: To verify the search functionality and its accuracy in returning relevant results.

Test Cases:
Search with valid keywords (positive scenario).

Search with invalid keywords or gibberish (negative scenario).

Empty search query and handling error messages.

Case-sensitivity testing in search queries.

Automation:
Automate test cases to validate search results and response time across browsers.

* Filters
Purpose: To test the accuracy of filters and ensure that users can narrow down results effectively.

Test Cases:

Apply single filter and validate results.

Apply multiple filters and ensure results match the selected criteria.

Remove applied filters and verify default state.

Validate UI elements for filters (checkboxes, dropdowns, etc.).

Automation: Developed reusable scripts for testing various filter combinations.

* Add to Cart
Purpose: To test the e-commerce functionality, ensuring items are added to the cart and retained correctly.

Test Cases:

Add single and multiple items to the cart.
Validate total price and quantities in the cart.

Remove items and verify updates in the cart summary.

Session persistence of cart items upon logout and login.

Automation: Scripts to verify adding and removing items under different scenarios.






