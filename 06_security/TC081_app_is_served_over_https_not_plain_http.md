# TC081: App is served over HTTPS — not plain HTTP

| Field | Detail |
|-------|--------|
| **Test ID** | TC081 |
| **Module** | Security |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- Browser is open.

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Navigate to the app URL |
| 2 | Check the browser address bar for the protocol |
| 3 | Try navigating to the HTTP version of the URL |

## Expected Results

URL begins with https://. HTTP redirects to HTTPS. Browser shows a padlock icon.

---
*Module: Security · Type: Positive*
