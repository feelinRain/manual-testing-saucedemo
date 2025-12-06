# Manual Testing Project: SauceDemo Web Application

## Objective
To demonstrate skills in test design, execution, and bug reporting for a web application.

## Test Object
[SauceDemo](https://www.saucedemo.com/) - a demo e-commerce site for practice.

## Testing Scope
*   Functional testing: Login, product catalog, cart, checkout.
*   UI/UX testing: Layout, responsiveness.
*   Basic validation: Error messages, field boundaries.

## Artifacts
*   📄 [Test Cases](/test_cases/) - Checklist and detailed test cases.
*   🐞 [Bug Reports](/bug_reports/) - Formatted issue reports.
*   📊 [Test Summary](/test_summary/test_summary.md) - Final report.

## Tools Used
*   Chrome DevTools
*   GitHub (for documentation)
*   Microsoft Excel / Google Sheets (for matrices)

## Key Finding
During testing, a **critical security/logic flaw** was discovered: users can access the order confirmation page without completing a purchase by manually navigating to `/checkout-complete.html`. This demonstrates inadequate state validation in the checkout workflow.

See detailed report: [Bug Report: Direct Access to Checkout Complete](/bug_reports/BR_01_direct_access_checkout.md)
