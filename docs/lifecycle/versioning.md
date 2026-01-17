# API Versioning

PromptX APIs are designed for long-lived enterprise integrations.  
API versioning exists to allow the platform to evolve **without breaking existing consumers** and to provide predictability for customers operating at scale.

This page explains how API versions are defined, how changes are introduced, and what customers can expect over time.

---

## Versioning Principles

PromptX follows these principles when versioning APIs:

- **Predictability**  
  API behaviour within a version remains stable.

- **Backward Compatibility First**  
  Non-breaking changes are preferred wherever possible.

- **Explicit Change Boundaries**  
  Breaking changes are introduced only through new API versions.

- **Governed Exposure**  
  New versions may be gated or limited based on risk and readiness.

- **Clear Communication**  
  Version changes are documented and communicated in advance.

---

## API Versioning Model

PromptX APIs are versioned explicitly.

Versions may be expressed through one or more of the following mechanisms:
- Versioned base paths (e.g. `/v1`, `/v2`)
- Version identifiers in headers
- Versioned SDK releases aligned to API versions

The exact mechanism may vary by capability, but the intent remains consistent.

---

## What Constitutes a New API Version

A new API version may be introduced when changes include:
- Breaking request or response schema changes
- Behavioural changes that alter output semantics
- Changes to authentication or authorisation models
- Changes that impact integration assumptions

Minor enhancements that do not affect compatibility are typically introduced within the same version.

---

## Changes Within a Version

Within an existing API version, PromptX may introduce:
- New optional fields
- Performance improvements
- Bug fixes
- Additional capabilities that do not alter existing behaviour

Such changes are designed to be **non-breaking**.

---

## Version Support and Lifecycle

Each API version follows a defined lifecycle:
- **Active** – Fully supported and recommended
- **Deprecated** – Still functional but scheduled for retirement
- **Retired** – No longer available

Deprecation and retirement follow the documented **Deprecation Policy** and are communicated in advance.

---

## Relationship to SDK Versioning

SDK versions are aligned with API versions but are versioned independently.

- An SDK may support multiple API versions
- SDK updates may include non-breaking improvements
- SDK deprecation does not automatically imply API deprecation

Customers are encouraged to align SDK and API versions deliberately.

---

## Version Selection and Responsibility

Customers are responsible for:
- Selecting the appropriate API version
- Testing integrations against supported versions
- Planning upgrades as part of normal lifecycle management

PromptX provides documentation and guidance but does not automatically migrate integrations.

---

## Preview and Experimental Versions

Some API versions or capabilities may be marked as:
- Preview
- Limited availability
- Experimental

Such versions:
- May change without full backward compatibility
- Are not guaranteed to reach general availability
- Should not be used for critical production workloads unless explicitly approved

---

## Questions About API Versioning

If you have questions about API versions, compatibility, or upgrade planning, contact the PromptX team.

<div style="margin-top:1.5rem">
<a href="mailto:promptx@ve3.global
?subject=PromptX%20API%20Versioning%20Query
&body=Organisation:%0D%0ACurrent%20API%20Version:%0D%0AIntegration%20Context:%0D%0AConcern:"
class="md-button md-button--primary">
🔢 Contact About API Versioning
</a>
</div>
