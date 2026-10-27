# Mini Project: Login DDT
# 🏦 ParaBank Login Portal - Manual Data-Driven Testing

## 📌 Project Overview
* **Project Title:** Manual Data-Driven Testing & Test Cases for a Banking Login Portal
* **Target Site:** [ParaBank Portal](https://parabank.parasoft.com/parabank/index.htm)
* **Concepts Used:** Test Case Writing, Positive & Negative Scenarios, Boundary Analysis, Expected vs. Actual Results, Data-Driven Testing (Excel/CSV).

---

## 📖 User Story
**Title:** User Login to Banking System

> **As a** registered bank customer,  
> **I want to** log in to my banking account using my username and password,  
> **So that** I can securely access my account information and banking services.

### ✅ Acceptance Criteria (AC)
1. **AC#1:** The user must enter a valid username and password.
2. **AC#2:** The system must allow login when the credentials are correct.
3. **AC#3:** The system must display an error message when the username or password is incorrect.
4. **AC#4:** The system must not allow login if the required fields are empty.
5. **AC#5:** The password must be masked while typing.
6. **AC#6:** The system must protect the account against repeated failed login attempts.
7. **AC#7:** After successful login, the user must be redirected to the dashboard (Accounts Overview).
8. **AC#8:** The system must provide a secure way to log out.
9. **AC#9:** The system must properly handle maximum character limits and reject excessively long inputs without crashing.

---

## 👥 Team Members & Testing Scope
| Member Name | Assigned Testing Scope | Covered ACs | Test Cases |
| :--- | :--- | :--- | :--- |
| **Ibrahim Asad** | Valid Login Flow, Password Masking & Session/Logout Security | AC#1, AC#2, AC#5, AC#7, AC#8 | 4 Test Cases |
| **Salma** | Invalid Credentials & Username/Password Mismatch | AC#3 | 4 Test Cases |
| **Mazen Yasser** | Case Sensitivity & Special Characters Handling | AC#3 | 3 Test Cases |
| **Mohamed Sameh** | Empty Fields & Whitespace Validation | AC#4 | 4 Test Cases |
| **Mohamed Hany** | Long Inputs, SQLi Payload & Account Lockout Security | AC#6, AC#9 | 4 Test Cases |

---

## 📊 Test Execution Summary
* **Total Test Cases:** 19
* **Passed:** 18 ✅
* **Failed:** 1 ❌ (`BUG-001`: Account is not locked after 5 consecutive failed login attempts - Violates `AC#6`)

---

## 📂 Repository Deliverables
* 📊 **[ParaBank_Login_Testing.xlsx](./ParaBank_Login_Testing.xlsx):** Full formatted Excel workbook containing all test cases, test data, and individual team tabs.
* 📄 **[ParaBank_Login_TestCases.csv](./ParaBank_Login_TestCases.csv):** Raw CSV data file for direct preview on GitHub.
* 🔗 **[Google Sheets Live Link](#):** *(https://docs.google.com/spreadsheets/d/1cBLno-nI9B-NyCrAqrBZVejvIDtSnvDPVxZMUROfTR4/edit?usp=sharing)*
