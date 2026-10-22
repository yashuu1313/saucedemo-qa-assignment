# SauceDemo QA Assignment

## Overview
Manual and automated testing of https://www.saucedemo.com/ (Swag Labs), covering login, product browsing, cart and checkout. I tested all four provided accounts (standard_user, locked_out_user, problem_user, performance_glitch_user), plus error_user and visual_user found on the login page. standard_user was used as the baseline for expected behavior.

## Repository contents
- `docs/` - Test plan, test cases (24 total) and bug report in one PDF
- `screenshots/` - Bug evidence, named by Bug ID (for example BUG01-a)
- `tests/` - Selenium automated tests (login, add to cart and checkout, locked-out user)

## Test environment
- Browser: Mozilla Firefox
- OS: Windows
- Device: laptop 
- Tested on: 22-10-2026

## Bug summary
| Bug ID | User | Summary | Severity |
-----------------------------------
| BUG01 | problem_user | Cart badge count does not match the items in the cart | High |
| BUG02 | problem_user | Last name field does not accept input, so checkout cannot be completed | High |
| BUG03 | error_user | Add and Remove fail for some products on the product list page | Medium |
| BUG04 | visual_user | Titles and buttons are misplaced on the product list | Medium |
| BUG05 | standard_user | Checkout accepts invalid first name, last name and postal code | Medium |
