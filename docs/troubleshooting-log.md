# Troubleshooting Log

## Entry 1: Domain Username Format

**Symptom:** A domain-user login attempt did not proceed as expected.

**Finding:** The username required correction before continuing the authentication test.

**Action:** Verified the user object in Active Directory and corrected the username used for the test.

**Result:** Account information was corrected and the domain-user authentication test completed successfully.

**Lesson:** Confirm the exact username, domain, account status, and password state before changing server or network settings.

## Entry 2: Account Lockout

**Symptom:** A test account became unavailable after repeated incorrect password attempts.

**Finding:** The account was locked according to the configured access-control scenario.

**Action:** Located the test user in Active Directory Users and Computers and cleared the lockout after reviewing account status.

**Result:** The lockout condition was removed and the account was ready for another controlled login test.

**Lesson:** Determine whether an authentication failure is caused by an incorrect password, disabled account, expired password, or lockout before resetting credentials.

## Entry 3: Limited Local Storage

**Symptom:** Available storage became too low to maintain another large virtual-machine installation safely.

**Finding:** Virtual-machine files and installation media consumed a significant amount of local storage.

**Action:** Removed unneeded installation media, reviewed VM storage use, and reclaimed enough capacity to complete the Windows 11 client validation safely.

**Result:** Storage pressure was reduced and the remaining client validation was completed.

**Lesson:** Check host capacity before expanding a lab and document incomplete validation instead of claiming an unverified result.
