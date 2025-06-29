
---

### 📁 05-access-control-review/README.md

```markdown
# Dormant Account Abuse – Access Control Investigation

## 📄 Description
Analysis of a security incident where a contractor's inactive admin account was used to access payroll systems years after the contract expired.

## 🧰 Tools & Skills
- Tools: Log correlation (manual), access review checklist
- Skills: Authorization auditing, user lifecycle enforcement

## 📊 Key Observations
- Access from IP 152.207.255.255 using device "Up2-NoGud"
- Account: Robert Taylor Jr (contract ended 2019)
- Accessed in 2023 with Administrator privileges

## ✅ Recommendation
- Immediately deactivate accounts after offboarding
- Apply role-based access: contractors ≠ admin
- Enforce MFA on high-privilege accounts

## 📚 Control Mapping
- NIST SP 800-53: AC-2 (Account Management), AC-6 (Least Privilege)
- MITRE ATT&CK: T1078 (Valid Accounts)
