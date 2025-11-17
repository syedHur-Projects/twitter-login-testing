# Test Scenarios – Twitter Login

| Scenario ID   | Scenario Description                                                           | Priority | Test Type      |
|---------------|---------------------------------------------------------------------------------|----------|----------------|
| TS-LOGIN-01   | Verify user can log in with valid email/username/phone and correct password    | High     | Functional     |
| TS-LOGIN-02   | Verify user cannot log in with valid email and incorrect password              | High     | Negative       |
| TS-LOGIN-03   | Verify user cannot log in with unregistered email/username                     | High     | Negative       |
| TS-LOGIN-04   | Verify login is not allowed when username/email field is left empty            | Medium   | Negative       |
| TS-LOGIN-05   | Verify login is not allowed when password field is left empty                  | Medium   | Negative       |
| TS-LOGIN-06   | Verify appropriate error message is displayed for invalid credentials          | High     | Functional/UI  |
| TS-LOGIN-07   | Verify "Forgot password?" link redirects to password recovery page             | Medium   | Functional     |
| TS-LOGIN-08   | Verify user is redirected to Home/Timeline after successful login              | High     | Functional     |
| TS-LOGIN-09   | Verify password characters are masked while typing                             | Low      | UI/Security    |
| TS-LOGIN-10   | Verify user remains logged in after refreshing the browser after login         | Medium   | Functional     |
