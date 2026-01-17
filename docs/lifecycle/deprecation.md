# Deprecation Policy

PromptX is designed for long-lived, enterprise integrations.  
As such, changes to APIs, SDKs, and platform capabilities are managed carefully to minimise disruption while allowing the platform to evolve.

This deprecation policy explains **how changes are introduced**, **how deprecations are communicated**, and **what customers can expect**.

---

## Principles of Deprecation

PromptX follows these core principles when deprecating functionality:

- **Stability First**  
  Existing integrations should continue to function without unexpected breakage.

- **Advance Notice**  
  Deprecations are communicated well in advance of removal.

- **Backward Compatibility Where Possible**  
  Non-breaking changes are preferred over breaking changes.

- **Clear Migration Paths**  
  Where deprecation is necessary, alternatives or migration guidance are provided.

- **No Silent Removal**  
  Functionality is never removed without explicit notice.

---

## What May Be Deprecated

The following may be subject to deprecation:

- API versions or endpoints
- SDK versions or features
- Configuration options or behaviours
- Experimental or preview capabilities

Deprecation does **not** imply immediate removal.

---

## Deprecation Lifecycle

A typical deprecation follows this lifecycle:

### 1. Announcement
A deprecation notice is published through:
- Documentation updates
- Changelog entries
- Direct communication to affected customers (where applicable)

The notice includes:
- What is being deprecated
- Why the change is necessary
- Recommended alternatives
- Expected timelines

---

### 2. Deprecation Period
During the deprecation period:
- The deprecated feature continues to function
- No new functionality is added to the deprecated feature
- Customers are encouraged to migrate

The length of the deprecation period depends on:
- Risk and impact
- Usage patterns
- Regulatory or security considerations

---

### 3. Removal or Disablement
After the deprecation period:
- The deprecated feature may be removed or disabled
- Removal is communicated in advance
- Customers should have had sufficient time to migrate

---

## Versioned APIs and Deprecation

For versioned APIs:
- Deprecated versions remain available for a defined support window
- New development occurs on newer versions
- Customers are encouraged to upgrade at a controlled pace

Exact timelines may vary by capability.

---

## SDK Deprecation

SDKs follow similar principles:
- Older SDK versions may be marked as deprecated
- Critical security fixes may still be applied during the support window
- Customers are encouraged to upgrade to supported versions

SDK deprecation does not immediately impact API availability.

---

## Emergency Changes

In rare cases, PromptX may need to modify or disable functionality immediately due to:
- Security vulnerabilities
- Legal or regulatory requirements
- Platform stability risks

Such changes are treated as exceptions and are communicated as transparently as possible.

---

## Customer Responsibilities

Customers are responsible for:
- Monitoring deprecation notices
- Planning and executing migrations
- Testing integrations against supported versions

PromptX provides documentation and guidance but does not automatically migrate customer integrations.

---

## Questions About Deprecation

If you have questions about deprecations or upcoming changes, contact the PromptX team.

<div style="margin-top:1.5rem">
<a href="mailto:promptx@ve3.global
?subject=PromptX%20Deprecation%20Policy%20Query
&body=Organisation:%0D%0AConcerned%20Feature:%0D%0AEnvironment:"
class="md-button md-button--primary">
📅 Contact About Deprecation
</a>
</div>
