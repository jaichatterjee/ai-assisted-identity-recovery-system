# Scenario Framework

| Scenario | Risk | Action |
|---|---:|---|
| Pre-expiry reset | Low | Allow + MFA |
| Password expired | Medium | Step-up MFA |
| Windows Hello session | Low | Allow |
| No login access | High | Strong MFA + Device check |
| Lost device | High | ITSM containment |
| No access + no factors | Critical | Escalation |
| Authentication failure | Critical | Block + Alert |

---

## Purpose

Maps user recovery scenarios to security responses.
