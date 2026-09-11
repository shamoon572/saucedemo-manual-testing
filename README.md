# 🧪 SauceDemo Manual Software Testing Project

![Testing](https://img.shields.io/badge/Testing-Manual-blue?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-green?style=flat-square)
![Platform](https://img.shields.io/badge/Platform-Web%20Application-lightblue?style=flat-square)

---

## 📋 Overview

A **comprehensive manual software testing project** for the **SauceDemo (Swag Labs)** web application. This repository documents the entire testing lifecycle from requirements gathering to defect reporting and final test summary.

**Application Under Test:** [SauceDemo - Swag Labs](https://www.saucedemo.com/)

---

## 📂 Project Structure

```
saucedemo-manual-testing/
│
├── 01_Requirements/              # Requirements & Scope Analysis
│   ├── Business_Requirements.md
│   ├── Scope_Document.md
│   └── Out_of_Scope.md
│
├── 02_Test_Plan/                # Testing Strategy & Plan
│   ├── Test_Plan.md
│   ├── Test_Approach.md
│   ├── Entry_Exit_Criteria.md
│   └── Schedule.md
│
├── 03_Test_Scenarios/           # High-Level Test Scenarios
│   ├── Functional_Scenarios.md
│   ├── User_Journey_Scenarios.md
│   └── Edge_Case_Scenarios.md
│
├── 04_Test_Cases/               # Detailed Test Cases
│   ├── TC_Login_Module.xlsx
│   ├── TC_Product_Catalog.xlsx
│   ├── TC_Cart_Checkout.xlsx
│   ├── TC_Payment.xlsx
│   └── TC_User_Management.xlsx
│
├── 05_Test_Data/                # Test Data & Credentials
│   ├── Test_Data.xlsx
│   ├── Test_Users.md
│   └── Test_Scenarios_Data.csv
│
├── 06_Test_Execution/           # Test Execution Results
│   ├── Test_Execution.xlsx
│   ├── Execution_Summary.md
│   └── Test_Metrics.md
│
├── 07_Defect_Reports/           # Defect Log & Reports
│   ├── Defect_Log.xlsx
│   ├── Bug_Report_Template.md
│   └── Severity_Classification.md
│
├── 08_RTM/                      # Requirement Traceability Matrix
│   ├── RTM.xlsx
│   └── Traceability_Analysis.md
│
├── 09_Test_Summary/             # Final Test Summary & Report
│   ├── Test_Summary_Report.md
│   ├── Test_Metrics.xlsx
│   ├── Pass_Fail_Analysis.md
│   └── Recommendations.md
│
├── 10_Screenshots/              # Test Execution Evidence
│   ├── Login_Tests/
│   ├── Product_Tests/
│   ├── Cart_Tests/
│   ├── Checkout_Tests/
│   └── Failed_Test_Evidence/
│
└── README.md                    # This file

```

---

## 📌 Folder Descriptions

| Folder | Purpose |
|--------|---------|
| **01_Requirements** | Defines what needs to be tested and scope boundaries |
| **02_Test_Plan** | Overall testing strategy, approach, and execution plan |
| **03_Test_Scenarios** | High-level user workflows and test scenarios |
| **04_Test_Cases** | Detailed test cases with steps and expected results |
| **05_Test_Data** | Test credentials, data sets, and test scenarios |
| **06_Test_Execution** | Actual test run results and execution logs |
| **07_Defect_Reports** | Bug reports, severity levels, and defect tracking |
| **08_RTM** | Traceability between requirements and test cases |
| **09_Test_Summary** | Final metrics, pass/fail analysis, and recommendations |
| **10_Screenshots** | Screenshots and visual evidence of test execution |

---

## 🚀 Getting Started

### Prerequisites
- Web Browser (Chrome/Firefox/Safari/Edge)
- SauceDemo Account (use provided test credentials)
- Spreadsheet Software (Excel/Google Sheets)
- Screenshot Tool

### How to Use This Repository

1. **Read the Requirements** → Start with `01_Requirements/`
2. **Review Test Plan** → Check `02_Test_Plan/Test_Plan.md`
3. **Execute Test Cases** → Use `04_Test_Cases/` files
4. **Log Results** → Update `06_Test_Execution/Test_Execution.xlsx`
5. **Report Defects** → Use template in `07_Defect_Reports/`
6. **Capture Evidence** → Add screenshots to `10_Screenshots/`

---

## 📊 Test Execution Workflow

```
Requirements Analysis
        ↓
Test Planning
        ↓
Test Case Design
        ↓
Test Data Preparation
        ↓
Manual Test Execution
        ↓
Defect Logging
        ↓
Evidence Documentation
        ↓
Test Summary Report
```

---

## 🎯 Test Coverage Areas

- ✅ **Login & Authentication** - Valid/Invalid credentials, session management
- ✅ **Product Catalog** - Browse, search, filter, sorting
- ✅ **Shopping Cart** - Add/Remove items, quantity updates
- ✅ **Checkout Process** - Cart review, user info, payment
- ✅ **User Account** - Profile management, order history
- ✅ **Performance & UI** - Load times, responsiveness, cross-browser
- ✅ **Negative Testing** - Error handling, edge cases, boundaries

---

## 📈 Metrics & Reporting

- **Total Test Cases** → [Update in `06_Test_Execution/`]
- **Executed** → [Update as you test]
- **Passed** → [Auto-calculated]
- **Failed** → [With defect references]
- **Pass Rate** → [Calculated: Passed/Total × 100%]
- **Defect Density** → [Defects/Test Cases]

---

## 🐛 Defect Reporting

For every failed test case:

1. **Create a screenshot** → `TC-XXX_FAILED.png`
2. **Log the defect** → Add row to `Defect_Log.xlsx`
3. **Use standard template** → See `07_Defect_Reports/Bug_Report_Template.md`
4. **Link to RTM** → Reference requirement ID

**Example Defect Naming:**
- `TC-LOGIN-001_FAILED.png`
- `TC-CHECKOUT-003_FAILED.png`
- `TC-PAYMENT-002_FAILED.png`

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|------|-------|
| **Excel/Google Sheets** | Test case management, execution tracking |
| **SauceDemo** | Application under test |
| **Screenshot Tool** | Evidence collection (Snagit/Greenshot/Built-in) |
| **GitHub** | Version control & documentation |

---

## 📝 Documentation Standards

- **Format:** Markdown for docs, Excel for data tracking
- **Naming Convention:** `TC-[MODULE]-[NUMBER]` for test cases
- **Date Format:** YYYY-MM-DD
- **Status Values:** Not Executed / Pass / Fail / Blocked / N/A

---

## 👤 Team Information

| Role | Name | Email |
|------|------|-------|
| QA Lead | - | - |
| Test Engineer | shamoon572 | - |
| Test Reviewer | - | - |

---

## 📅 Timeline

| Phase | Start Date | End Date | Status |
|-------|-----------|----------|--------|
| Requirements Review | - | - | Pending |
| Test Planning | - | - | Pending |
| Test Case Development | - | - | Pending |
| Test Execution | - | - | Pending |
| Defect Reporting | - | - | Pending |
| Test Summary | - | - | Pending |

---

## 🔍 Quality Metrics to Track

- **Test Case Density** → Test cases per feature
- **Defect Severity Distribution** → Critical/High/Medium/Low %
- **Test Execution Progress** → % of tests executed
- **Defect Resolution Time** → Average time to fix
- **Test Effectiveness** → % of defects caught during testing

---

## ✨ Skills Demonstrated

- ✓ Requirements analysis & scope management
- ✓ Test plan development
- ✓ Test case design (positive & negative testing)
- ✓ Test data preparation
- ✓ Manual test execution
- ✓ Defect documentation
- ✓ Requirement Traceability Matrix (RTM)
- ✓ Test reporting & metrics
- ✓ Screenshot/evidence collection
- ✓ GitHub documentation

---

## 📚 Reference Materials

- **Testing Standards:** ISTQB Best Practices
- **Test Case Template:** See `04_Test_Cases/`
- **Defect Report Template:** See `07_Defect_Reports/`
- **RTM Template:** See `08_RTM/`

---

## 🤝 Contributing

When updating this repository:

1. Follow the folder structure
2. Use consistent naming conventions
3. Document changes in relevant README files
4. Maintain version control discipline
5. Update `09_Test_Summary/` with latest metrics

---

## 📞 Contact & Support

For questions regarding this testing project, create an **Issue** in this repository or contact the QA team.

---

## 📄 License

This project is provided as-is for educational and testing purposes.

---

**Last Updated:** 2026-09-11 | **Repository:** [shamoon572/saucedemo-manual-testing](https://github.com/shamoon572/saucedemo-manual-testing)
