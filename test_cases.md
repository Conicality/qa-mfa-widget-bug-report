# Test Cases – MFA Removal Widget

| Test Case ID | Scenario | Expected Result | Actual Result | Status |
|---------------|-----------|----------------|----------------|--------|
| TC01 | User has access to both email and phone | MFA removed successfully | ✅ Success | Pass |
| TC02 | User has access to email but phone invalid | MFA removal blocked, prompt for verification | ⚠️ Error (format) | Fail |
| TC03 | Multiple MFA devices linked | Widget handles removal sequentially | ❌ Only first removed | Fail |
| TC04 | User confirms ownership via verification email | Removal workflow continues | ✅ Success | Pass |

---

—  
Created and documented by Andrea "Nea" Esquivel  
Cloudbynea Technical Portfolio | cloudbynea@gmail.com