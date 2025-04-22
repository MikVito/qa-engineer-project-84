### Hexlet tests and linter status:
[![Actions Status](https://github.com/MikVito/qa-engineer-project-84/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/MikVito/qa-engineer-project-84/actions)


# 🛒 Online Store Testing

This project is dedicated to testing a small online store that sells products.
The testing process includes verifying functional correctness, usability, security,
responsiveness, and cross-browser compatibility.

Tested application: [Hexlet Products Store](https://hexlet-products-store.vercel.app/)

### 🎯 Project Goals

 - Get familiar with the application under test and its features
 - Perform test analysis and create test cases
 - Prepare bug reports
 - Execute tests and document the results
 - Perform regression testing after bug fixes

### 🔍 Main Testing Areas

**Functional Testing**
 - Product search and filtering
 - Adding products to the cart
 - Placing an order and proceeding to the payment page
 - Correct display of product information

**Non-Functional Testing**
 - Responsiveness: proper display on mobile devices, tablets, and PCs
 - Cross-browser compatibility: testing in different browsers and their versions
 - Performance: checking load speed
 - Usability: ease of use of the interface

**Security**
 - Protection against XSS attacks
 - Protection against SQL injections

### 📋 Test Documentation Formats
Test cases, bug reports, and test reports are written in YAML format

**List of files:**
 - requirements.yml – functional, non-functional, and implicit requirements
 - test-cases.yml – list of test cases with execution steps
 - bugreports.yml – list of discovered bugs
 - testing-report.yml – report on the status of test case execution
 - regress-report.yml – regression testing report

### 🛠 Tools

 - GitHub – for managing test documentation and bug reports
 - DevTools – for analyzing network requests, performance, and debugging
 - YAML Lint – for validating YAML files
 - BrowserStack – for cross-browser testing