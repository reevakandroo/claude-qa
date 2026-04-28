# TC066: Risk assessment API returns valid HTTP status — Performance

| Field | Detail |
|-------|--------|
| **Test ID** | TC066 |
| **Module** | Risk Assessment |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable
- [**PC009**](../00_preconditions/PC009_browser_dev_tools_open.md) — Browser DevTools are open

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Open network monitoring |
| 2 | Fill form and click Get Risk Assessment |
| 3 | Identify the risk API call |
| 4 | Check its HTTP status code |

## Expected Results

Risk API returns 200 OK or 201. No 4xx or 5xx status codes.

---
*Module: Risk Assessment · Type: Positive*
