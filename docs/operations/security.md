# API Security

Security is a foundational design principle of PromptX APIs.  
All API capabilities are delivered within a **defence-in-depth security model** that prioritises confidentiality, integrity, availability, and accountability.

This page explains how PromptX approaches API security and what customers can expect when integrating.

---

## Security-by-Design Philosophy

PromptX APIs are built with security as a **default condition**, not an optional configuration.

Key aspects include:
- Least-privilege access by default
- Explicit trust boundaries between tenants
- Secure handling of credentials and secrets
- Policy enforcement at every request

Security controls are layered to reduce the impact of any single failure.

---

## Authentication and Credential Security

PromptX APIs use secure, token-based authentication mechanisms.

Security expectations include:
- Tokens are scoped to approved capabilities
- Tokens must be stored securely and never embedded in client-side code
- Credential rotation is encouraged
- Compromised credentials can be revoked promptly

PromptX does not support anonymous API access.

---

## Authorisation and Access Control

Authorisation is enforced through:
- Role-based access control (RBAC)
- Scope-limited credentials
- Tenant isolation
- Policy enforcement

API calls are evaluated against approved permissions before execution.

Access control applies consistently across UI and API interactions.

---

## Network and Transport Security

PromptX APIs are accessible only over secure channels.

Key measures include:
- Encrypted communication using modern TLS standards
- Protection against common network-level attacks
- Controlled ingress and egress points

Unencrypted or insecure connections are not supported.

---

## Data Protection and Isolation

PromptX enforces strict data protection measures:
- Logical isolation between tenants
- Processing of customer data only for service delivery
- Alignment with documented data handling and retention policies

API access does not bypass data protection controls.

---

## Protection Against Abuse and Misuse

To protect platform integrity, PromptX implements:
- Rate limiting and quotas
- Abuse detection mechanisms
- Monitoring for anomalous usage patterns

These controls help prevent denial-of-service, data exfiltration, and unintended usage.

---

## Secure Development and Testing

PromptX follows secure development practices, including:
- Code review and change management
- Dependency and supply-chain risk management
- Regular security testing and vulnerability assessment

Security improvements are ongoing and iterative.

---

## Incident Detection and Response

Security events are:
- Detected through monitoring and alerts
- Investigated by authorised personnel
- Addressed according to defined incident response processes

Customers may be notified of security incidents in line with contractual and regulatory requirements.

---

## Shared Responsibility Model

Security is a shared responsibility:

### PromptX Responsibilities
- Platform security controls
- Infrastructure and network protection
- Access enforcement and audit logging

### Customer Responsibilities
- Secure credential handling
- Appropriate use of APIs
- Implementation of client-side security measures

PromptX provides secure foundations but does not control customer environments.

---

## Security Expectations for Integrators

When integrating with PromptX APIs, customers are expected to:
- Use least-privilege access scopes
- Secure secrets and credentials
- Implement appropriate error handling
- Monitor integrations for abnormal behaviour

Failure to follow security best practices may increase risk.

---

## Questions About Security

If you have questions about API security, controls, or responsibilities, contact the PromptX team.

<div style="margin-top:1.5rem">
<a href="mailto:promptx@ve3.global
?subject=PromptX%20API%20Security%20Query
&body=Organisation:%0D%0AUse%20Case:%0D%0AConcern:"
class="md-button md-button--primary">
🔐 Contact Security Team
</a>
</div>
