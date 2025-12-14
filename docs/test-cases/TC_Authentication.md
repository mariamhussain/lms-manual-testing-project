# Test Cases – Authentication

| TC ID | Title | Precondition | Steps | Expected Result |
|------|--------|---------------|--------|------------------|
| TC-AUTH-01 | Login with valid credentials | User exists | 1. Open login page <br> 2. Enter valid email/password <br> 3. Click Login | User goes to dashboard |
| TC-AUTH-02 | Login with invalid password | User exists | Enter wrong password | Error message appears |
| TC-AUTH-03 | Register new user | Registration open | Fill all required fields + submit | Account created |
| TC-AUTH-04 | Forgot password | Email exists | Enter email → submit | Reset link sent |

