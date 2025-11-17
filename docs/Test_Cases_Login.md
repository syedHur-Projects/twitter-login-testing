# Test Cases – Twitter Login

---

## TC-LOGIN-001 – Valid login with correct credentials

- **Story ID:** AUTH-1
- **Scenario ID:** TS-LOGIN-01
- **Test Type:** Functional
- **Title:** Verify user can log in with valid email/username/phone and correct password

**Preconditions:**
- User has a valid, active Twitter account.
- Test data is available (email/username/phone and password).

**Test Data:**
- Username/Email/Phone: `<valid_user>`
- Password: `<valid_password>`

**Steps:**
1. Open a browser and navigate to `https://x.com/login`.
2. Enter a valid email/username/phone in the “Phone, email, or username” field.
3. Enter the correct password in the password field.
4. Click the “Log in” button.

**Expected Result:**
- User is successfully logged in and redirected to the Home/Timeline page.
- No error message is displayed.

**Actual Result:**
- (To be filled during execution)

**Status:**
- (Pass/Fail)

**Comments:**
- (Optional)

---

## TC-LOGIN-002 – Login with invalid password

- **Story ID:** AUTH-1
- **Scenario ID:** TS-LOGIN-02
- **Test Type:** Negative
- **Title:** Verify user cannot log in with valid email and incorrect password

**Preconditions:**
- User has a valid, active Twitter account.

**Test Data:**
- Email/Username: `<valid_user>`
- Password: `WrongPass123` (invalid)

**Steps:**
1. Go to `https://x.com/login`.
2. Enter a valid email/username in the “Phone, email, or username” field.
3. Enter an incorrect password in the password field.
4. Click the “Log in” button.

**Expected Result:**
- User is not logged in.
- An appropriate error message is displayed indicating invalid credentials.
- User remains on the login screen.

**Actual Result:**
- (To be filled during execution)

**Status:**
- (Pass/Fail)

**Comments:**
- (Optional)

---

## TC-LOGIN-003 – Login with empty username/email

- **Story ID:** AUTH-1
- **Scenario ID:** TS-LOGIN-04
- **Test Type:** Negative
- **Title:** Verify login fails when username/email field is left empty

**Preconditions:**
- None.

**Test Data:**
- Username/Email: (leave blank)
- Password: `<valid_password>`

**Steps:**
1. Navigate to `https://x.com/login`.
2. Leave the “Phone, email, or username” field empty.
3. Enter a valid password in the password field.
4. Click the “Log in” button.

**Expected Result:**
- Login attempt is not successful.
- Either:
  - A validation message appears near the username/email field, or
  - An error message indicates that the identifier field is required.

**Actual Result:**
- (To be filled during execution)

**Status:**
- (Pass/Fail)

**Comments:**
- (Optional)

---

## TC-LOGIN-004 – Login with empty password

- **Story ID:** AUTH-1
- **Scenario ID:** TS-LOGIN-05
- **Test Type:** Negative
- **Title:** Verify login fails when password field is left empty

**Preconditions:**
- None.

**Test Data:**
- Username/Email: `<valid_user>`
- Password: (leave blank)

**Steps:**
1. Navigate to `https://x.com/login`.
2. Enter a valid username/email in the “Phone, email, or username” field.
3. Leave the password field empty.
4. Click the “Log in” button.

**Expected Result:**
- Login attempt is not successful.
- Either:
  - A validation message appears near the password field, or
  - An error message indicates that the password is required.

**Actual Result:**
- (To be filled during execution)

**Status:**
- (Pass/Fail)

**Comments:**
- (Optional)

---

## TC-LOGIN-005 – Forgot password link

- **Story ID:** AUTH-1
- **Scenario ID:** TS-LOGIN-07
- **Test Type:** Functional
- **Title:** Verify "Forgot password?" link redirects to password recovery page

**Preconditions:**
- None.

**Test Data:**
- Not required.

**Steps:**
1. Navigate to `https://x.com/login`.
2. Click on the “Forgot password?” link.

**Expected Result:**
- User is redirected to the Twitter password recovery flow/page.
- Page should request email/username/phone or similar recovery identifier.

**Actual Result:**
- (To be filled during execution)

**Status:**
- (Pass/Fail)

**Comments:**
- (Optional)
