# Concept 01: The Enterprise Software Engineering Mindset

## What distinguishes a "Hobby/Tutorial App" from an "Enterprise App"?

| Aspect | Tutorial / Hobby App | Enterprise-Ready App |
| :--- | :--- | :--- |
| **Accuracy** | Uses standard floating point math (`0.1 + 0.2`) | Zero-error financial math (Integer cents/paise or Decimal) |
| **Security** | Stores passwords in plain text or simple hashes | Argon2/bcrypt, secure session/token rotation, RBAC, PII encryption |
| **Architecture** | Spaghetti code mixing UI and database logic | Separation of Concerns (Domain Engine -> API -> UI) |
| **Testing** | Manual testing in browser | Automated Unit, Integration, and End-to-End tests |
| **Auditability** | Changes overwrite data silently | Immutable audit logs (who changed what, when, and from where) |
| **Error Handling** | Crashes or shows raw stack traces | Graceful user recovery, structured error logs, telemetry |

## How EasyTax applies this from Day 1:
1. **Never use standard floats for money**: Taxes must be exact to the cent/paise.
2. **Domain logic must run independently**: You should be able to run and test tax calculations from the command line without opening a browser or database.
3. **Every decision is documented**: Code is written for humans first, machines second.
