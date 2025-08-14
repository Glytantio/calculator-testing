# Test Plan – Calculator Application

## 1. Introduction
This test plan outlines the strategy, objectives, scope, and approach for testing the Calculator application.  
The primary goal is to validate that all calculator functions operate correctly, handle edge cases, and maintain usability.

---

## 2. Objectives
- Verify the accuracy of all basic arithmetic operations.
- Ensure the calculator handles special and edge cases gracefully.
- Confirm the application’s functional reliability and user experience.
- Identify and document defects clearly.

---

## 3. Scope

### In-Scope
- Basic arithmetic operations: addition, subtraction, multiplication, division.
- Functional operations: clear button, chained operations, order of operations.
- Edge cases: division by zero, large number handling, decimal operations, negative numbers.

### Out-of-Scope
- Scientific functions (e.g., trigonometry, logarithms).
- Performance/load testing.
- Multi-platform testing (only one environment will be covered for this demo).

---

## 4. Test Approach
- **Manual Testing:** Execute predefined test cases documented in [`manual-test-cases.md`](manual-test-cases.md).
- **Bug Reporting:** Log all defects in [`bug-reports.md`](bug-reports.md) and optionally in GitHub Issues.
- **Test Levels:** Functional Testing, Regression Testing.
- **Test Types:** Positive and Negative Testing.

---

## 5. Test Environment
- **Device:** Desktop or mobile device (web or app version of calculator)
- **OS:** Windows 10 / Android 14 (example)
- **Browser:** Google Chrome (latest version) – if web-based
- **Tools:** GitHub Markdown for documentation

---

## 6. Test Deliverables
- Test Plan (`test-plan.md`)
- Manual Test Cases (`manual-test-cases.md`)
- Bug Reports (`bug-reports.md`)
- Optional Automation Scripts (`automation/`)

---

## 7. Entry Criteria
- Calculator application build is deployed and stable.
- All required features for testing are available.

---

## 8. Exit Criteria
- All planned test cases executed.
- All critical defects resolved.
- Test summary prepared.

---

## 9. Risks & Mitigation
- **Risk:** Calculator may not have all expected features.
  - **Mitigation:** Adjust test cases and scope based on available functionality.
- **Risk:** Limited test environment coverage.
  - **Mitigation:** Focus on core functionality validation.

---

## 10. Approval
**Tester:** _Dreico Karlo Librodo_  
**Date:** _08/15/2025_
