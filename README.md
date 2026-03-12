# QA Manual Testing Portfolio – OpenCart

## Project Overview
This project demonstrates manual QA testing performed on the OpenCart e-commerce application.

The goal of this project is to showcase the QA testing workflow including:

- Test Scenario creation
- Test Case design
- Test Execution
- Bug Reporting
- Issue Analysis
- Enhancement Suggestions
- Test Summary Report

---

## Application Under Test

OpenCart v3.0.4.1  
Environment: Localhost (XAMPP)  
Browser: Google Chrome  
Operating System: Windows 10

---

## Modules Tested

- Register
- Login
- Add to Cart
- Shopping Cart
- Checkout

---

## Test Results

| Metric | Count |
|------|------|
| Total Test Cases | 74 |
| Passed | 70 |
| Failed | 3 |
| Blocked | 1 |

---

## Test Scope

The following core e-commerce functionalities were tested:

- User Registration
- User Login
- Product Selection
- Add to Cart
- Shopping Cart Management
- Checkout Process

The testing covered validation rules, error handling, and expected system behavior during normal and edge case scenarios.

---

## Bugs Identified

**BUG-OPENCART-01**  
Login validation does not trim leading and trailing whitespace in email input.

**BUG-OPENCART-02**  
System displays success message when quantity is set to 0.

**BUG-OPENCART-03**  
System allows negative quantity values in the cart.

Bug evidence screenshots are available in the `Bug Evidence` folder.

---

## Repository Structure

```
opencart-qa-manual-testing
│
├── OpenCart_QA_Testing.xlsx
├── README.md
└── Bug_Evidence
    ├── BUG-OPENCART-01_Login_Email_Whitespace.png
    ├── BUG-OPENCART-02_Quantity_0.png
    └── BUG-OPENCART-03_Negative_Quantity.png
```
