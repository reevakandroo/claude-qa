# TC065: No 5xx server errors occur during risk assessment — Performance

| Field | Detail |
|-------|--------|
| **Test ID** | TC065 |
| **Module** | Risk Assessment |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable
- [**PC009**](../00_preconditions/PC009_browser_dev_tools_open.md) — Browser DevTools are open

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Open browser dev tools > Network |
| 2 | Fill patient form |
| 3 | Click Get Risk Assessment |
| 4 | Monitor all HTTP responses |

## Expected Results

All network responses return 2xx status codes. No 500, 502, 503, or 504 errors appear.

---
*Module: Risk Assessment · Type: Positive*
