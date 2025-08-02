# SauceDemo Manual Testing Project

This repository contains manual test cases and reported bugs for the [SauceDemo](https://www.saucedemo.com/) e-commerce demo website.

## 🔍 Purpose

The goal of this project is to demonstrate manual testing skills, including test case writing, exploratory testing, bug reporting, and test documentation.

Currently, only the `standard_user` profile is covered. Future plans include testing other profiles such as:
- `problem_user`
- `performance_glitch_user`
- `error_user`
- `visual_user`

---

## 📂 Folder Structure

- `test-cases/`  
 Files with manually written test scenarios for each user type. Each file includes:
  - Functional tests (login, cart, checkout)
  - Negative test cases
  - Edge cases (e.g. input validation)

- `bug-reports/`  
  Bug descriptions organized by user profile. Each bug contains:
  - Bug ID
  - Summary
  - Steps to reproduce
  - Expected vs Actual results
  - Screenshot 

---

## 🧪 Covered Features (standard_user)

- Login functionality
- Add to cart / Remove from cart
- Checkout flow
- Field validation (e.g., Zip/Postal Code)
- UI elements (buttons, layout, navigation)

---

## 📋 Example Bug

**Bug ID:** #12  
**Summary:** User can input letters and special characters for "Zip/Postal Code" and proceed to checkout  
**Expected:** Validation should prevent non-numeric values  
**Actual:** Checkout proceeds even with invalid input

---

## 🚧 Tools Used

- Browser: Google Chrome
- Documentation: Qase.io & Markdown
- Reporting: Manual (via GitHub)

---

## 💡 Future Improvements

- Add test cases and bugs for other user profiles
- Integrate simple UI test automation with Selenium or Cypress

---

## 💻 Author

Marina Jakovljevic  
*Manual QA Tester in training, passionate about UI/UX and quality assurance*

