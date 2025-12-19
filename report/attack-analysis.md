# Attack Analysis

## Phishing Campaign
- Over 40 employees received malicious emails
- Healthcare-related subjects used for social engineering
- Multiple spoofed domains impersonated trusted partners

## Malware Execution
- Initial payload downloaded via browser
- Secondary executable dropped in Temp directory
- Database discovery tool searched for `.db`, `.sql`, `.mdb` files

## Command Execution
- Archive utilities used to compress files
- SSH connections established to external IPs
- Hardcoded credentials observed (not documented here)
