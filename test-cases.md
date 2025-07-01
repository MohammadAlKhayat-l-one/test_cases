# E-Commerce Website Test Cases

---

## 🔐 Feature 1: Authentication

### Test Case 1: Successful User Registration
- **Preconditions:** User is on the registration page.
- **Steps:**
  1. Enter a valid email address.
  2. Enter a valid password.
  3. Submit the registration form.
- **Expected Result:** User account is created and user is redirected to the login or home page.

### Test Case 2: Registration with Invalid Email
- **Preconditions:** User is on the registration page.
- **Steps:**
  1. Enter an invalid email address (e.g., "user@").
  2. Enter a valid password.
  3. Submit the registration form.
- **Expected Result:** Registration fails and an error message about invalid email is displayed.

### Test Case 3: Registration with Missing Fields
- **Preconditions:** User is on the registration page.
- **Steps:**
  1. Leave one or more required fields empty.
  2. Submit the registration form.
- **Expected Result:** Registration fails and error messages indicate which fields are missing.

### Test Case 4: Successful Login
- **Preconditions:** User account exists with known credentials.
- **Steps:**
  1. Enter correct email and password.
  2. Submit the login form.
- **Expected Result:** User is logged in and redirected to the home page.

### Test Case 5: Login with Incorrect Credentials
- **Preconditions:** User account exists.
- **Steps:**
  1. Enter correct email and incorrect password.
  2. Submit the login form.
- **Expected Result:** Login fails and an error message about incorrect credentials is displayed.

### Test Case 6: Successful Logout
- **Preconditions:** User is logged in.
- **Steps:**
  1. Click the logout button or link.
- **Expected Result:** User is logged out and redirected to the login or home page.

---

## 📦 Feature 2: Add Product

### Test Case 1: Access "Add Product" Form as Logged-in User
- **Preconditions:** User is logged in.
- **Steps:**
  1. Navigate to the "Add Product" page.
- **Expected Result:** "Add Product" form is displayed.

### Test Case 2: Access "Add Product" Form as Guest
- **Preconditions:** User is not logged in.
- **Steps:**
  1. Attempt to navigate to the "Add Product" page.
- **Expected Result:** User is redirected to the login page or shown an access denied message.

### Test Case 3: Successful Product Submission
- **Preconditions:** User is logged in and on the "Add Product" page.
- **Steps:**
  1. Enter valid product name, description, price, and upload a valid image.
  2. Submit the form.
- **Expected Result:** Product is added, and a success message is displayed.

### Test Case 4: Submission with Missing Fields
- **Preconditions:** User is logged in and on the "Add Product" page.
- **Steps:**
  1. Leave one or more required fields empty.
  2. Submit the form.
- **Expected Result:** Submission fails and error messages indicate which fields are missing.

### Test Case 5: Submission with Invalid Field Values
- **Preconditions:** User is logged in and on the "Add Product" page.
- **Steps:**
  1. Enter invalid values (e.g., negative price, non-image file).
  2. Submit the form.
- **Expected Result:** Submission fails and error messages indicate which fields are invalid.

---

## 👤 Feature 3: Update Profile

### Test Case 1: Successful Profile Update
- **Preconditions:** User is logged in and on the profile update page.
- **Steps:**
  1. Enter new valid name, email, and password.
  2. Enter the correct current password.
  3. Submit the form.
- **Expected Result:** Profile is updated and a success message is displayed.

### Test Case 2: Update with Incorrect Current Password
- **Preconditions:** User is logged in and on the profile update page.
- **Steps:**
  1. Enter new valid name, email, and password.
  2. Enter an incorrect current password.
  3. Submit the form.
- **Expected Result:** Update fails and an error message about incorrect current password is displayed.

### Test Case 3: Update with Invalid or Missing Fields
- **Preconditions:** User is logged in and on the profile update page.
- **Steps:**
  1. Leave one or more required fields empty or enter invalid values.
  2. Enter the correct current password.
  3. Submit the form.
- **Expected Result:** Update fails and error messages indicate which fields are missing or invalid. 