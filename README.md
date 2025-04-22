## Project Overview

This repository contains both manual test case documentation and API test case definitions for the AutomationExercise application and related endpoints.

## Folder Structure

- `/Manual-Testing/`
  - `TC01/`
    - `TC01.md` — Detailed steps for “Register a New User”
  - `TC02/`
    - `TC02.md` — Detailed steps for “Login with Valid Credentials”
  - …
- `/API-Testing/`
  - `API01/`
    - `API01.md` — Test cases for GET `/api/productsList`
  - `API02/`
    - `API02.md` — Test cases for POST `/api/productsList`
  - …

### Manual Testing

- 26 Test Cases written in professional format
- Each case includes: Objective, Preconditions, Steps, Expected/Actual Results, Test Data & Status

### API Testing

- 14 REST API Test Cases using typical request/response formats
- Validates status codes, payloads, and error handling

## Test Coverage Summary

- _User Registration/Login_: Covered
- _Cart, Checkout, Order Placement_: Covered
- _Negative Testing_: Included for invalid logins, method not allowed, and missing parameters
- _Gaps Identified_:
  - Password Recovery
  - Filtering & Sorting
  - Wishlist Feature
  - User Profile Editing
  - Email Verification

---

## Author

_Name:_ Nipuni Navodya  
_Challenge:_ AgroWorld QA Internship - Challenge 10  
*Date:* April 2025

## How to Use

1. Clone this repository.
2. Browse to the folder of interest:
   - Manual test cases under [Manual-Testing](./Manual-Testing/).
   - API test definitions under [API-Testing](./API-Testing/).
3. Follow the instructions in each `README.md` to execute tests or review results.
