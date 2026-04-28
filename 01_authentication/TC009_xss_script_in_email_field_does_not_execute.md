# TC009: XSS script in email field does not execute

| Field | Detail |
|-------|--------|
| **Test ID** | TC009 |
| **Module** | Authentication |
| **Type** | ⚠️ Edge |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC001**](../00_preconditions/PC001_app_loaded_at_login_url.md) — App is open at the login page; no user is logged in

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Enter XSS payload in email: <script>alert("xss")</script> |
| 2 | Enter any password |
| 3 | Click Login |
| 4 | Observe whether an alert dialog appears |

## Expected Results

No alert dialog fires. Login is rejected. Script tag is not executed. App stays on login page.

---
*Module: Authentication · Type: Edge*
