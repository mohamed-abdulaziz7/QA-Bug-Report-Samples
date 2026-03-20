# QA Bug Report Samples

## Overview

This repository contains **bug report samples** documented during manual exploratory testing on **Swag Labs (saucedemo.com)**.

Each bug report is written in a structured format to clearly communicate:

* What the issue is
* How to reproduce it
* What was expected vs what actually happened
* Supporting evidence (screenshots)
* Severity and priority assessment

## Test Accounts Used

The following test accounts were used during testing:

* `standard_user`
* `problem_user`
* `error_user`
* `visual_user`

## Scope of Testing

The main testing focus areas were:

* **Inventory page** (Add to cart / Remove)
* **Cart page**
* **Products Sorting**
* Additional issues found during related navigation/checkout steps were also documented where applicable.

## Bug Report Format

All bug reports follow this format (columns in the bug report sheet):

* **Bug_ID**
* **Title**
* **Test Account**
* **Module**
* **Preconditions**
* **Steps to Reproduce**
* **Expected Result**
* **Actual Result**
* **Screenshot**
* **Severity**
* **Priority**
* **Assign Person**
* **Status**
* **Comments**

## Repository Structure

* `bug-reports/Bug_Report_Samples.xlsx`
  Contains all documented bugs using the structured format above.

* `screenshots/`
  Contains screenshot evidence for each bug report.
  Screenshots are named using the matching **Bug_ID** (e.g., `BUG-001.png`).

## Notes

* Bugs were documented using manual exploratory testing.
* Severity and priority are assigned based on impact to core functionality and user flow.
* "Assign Person" is kept as a generic value (e.g., **QA Team**) since this is a portfolio sample repository.
