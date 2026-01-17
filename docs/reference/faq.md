# Frequently Asked Questions (FAQ)

This page answers common questions about PromptX APIs, governance, security, and integration.

If your question is not answered here, contact the PromptX team using the links provided throughout the portal.

---

## General Questions

### What is PromptX?

PromptX is an enterprise-grade AI platform designed to enable organisations to adopt generative AI **safely, securely, and at scale**.

PromptX combines:
- Governed AI interactions
- Knowledge grounding
- Policy enforcement
- Auditability
- Human accountability

---

### Who are PromptX APIs designed for?

PromptX APIs are designed for:
- Enterprise engineering teams
- Platform and integration teams
- Public-sector and regulated organisations
- Internal application and workflow integrations

They are **not** designed for unrestricted consumer-facing AI products.

---

## Access & Governance

### Why is API access restricted?

PromptX APIs are powerful capabilities that operate within organisational and regulatory boundaries.

Restricted access ensures:
- Responsible use
- Policy compliance
- Auditability
- Protection against misuse

This is a deliberate design choice, not a limitation.

---

### How do I request API access?

API access requests are submitted via email and reviewed for:
- Business purpose
- Risk and policy alignment
- Intended usage patterns

Approved requests are issued scoped credentials.

---

### Can API access be revoked?

Yes. API access may be revoked if:
- Usage falls outside approved intent
- Security risks are identified
- Credentials are compromised
- Access is no longer required

Revocation is part of responsible governance.

---

## Technical Questions

### Are PromptX APIs model-specific?

No. PromptX APIs abstract underlying AI models.

This:
- Avoids vendor lock-in
- Allows model upgrades without breaking integrations
- Ensures consistent governance regardless of model provider

---

### Can I use PromptX APIs for public-facing applications?

Yes, **with approval**.

Public-facing use cases (such as government information services) are supported when:
- Knowledge sources are controlled
- Prompts are governed
- Safeguards are in place
- Usage is monitored

Each case is reviewed individually.

---

### Is there a sandbox environment?

Sandbox or non-production environments may be provided depending on customer context and use case.

Availability and scope are determined during the access approval process.

---

## Data, Privacy & Security

### Does PromptX store or train on my data?

PromptX does not claim ownership of customer data.

Customer data is processed only to deliver the service and is not used to train public or shared AI models without explicit agreement.

---

### How is customer data protected?

PromptX enforces:
- Tenant isolation
- Secure transport (TLS)
- Role-based access controls
- Data handling and retention policies

API access does not bypass these protections.

---

### Are prompts and responses logged?

PromptX logs metadata required for audit and security purposes.

Full prompt or response content is not logged unnecessarily and logging practices align with data minimisation principles.

---

## Reliability & Operations

### What happens if the API is unavailable?

PromptX APIs are designed for reliability, but transient failures may occur.

Customers are expected to:
- Implement appropriate error handling
- Use retries where appropriate
- Design fallback behaviour

AI should enhance systems, not be a single point of failure.

---

### How are breaking changes handled?

Breaking changes are introduced only through:
- Explicit API versioning
- Advance communication
- Defined deprecation periods

PromptX does not remove functionality without notice.

---

## SDKs & Documentation

### Are SDKs required to use PromptX APIs?

No. SDKs are optional.

Some customers prefer SDKs for convenience and guardrails, while others integrate directly with APIs.

Both approaches are supported and governed.

---

### Why isn’t full API documentation public?

Detailed API specifications are shared with approved consumers to:
- Prevent misuse
- Align documentation access with governance
- Reduce risk exposure

This is standard practice for enterprise platforms.

---

## Support & Escalation

### How do I get help?

Support is provided through:
- Organisational administrators
- Approved support channels
- PromptX platform support teams (where applicable)

Escalation paths depend on severity and impact.

---

### How do I report a security or reliability issue?

Security or reliability concerns should be reported promptly using the **Report Issue** option in the Support section.

Responsible reporting helps keep the platform safe for all users.

---

## Still Have Questions?

If you have additional questions that are not covered here, contact the PromptX team.

<div style="margin-top:1.5rem">
<a href="mailto:promptx@ve3.global
?subject=PromptX%20API%20FAQ%20Query
&body=Organisation:%0D%0AQuestion:%0D%0AContext:"
class="md-button md-button--primary">
❓ Contact PromptX Team
</a>
</div>
