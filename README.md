
# Manual Testing - LazzPharma
This repository contains manual test documentation for the [LazzPharma](https://www.lazzpharma.com/) e-commerce platform. The goal of this project is to ensure the reliability, functionality, and user-friendliness of the platform through comprehensive manual testing practices.

## Introduction
LazzPharma is a leading online pharmacy in Bangladesh that offers a wide range of medicines, health products, and personal care items. To ensure a smooth and reliable experience for its users, thorough manual testing of the platform is essential.

This repository is dedicated to documenting the manual testing process for the LazzPharma website. It includes a structured approach to identifying functional issues, usability flaws, and UI inconsistencies, ultimately contributing to a more stable and user-friendly platform.

## Test Plan
The test plan outlines the scope, approach, resources, and schedule for manual testing activities. Key testing focus areas include:

**Key Components of the Test Plan:**
- **Test Items**: Modules to be tested include User Account, Home Page, Categories, Product Management, Request Order, Special Offers, Branch Location, Company Info, and Footer.
- **Features to be Tested:**: Sign Up, Login, Logout, Profile, Order History, Prescription History, Request History, Submit Complain, Payment History, Banners, Marquee, Service Highlights, Featured Products, Resort Banner,Categories, Product Search, Product Card, Product Cart, Checkout, Request Order, Special Offers, Search Branch, Branch List, Map Location, Company info, Footer
- **Test Approach:** Manual functional, UI, and usability testing.
- **Entry Criteria:** Stable build available for testing, test data prepared.
- **Exit Criteria:** All test cases executed, critical bugs resolved, summary report created.


For more details, refer to the [Test Plan PDF](https://drive.google.com/file/d/1kc7YnCGultZV4a3i6GZj2W7MXKVtsyxj/view?usp=sharing).

## Mind Map
A visual mind map is included in the **Mind Maps** sheet of the Excel file, which outlines the LazzPharma platform's structure, including:

- **Account:** Sign Up, Login, Logout, Profile, Order History, Prescription History, Request History, Submit Complain, Payment History.
- **Home Page:** Banners, Marquee, Service Highlights, Featured Products, Resort Banner.
-**Request Order:** Add Product, Prescription Selection, Receiver's Information.
- **Special Offers** 
- **Branch Location:** Search Branch, Branch List, Google Map Location.
- **Company Info:** Review, Gallery, About Us, Contact Us, Franchise Info.
- **Product Management:** Categories, Product Search, Product Card, Cart Checkout
- **Shopping Management:** Product Search, Shopping Cart, Track Order.
- **Footer:** Lazz Pharma Limited, For Customer, Suppoert, Socialize.

The Mind Map is visualized in the **Mind Maps** sheet of the Excel file.


## Test Scenarios
Test scenarios define high-level functionalities to be tested. Example scenarios include:


- Validate login, signup, and password reset and logout functionality with proper redirection.
- Validate logged-in user features like profile editing, order history, prescription uploads.
- Validate product search functionality with accurate and relevant results.
- Validate product card and product details page components (name, price, review, add to bag, etc).

Test scenarios are documented in the **TestScenarios** sheet of the Excel file.

## Test Cases
The test cases are organized into different modules based on the functionality being tested. Each test case includes:
- **Description:** A brief description of the test case.
- **Expected Result:** The expected outcome of the test.
- **Actual Result:** The observed outcome.
- **Test Data:** Data used during testing.
- **Reproducing Steps:** Step-by-step instructions to perform the test.
- **Bugs ScreenShot:** ScreenShot/ScreenRecording of reported bug.
- **Status:** Pass/Fail status of the test case.


Test cases are documented in the following files:

[Lazz Pharma Limited_TestCase_Writing.xlsx](https://github.com/kawsar12759/ManualTesting-LazzPharma/blob/main/Lazz%20Pharma%20Limited_TestCase_Writing.xlsx) (TestCase sheet)


## Bug Reports
Bug reports document any issues found during testing. Each bug report includes:

- **Issue:** A description of the bug.
- **Reproducing Steps:** Steps to reproduce the issue.
- **Environment:** The environment where the bug was found (e.g., Production).
- **Priority:** The priority of the bug (e.g., P1, P2).
- **Severity:** The severity of the bug (e.g., Major, Minor).
- **Screenshot:** A screenshot/Screen recording of the issue.
- **Expectation:** The expected behavior.
- **Responsible QA:** The QA engineer responsible for reporting the bug.

Bug reports are documented in the **Bug Report** sheet of the Excel file.

## Test Summary Report
The Test Summary Report provides a high-level overview of the testing activities, including the results of executed test cases, defects found, and overall test coverage. It serves as a final report to stakeholders, summarizing the quality of the application after testing.


![Test Summary Report](https://i.ibb.co.com/4C5g75N/Lazz-Pharma-Test-Summary.png)

## How to Use
1. **Clone the Repository:**
    ```bash
    git clone https://github.com/kawsar12759/ManualTesting-LazzPharma.git
    ```
2. **Navigate to Repository:**
    ```bash
    cd ManualTesting-LazzPharma
    ```
3. **Review Test Cases:**
Open the relevant test case files **Lazz Pharma Limited_TestCase_Writing.xlsx** to view the test cases.

4. **Execute Test Cases:**
Follow the steps outlined in the test cases to manually test the LazzPharma platform.

5. **Document Results:**
Update the **Actual Result** and **Status** fields for each test case based on your observations.

## Contributing
Contributions to this project are welcome! If you find any issues or want to add new test cases, please follow these steps:
1. Fork the repository.
2. Create a new branch for your changes.
3. Make your changes and commit them.
4. Submit a pull request with a detailed description of your changes.

***
For any questions or feedback, please contact the repository owner or open an issue on GitHub.

Happy Testing! 🚀
