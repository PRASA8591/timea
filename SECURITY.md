# Security Policy

## Supported Versions

Security updates and patches are actively maintained for the latest release branch of TimeSheet Pro[cite: 5].

| Version | Supported          |
| ------- | ------------------ |
| 5.1.x   | :white_check_mark:[cite: 5] |
| 5.0.x   | :x:               [cite: 5] |
| < 5.0   | :x:               [cite: 5] |

## Security Architecture

- **Encrypted Storage**: All timesheet and salary records are secured and synchronized via Firebase Firestore with role-based document access[cite: 2, 6].
- **Session Auto-Logout**: Automatic session revocation is enforced after 15 minutes of inactivity to safeguard open operator terminals[cite: 6].
- **Emergency Lockdown**: Admins can broadcast a global lockout that forces non-admin operators out of active sessions within 1 second[cite: 6].
- **Audit Logging**: All administrative actions (user provisioning, approvals, permission changes, deletions) are logged to the `audit_logs` collection[cite: 6].

## Reporting a Vulnerability

If you discover a security vulnerability within TimeSheet Pro, please do not disclose it publicly. Report it directly to our security team:

- **Email**: [info@prasatek.lk](mailto:info@prasatek.lk)
- **Subject Line**: `[SECURITY VULNERABILITY] TimeSheet Pro`
- **Phone**: +94 71 932 3239

Please include a detailed description of the vulnerability, step-by-step reproduction instructions, and affected components. Our team will acknowledge receipt within 24–48 hours and provide remediation updates.
