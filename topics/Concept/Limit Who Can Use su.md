---
type: Concept
---

Limiting who can use su involves restricting the use of the su command to specific users or groups. This is done by changing the ownership and permissions of the su binary to allow only certain users or groups to execute it. By default, all users can use su to switch to the root user, but this can be changed to restrict access to a smaller group of trusted users. This measure helps to prevent unauthorized users from gaining root access and making system-wide changes.