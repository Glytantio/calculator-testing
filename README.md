# Calculator Testing (QA Portfolio Project)

This repository contains manual and automated test cases for verifying the functionality of a basic calculator application.  
It is part of my QA portfolio to demonstrate skills in **test design**, **execution**, **bug reporting**, and (optional) **test automation**.

---

## 📖 Project Overview
The objective of this project is to ensure that the calculator performs arithmetic and special operations correctly, handles edge cases gracefully, and maintains a user-friendly experience.

---

## 🛠 Tools & Technologies
- **Manual Testing Documentation:** Markdown (`.md` files on GitHub`)
- **Automation (Optional):** Selenium, Cypress, or Playwright
- **Programming Language (Optional):** Python / JavaScript
- **Bug Tracking:** GitHub Issues

---

## ✅ Test Scenarios

### Basic Operations
1. Addition of two numbers
2. Subtraction of two numbers
3. Multiplication of two numbers
4. Division of two numbers

### Edge Cases
1. Division by zero
2. Operations with negative numbers
3. Decimal calculations
4. Very large number calculations

### Functional Tests
1. Clear (C/AC) button functionality
2. Chained operations (e.g., `2 + 3 × 4`)
3. Order of operations (PEMDAS/BODMAS)
4. Continuous operations without pressing equals
---

## 📂 Repository Structure

calculator-testing/ ├── README.md                 # Project overview and instructions ├── manual-test-cases.md      # Manual test scenarios in Markdown format ├── bug-reports.md            # Example defect reports ├── automation/               # Automation scripts (optional) └── docs/                     # (Optional) Extra QA documentation like test plans

---

## 📄 Documentation
- [Test Plan](test-plan.md)  
- [Manual Test Cases](manual-test-cases.md)  
- [Bug Reports](bug-reports.md)  

---

## 🚀 Running Automation Tests
Example for Python + Selenium:
```bash
pip install -r requirements.txt
python automation/test_calculator.py
