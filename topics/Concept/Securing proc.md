---
type: Concept
---

Securing the /proc filesystem involves restricting access to sensitive information that is exposed through the /proc directory. This is done by mounting the /proc filesystem with specific options that limit the visibility of process information to only the user who owns the process. This measure helps to prevent unauthorized users from accessing sensitive information about running processes, which could be used to launch attacks or gather information about the system.