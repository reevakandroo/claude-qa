# TC110: All interactive elements have ARIA labels for screen readers

| Field | Detail |
|-------|--------|
| **Test ID** | TC110 |
| **Module** | Compatibility |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC001**](../00_preconditions/PC001_app_loaded_at_login_url.md) — App is open at the login page; no user is logged in

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Open login page |
| 2 | Inspect aria-label attributes on: email input, password input, login button |
| 3 | Check patient form for ARIA labels |

## Expected Results

Each interactive element has a descriptive aria-label. Screen readers can identify and interact with all inputs.

---
*Module: Compatibility · Type: Positive*
