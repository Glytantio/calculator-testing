# Calculator Testing (QA Portfolio Project)

This repository contains manual and automated test cases for verifying the functionality of a basic calculator application.  
It is part of my QA portfolio to demonstrate skills in **test design**, **execution**, **bug reporting**, and (optional) **test automation**.

---

## 📖 Project Overview
The objective of this project is to ensure that the calculator performs arithmetic and special operations correctly, handles edge cases gracefully, and maintains a user-friendly experience.

---

## 🛠 Tools & Technologies
- **Manual Testing:** TestRail / Google Sheets / Excel
- **Automation (Optional):** Selenium, Cypress, or Playwright
- **Programming Language:** Python / JavaScript
- **Bug Tracking:** Jira / GitHub Issues

---

## ✅ Test Scenarios
- **Basic Operations**
  1. Addition of two numbers
  2. Subtraction of two numbers
  3. Multiplication of two numbers
  4. Division of two numbers
- **Edge Cases**
  5. Division by zero
  6. Operations with negative numbers
  7. Decimal calculations
  8. Very large number calculations
- **Functional Tests**
  9. Clear (C/AC) button functionality
  10. Chained operations (`2 + 3 × 4`)
  11. Order of operations (BODMAS/PEMDAS)
  12. Continuous operations without pressing equals

---

## 📂 Repository Structure
calculator-testing/ ├── README.md                # Project documentation ├── manual-test-cases.xlsx   # Manual test scenarios ├── automation/              # Automation scripts (optional) └── bug-reports/             # Defects with screenshots

## 🚀 Running Automation Tests (If Added)
Example for Python + Selenium:
```bash
pip install -r requirements.txt
python automation/test_calculator.py
