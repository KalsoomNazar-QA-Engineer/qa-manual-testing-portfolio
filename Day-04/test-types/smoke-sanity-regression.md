# Smoke, Sanity, Regression & Retesting Practice

## Example: Login Functionality

### 1. Smoke Testing

**Scenario:** A new build is received.

**Checks:**

* Login page opens
* Valid login works
* Login button is functional

**Purpose:** To verify that the main functionality is working and the build is stable enough for further testing.

---

### 2. Sanity Testing

**Scenario:** Developer fixes an issue related to the password field.

**Checks:**

* Password field accepts input
* Password validation works
* Login works with valid credentials

**Purpose:** To verify the specific changed/fixed area.

---

### 3. Regression Testing

**Scenario:** A new feature is added to the login module.

**Checks:**

* Valid login
* Invalid login
* Password validation
* Username validation
* Logout functionality

**Purpose:** To verify that existing functionality has not been affected by the new change.

---

### 4. Retesting

**Scenario:** A login bug was reported and the developer fixed it.

**Check:**

* Execute the same steps that previously reproduced the bug.

**Purpose:** To verify that the specific defect has been fixed.

## Key Learning

Smoke checks the build, Sanity checks a specific change, Regression checks existing functionality after changes, and Retesting verifies a specific bug fix.
