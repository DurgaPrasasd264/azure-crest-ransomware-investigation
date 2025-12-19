# Incident Report – Azure Crest Hospital

## Executive Summary
Azure Crest Hospital experienced a ransomware incident initiated
through a phishing campaign delivering malicious `.docm` files.

Multiple employee systems were compromised, leading to
malware execution and database encryption.

---

## Initial Detection
- Alert triggered on macro-enabled document
- Filename: New_Healthcare_Protocols.docm
- Delivery method: Email phishing

---

## Infection Vector
Employees received emails impersonating healthcare partners.
Links redirected to attacker-controlled domains hosting malicious files.

---

## Malware Activity
- Secondary payloads downloaded
- Database discovery tools executed
- Files compressed and encrypted

---

## Impact
- Multiple endpoints compromised
- Database files encrypted
- Business operations disrupted

---

## Conclusion
This case highlights the effectiveness of phishing-based ransomware
attacks and the importance of EDR, email security, and user awareness.
