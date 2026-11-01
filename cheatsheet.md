# Cheatsheet

## Entra sign-in error codes
| Code | Meaning |
|---|---|
| 50126 | Invalid username or password |
| 50053 | Account locked (Smart Lockout) |
| 50140 | "Stay signed in?" prompt - interrupt, not an error |
| 50058 | No active session - user must sign in again (seen after revoking sessions) |

## Exchange delivery codes
| Code | Meaning |
|---|---|
| 550 5.1.10 | Recipient not found - usually a typo in the address |
| 5xx | Permanent failure, no retry |
| 4xx | Temporary failure, server retries | 

## Admin roles
| Role | Can do |
|---|---|
| Security Reader | Read-only access to security portals |
| Security Operator | Manage alerts/incidents, read security data |
| Security Administrator | Manage security settings and policies |
| Global Administrator | Everything — avoid for daily analyst work |
