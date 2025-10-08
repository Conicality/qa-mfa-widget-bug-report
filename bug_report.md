# Bug Report – MFA Removal Widget

## Bug Summary

| ID | Description | Type | Status | Severity | Notes |
|----|--------------|------|----------|-----------|--------|
| 001 | OTP input not recognized due to formatting error | Functional | Resolved | High | Input required full integer string, widget failed when extra spaces were present. |
| 002 | Email validation rejected “.co.cr” domains | Functional | Open | Medium | Regex pattern limited to “.com” only. |
| 003 | Multiple MFA attached to root not removed in bulk | Logic | Open | High | Workflow triggered only first MFA instance removal. |
| 004 | Number format validation failed for +506 prefix | UX/Validation | Resolved | Medium | Widget did not accept Costa Rica phone prefix initially. |

---

—  
Created and documented by Andrea "Nea" Esquivel  
Cloudbynea Technical Portfolio | cloudbynea@gmail.com