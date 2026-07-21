# Bug Report Log

| Bug ID | Title | Steps to Reproduce | Expected Result | Actual Result | Severity | Priority | Environment |
|---|---|---|---|---|---|---|---|
| BUG_001 | Unclear and unprofessional error message shown for locked-out user | 1. Go to saucedemo.com login page 2. Enter username "locked_out_user" 3. Enter password "secret_sauce" 4. Click Login button | System should display a clear, professional error message explaining the account is locked, and ideally guide the user on next steps (e.g. "Your account has been locked. Please contact support.") | System displays: "Epic sadface: Sorry, this user has been locked out." — message is informal, doesn't explain why, and gives no guidance on next steps | Low | Low | Chrome Version 150.0.7871.101 |