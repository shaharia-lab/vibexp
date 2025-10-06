# Security Policy

## Reporting a Vulnerability

We take the security of vibexp seriously. If you have discovered a security vulnerability, we appreciate your help in disclosing it to us in a responsible manner.

### How to Report a Security Vulnerability

**Please DO NOT report security vulnerabilities through public GitHub issues.**

Instead, please report them via one of the following methods:

1. **Email**: Send details to [mail@shaharia.com](mailto:mail@shaharia.com) with the subject line "Security Vulnerability Report - vibexp"
2. **GitHub Security Advisory**: Use GitHub's [private security vulnerability reporting](https://github.com/shaharia-lab/vibexp/security/advisories/new)

### What to Include in Your Report

Please include as much of the following information as possible:

- Type of vulnerability (e.g., XSS, SQL injection, authentication bypass, etc.)
- Full paths of source file(s) related to the vulnerability
- The location of the affected source code (tag/branch/commit or direct URL)
- Step-by-step instructions to reproduce the issue
- Proof-of-concept or exploit code (if possible)
- Impact of the vulnerability, including how an attacker might exploit it
- Any suggested remediation steps

### What to Expect

- **Response Time**: We will acknowledge receipt of your vulnerability report within 48 hours
- **Communication**: We will keep you informed about the progress of fixing the vulnerability
- **Credit**: We will credit you in the security advisory (unless you prefer to remain anonymous)
- **Timeline**: We aim to release fixes for confirmed vulnerabilities within 90 days

### Scope

This security policy applies to:

- vibexp backend API
- vibexp frontend application
- vibexp MCP server implementations
- All official vibexp repositories under the shaharia-lab organization

### Out of Scope

The following are generally **not** considered security vulnerabilities:

- Vulnerabilities in third-party dependencies (please report to the respective maintainers)
- Social engineering attacks
- Denial of Service (DoS) attacks requiring significant resources
- Issues in unsupported or deprecated versions
- Attacks requiring physical access to a user's device

### Safe Harbor

We consider security research conducted under this policy to be:

- Authorized concerning any applicable anti-hacking laws
- Exempt from DMCA
- Lawful and helpful to the overall security of the Internet

As long as you:

- Make a good faith effort to avoid privacy violations, data destruction, and service interruption
- Only interact with accounts you own or with explicit permission from the account holder
- Do not exploit vulnerabilities beyond the minimum necessary to confirm their existence
- Do not access or modify data beyond what is necessary to demonstrate the vulnerability

## Supported Versions

We currently support the following versions with security updates:

| Version | Supported          |
| ------- | ------------------ |
| main    | :white_check_mark: |
| < 1.0   | :x:                |

## Security Best Practices

When using vibexp, we recommend:

- Keep your installation up to date with the latest releases
- Use strong, unique API keys and rotate them regularly
- Enable HTTPS/TLS for all network communications
- Follow the principle of least privilege for user permissions
- Regularly review access logs and audit trails
- Keep dependencies up to date

## Security Updates

Security updates will be announced via:

- GitHub Security Advisories
- Release notes in the repository
- Git tags for security releases

## Questions?

If you have questions about this security policy, please open a [general issue](https://github.com/shaharia-lab/vibexp/issues/new/choose) or email [mail@shaharia.com](mailto:mail@shaharia.com).

---

Thank you for helping keep vibexp and our community safe!

