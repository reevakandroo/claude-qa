# TC020: Rapid repeated clicks on ECG item do not crash the app — Scalability

| Field | Detail |
|-------|--------|
| **Test ID** | TC020 |
| **Module** | ECG Dashboard |
| **Type** | ⚠️ Edge |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC004**](../00_preconditions/PC004_ecg_list_visible_with_entries.md) — ECG list is loaded with at least one entry visible

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Log in |
| 2 | Locate an ECG entry |
| 3 | Click it 5 times rapidly within 2 seconds |
| 4 | Observe app stability |

## Expected Results

App does not crash, freeze, or show unhandled error. Either the ECG opens once or the duplicate clicks are ignored gracefully.

---
*Module: ECG Dashboard · Type: Edge*
