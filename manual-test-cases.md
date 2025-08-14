# Manual Test Cases – Calculator Testing

This document contains manual test cases for verifying the functionality of a basic calculator application.  
It is part of the **Calculator Testing QA Portfolio Project**.

---

## 📋 Test Cases

| Test Case ID | Test Scenario | Test Steps | Expected Result | Test Type | Execution Status | Remarks |
|--------------|--------------|------------|-----------------|-----------|------------------|---------|
| **TC001** | Addition of two positive integers | Open calculator → Enter 5 → Press `+` → Enter 3 → Press `=` | `8` is displayed | Functional | Not Executed | |
| **TC002** | Subtraction of two positive integers | Open calculator → Enter 10 → Press `-` → Enter 4 → Press `=` | `6` is displayed | Functional | Not Executed | |
| **TC003** | Multiplication of two positive integers | Open calculator → Enter 7 → Press `×` → Enter 6 → Press `=` | `42` is displayed | Functional | Not Executed | |
| **TC004** | Division of two positive integers | Open calculator → Enter 20 → Press `÷` → Enter 5 → Press `=` | `4` is displayed | Functional | Not Executed | |
| **TC005** | Division by zero | Open calculator → Enter 8 → Press `÷` → Enter 0 → Press `=` | Error message or `"Infinity"` displayed | Functional | Not Executed | |
| **TC006** | Negative number operation | Open calculator → Enter `-5` → Press `+` → Enter 3 → Press `=` | `-2` is displayed | Functional | Not Executed | |
| **TC007** | Decimal calculation | Open calculator → Enter 2.5 → Press `+` → Enter 3.1 → Press `=` | `5.6` is displayed | Functional | Not Executed | |
| **TC008** | Very large number calculation | Open calculator → Enter `99999999` → Press `×` → Enter `99999999` → Press `=` | Result is displayed without overflow | Functional | Not Executed | |
| **TC009** | Clear button (C/AC) functionality | Open calculator → Enter 5 → Press `+` → Enter 3 → Press `C/AC` | Display resets to `0` | Functional | Not Executed | |
| **TC010** | Chained operations | Open calculator → Enter 2 → Press `+` → Enter 3 → Press `×` → Enter 4 → Press `=` | `14` is displayed (BODMAS applied) | Functional | Not Executed | |
| **TC011** | Order of operations (BODMAS/PEMDAS) | Open calculator → Enter `2 + 3 × 4 =` | `14` is displayed | Functional | Not Executed | |
| **TC012** | Continuous operations without equals | Open calculator → Enter `5 + 3 + 2 =` | `10` is displayed | Functional | Not Executed | |

---

## 🛠 Notes
- **Test Environment:** Windows 11 Calculator App / Online Web Calculator
- **Test Data:** Mix of positive, negative, decimal, and large numbers
- **Precondition:** Calculator is reset before each test
