# Help Desk Scenarios

These scenarios are written in a simple ticket format to demonstrate issue intake, investigation, resolution, verification, and documentation.

## Ticket 1: Forgotten Password

**Issue:** A test user cannot sign in after forgetting the account password.

**Investigation:** Confirmed the username, reviewed account status in Active Directory Users and Computers, and checked whether the account was disabled or locked.

**Action:** Reset the password and required a password change at the next sign-in.

**Verification:** Confirmed that the account was enabled and prepared the user to test the new temporary password.

**Documentation:** Recorded the account checked, action completed, and required follow-up without documenting the password.

## Ticket 2: Locked Account

**Issue:** A test user is unable to authenticate after repeated incorrect password attempts.

**Investigation:** Reviewed the account properties and confirmed that the account was locked.

**Action:** Unlocked the account after confirming the simulated user’s identity and account status.

**Verification:** Confirmed that the lockout flag was cleared and reviewed the next login step.

**Documentation:** Recorded the symptoms, lockout finding, corrective action, and test status.

## Ticket 3: Disabled Account

**Issue:** A test user receives an account-access error.

**Investigation:** Checked the user object and confirmed that the account was disabled.

**Action:** Enabled the account as part of the approved lab scenario.

**Verification:** Confirmed the updated account status and prepared an authentication test.

**Documentation:** Recorded the original state, change performed, and validation step.

## Ticket 4: Security-Group Access

**Issue:** A test user requires access associated with a security group.

**Investigation:** Reviewed the user’s existing group membership and identified the required lab group.

**Action:** Added the user to the correct security group.

**Verification:** Reopened the user’s membership list and confirmed the change.

**Documentation:** Recorded the group added, reason for the change, and verification result.

## Ticket 5: Account-Lockout Policy

**Issue:** The lab requires accounts to lock after five failed sign-in attempts.

**Investigation:** Reviewed the applicable account-policy settings in Group Policy Management.

**Action:** Configured the account-lockout threshold for five invalid attempts.

**Verification:** Reviewed the configured policy and validated the five-attempt threshold in the private lab.

**Documentation:** Recorded the policy value, configuration location, and validation result without exposing account details.
