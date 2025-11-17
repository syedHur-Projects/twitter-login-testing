# Test Plan – Twitter Login

## 1. Introduction
This test plan covers manual testing of the Twitter (X) login functionality on the web login page (`https://x.com/login`).

## 2. Scope
**In Scope**
- Login using email/username/phone + password
- Input validation and error messages
- Redirect to Home/Timeline on successful login
- "Forgot password?" link navigation
- Basic UI checks on the login page
- Basic session behavior (stay logged in after login)

**Out of Scope**
- Signup and account creation
- Full password reset process (email/SMS backend)
- Two-factor authentication (2FA)
- Mobile app (Android/iOS)
- Performance and load testing

## 3. Test Types
- Functional testing
- Negative testing
- UI/UX testing
- Basic security checks (password masking, logout behavior)
- Regression baseline (re-run key tests after changes)

## 4. Test Environment
- URL: https://x.com/login
- Environment: Production
- Browser: Chrome (latest)
- OS: Windows 10 / 11 (local machine)
- Test Account: Personal Twitter test account (credentials not stored in repo)

## 5. Entry Criteria
- Login page is accessible
- Test account exists and is active

## 6. Exit Criteria
- All high priority test cases are executed
- All Critical/High severity bugs are fixed or accepted with mitigation
- No open blocker defects related to login

## 7. Deliverables
- Test_Scenarios_Login.md
- Test_Cases_Login.md
- Bug_Reports.md (and Jira bugs)
- Test_Summary_Twitter_Login.md
