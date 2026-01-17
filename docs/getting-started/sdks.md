# SDKs & Client Libraries

PromptX SDKs provide **opinionated, governed client libraries** that simplify integration with PromptX APIs while reinforcing security, policy, and best practices.

SDKs are designed to reduce integration risk and ensure consistent, responsible use of PromptX capabilities across teams and applications.

---

## Purpose of PromptX SDKs

PromptX SDKs exist to:
- Simplify authentication and request handling
- Enforce recommended security practices
- Abstract API complexity
- Reduce the likelihood of misuse or misconfiguration
- Provide a consistent developer experience across languages

SDKs are not thin wrappers — they encode **platform expectations**.

---

## Supported Languages

### Currently Available
SDK availability depends on customer context and use case.

Some SDKs may be shared with approved customers under controlled access.

### Planned / Under Evaluation
Language support is prioritised based on:
- Customer demand
- Security considerations
- Operational maintainability

Common candidates include:
- Java
- Python
- JavaScript / TypeScript
- .NET

Availability does not imply public release.

---

## What PromptX SDKs Provide

PromptX SDKs typically handle:
- Secure token management
- Request construction and validation
- Retry and backoff logic
- Error categorisation
- Response normalisation
- Basic telemetry hooks (where permitted)

This allows developers to focus on **business logic**, not plumbing.

---

## Governance & Security in SDKs

SDKs are designed to reinforce governance by:
- Encouraging least-privilege access
- Preventing hard-coded secrets
- Making audit-friendly patterns the default
- Aligning SDK usage with API approval scope

SDKs do not bypass platform controls.

---

## Versioning & Compatibility

SDKs follow structured versioning practices:
- Backward-compatible changes are preferred
- Breaking changes are minimised and communicated
- SDK versions align with supported API versions

This protects long-lived enterprise integrations.

---

## When to Use an SDK vs Raw APIs

### Use an SDK when:
- Rapid integration is needed
- Teams want guardrails by default
- Multiple applications share integration logic

### Use raw APIs when:
- Custom networking or security layers are required
- The environment restricts third-party libraries
- Advanced control is necessary

Both approaches remain governed.

---

## Request SDK Access

If you are interested in using a PromptX SDK or discussing SDK availability for your use case, submit a request.

<div style="margin-top:1.5rem">
<a href="mailto:promptx@ve3.global
?subject=PromptX%20SDK%20Access%20Request
&body=Organisation:%0D%0AUse%20Case:%0D%0APreferred%20Language:%0D%0AEnvironment:"
class="md-button md-button--primary">
🧩 Request SDK Access
</a>
</div>

---

## Important Notes

- SDK availability may vary by customer and environment
- SDK usage is subject to the same governance and approval as direct API usage
- SDKs are not required to use PromptX APIs
