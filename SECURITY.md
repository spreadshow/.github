# Security Policy

## Reporting a vulnerability

Please **do not** open a public issue for security problems.

Use GitHub's private reporting: open the **Security** tab of the affected repository and choose **Report a vulnerability**. If that is not available, write to **spreadshow.project@proton.me**.

Include:

- A description of the issue and its impact
- Steps to reproduce, or a proof of concept
- Affected versions, if known

## What to expect

- Acknowledgement within 3 working days
- An initial assessment within 10 working days
- Coordinated disclosure: we will agree on a timeline with you and credit you in the advisory unless you prefer otherwise

## Scope

Spreadshow connects to databases and data lakes, so we take these areas especially seriously:

- Handling of credentials and connection secrets
- SQL injection or privilege escalation through the query builder
- Leaking data between users or between shared workbooks and their sources

## Supported versions

The project is at an early stage: only the latest release and the `main` branch receive security fixes.
