# Answers to Assignment 8 Part 3

Add your answers to the questions in Assignment 8 Part 3, Step 2 below. 

## Vulernability Remediation:
### Vulnerability 1: 
1. Which package or library are you addressing?
PyYAML library v5.1-5.1.2
2. Which CVE is linked to this vulnerability?
CVE-2019-20477
3. What remediation steps do you suggest?
Upgrade PyYAML to version 5.2 or later to resolve this issue, these versions add stricter control. When handling YAML data, use the safe_load method instead of load.

### Vulnerability 2:
1. Which vulnerability are you addressing?
libwebp in Pillow library
2. Which CVE is linked to this vulnerability?
CVE-2023-4863
3. What remediation steps do you suggest? 
Upgrade Pillow to version 10.0.1 or later, including libwebp version 1.3.2. 
