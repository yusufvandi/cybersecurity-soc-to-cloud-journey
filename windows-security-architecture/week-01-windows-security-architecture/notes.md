# Windows Security Architecture — Conceptual Notes

## Windows Authentication
Windows authentication is the process by which the operating system verifies a user's identity before granting access to system resources.

Key components include:
- Credential validation
- User and group membership checks
- Generation of a security token
- Assignment of permissions based on privilege level

Authentication is completed **before** the user gains access to the desktop environment.

---

## Local Users vs Administrators
- **Local users** operate with limited permissions.
- **Administrators** possess elevated privileges that allow system-level changes.

This distinction is critical in security monitoring, as administrative actions carry higher risk and require closer scrutiny.

---

## Purpose of Windows Security Logs
Windows security logs exist to:
- Record authentication attempts
- Track access to protected resources
- Support auditing and compliance
- Enable incident detection and investigation

Security logs are designed for **evidence and traceability**, not as unquestionable truth.

---

## Security Log Location
Security events are stored in:

Event Viewer → Windows Logs → Security

These logs are a primary data source for SOC analysts and SIEM platforms.
