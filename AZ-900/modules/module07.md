# Module 7 - Describe Azure Identity, Access, and Security

Status: ✅ Completed

## Exam Objective

Understanding access control fundamentals and recognize Azure security services in scenario questions.

## Core Definitions

- Microsoft Entra ID: Cloud identity and access management service (formerly Azure AD).
- Authentication: Verifying identity (who you are).
- Authorization: Granting permissions (what you can do).
- Single Sign-On (SSO): One sign-in used across multiple apps.
- Multi-Factor Authentication (MFA): Authentication requiring two or more factor types.
- Passwordless authentication: Sign-in without passwords using secure methods like keys/biometrics/app.
- RBAC (Role-Based Access Control): Access control model based on assigning roles at scopes.
- Conditional Access: Policy engine that grants/blocks access based on signals.
- Zero Trust: Security model of never trust, always verify.
- Defense in depth: Layered security controls across identity, network, compute, apps, and data.

## Identity and Access Concepts

- Common auth factors:
	- Something you know (password/PIN)
	- Something you have (authenticator app/security key)
	- Something you are (biometric)
- External identity models:
	- B2B: Partner/collaborator access.
	- B2C: Customer identity for apps.
- Least privilege principle: Give minimum permissions required, for minimum duration.

## Security Services to Recognize

- Microsoft Defender for Cloud: Unified security posture management and workload protection.
- Azure Key Vault: Secure storage for secrets, keys, and certificates.
- Azure DDoS Protection: Protection against distributed denial-of-service attacks.

## Common Exam Traps

- RBAC controls permissions; Conditional Access controls sign-in conditions.
- Authentication and authorization are not interchangeable terms.
- Zero Trust is a strategy model, not a single product.

## Quick Checklist

- [x] I can define Entra ID, SSO, MFA, RBAC, Conditional Access, and Zero Trust.
- [x] I can explain authentication vs authorization with examples.
- [x] I can identify when to use Defender for Cloud and Key Vault.
