# Security Policy

## Reporting a vulnerability

**Please do not open a public issue for security problems.**

Report privately via GitHub's
[Security Advisories](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing/privately-reporting-a-security-vulnerability)
on the affected repository, or email **<TODO: set a security contact email>**.

Please include:

- What the issue is and roughly how severe you think it is
- Steps to reproduce, or a proof of concept
- Which version, commit, or deployed URL you tested against

We aim to acknowledge within 5 days. Because we are a student chapter,
resolution time varies — we'll keep you updated.

## Scope

Several of our projects handle real personal data (event registrations,
applications). We take reports about the following especially seriously:

- Authentication or authorisation bypass
- Exposure of personal data belonging to registrants or applicants
- Leaked credentials, API keys, or tokens in source or build output
- SQL injection, or row-level-security bypass in Supabase-backed projects

## Please don't

- Access, modify, or delete data belonging to other people
- Run automated scanners against our production deployments
- Perform denial-of-service testing

Report it and we'll reproduce it ourselves.

## Credit

We're happy to credit you in the advisory unless you'd rather stay anonymous.
