# 🐞 Bug Report - One Finance Procurement Module

This repository contains a QA bug report for the **Procurement Module** of the **E-requisition** system. The document outlines issues identified during manual testing of procurement-related workflows and UI components. The goal is to ensure that the procurement processes are stable, accurate, and user-friendly.

---

## 📋 Project Overview

The **Procurement Module** manages key procurement functions such as vendor onboarding, purchase requisitions, quotations, purchase orders, and goods receipts. This QA report highlights functional, UI, and performance-related bugs discovered during hands-on testing.

---

## ✅ Test Summary

| Category              | Count   |
|-----------------------|---------|
| Total Test Cases      | 80      |
| Test Cases Passed     | 51      |
| Test Cases Failed     | 29      |
| Total Bugs Reported   | 29      |
| Critical Bugs         | 18      |
| Minor Bugs            | 11      |
| Test Coverage         | 100%    |

---

## 📁 File Structure

- `Bug report of Procurement.xlsx`  
  This file includes:
  - Bug ID
  - Bug Title / Summary
  - Module Name
  - Steps to Reproduce
  - Expected vs Actual Results
  - Severity (Critical / Minor)
  - Status (Open / Fixed / In Progress)
  - Screenshots (if any)
  - Reported By & Report Date

---

## 🔍 Sample Bug Entry

| Field              | Example Value                                             |
|-------------------|-----------------------------------------------------------|
| **Bug ID**         | BUG-PR-006                                                |
| **Module**         | Quotation Management                                      |
| **Summary**        | System crashes when uploading quotation attachments       |
| **Severity**       | Critical                                                  |
| **Steps to Reproduce** | 1. Navigate to Quotation page <br>2. Upload a PDF file <br>3. Click "Save" |
| **Expected Result** | Quotation saved with attachment                         |
| **Actual Result**   | Application crashes and returns to dashboard             |
| **Status**         | Open                                                      |

---

## 🔧 Modules Tested

- Vendor Master
- Purchase Requisition
- Quotation Management
- Purchase Order
- Goods Receipt Note
- Approval Workflow

---

## 🎯 Purpose

This bug report was created to:
- Log and communicate issues effectively to the development team
- Improve the reliability and usability of the Procurement module
- Track the status of fixes and verify them through retesting
- Help the product meet business goals with fewer post-release issues

---

## 🙋‍♂️ Author

**Name**: Md. Sadman Shahrieal Pieal  
**Role**: QA Engineer  
**Email**: sadmanpieal@gmail.com  
**Date**: December 2024

---

## 🧭 Future Enhancements

- Automate common flows using Cypress or Selenium
- Implement bug-to-issue tracking with JIRA or GitHub Issues
- Create summary charts for bug trends and test coverage
- Include integration and performance testing for bulk operations

---

## 📌 Disclaimer

This project is intended strictly for testing and quality assurance documentation. All findings and content are confidential and the property of the One Finance QA team.

