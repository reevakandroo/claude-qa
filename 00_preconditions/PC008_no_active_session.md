# PC008: No Active User Session — Unauthenticated

| Field | Detail |
|-------|--------|
| **Precondition ID** | PC008 |
| **Title** | No Active User Session — Unauthenticated |
| **Summary** | No user is logged in; browser has no valid session |

## Description

The browser has no active session. Accessing protected routes redirects to login.

## Setup Steps

1. Option A — Open a fresh incognito / private browser window.
2. Option B — In a regular window: open DevTools → Application → **Clear site data**.
3. Reload the page.
4. Confirm the app redirects to login when any protected URL is accessed.

---
*Referenced by test cases across all modules.*
