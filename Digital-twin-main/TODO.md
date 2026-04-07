# Task: Create Authentication Logic

## Steps to Complete

- [x] 1. Create TODO.md and confirm plan with user
- [x] 2. Edit Digital-twin-main/index.html to add auth error div for login form
- [x] 3. Replace login form JS handler with real auth check (localStorage users array)
- [x] 4. Replace signup form JS handler with real signup (prevent duplicate, store user)
- [x] 5. Update TODO.md and test
- [x] 6. Complete task

**Status:** Complete

**Details:**
- Added #authError div for login errors.
- Login: Validates credentials against localStorage 'users', shows success with name or "Invalid credentials".
- Signup: Prevents duplicate emails, stores {name, email, password}.
- localStorage: 'users' array, 'currentUser' on login.
- Retains remember me, validation, loading states.
- Test: Create account → login success/fail → duplicate prevent.

Open Digital-twin-main/index.html to test.

