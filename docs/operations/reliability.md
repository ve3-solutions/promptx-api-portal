# Error Handling & Reliability

PromptX APIs are designed to operate reliably at enterprise scale.  
However, like all distributed systems, errors can occur.

This page explains **how errors are categorised**, **how they should be handled**, and **what developers can expect** when something goes wrong.

---

## Reliability Philosophy

PromptX follows these reliability principles:

- **Fail Predictably**  
  Errors are explicit and structured rather than silent or ambiguous.

- **Fail Safely**  
  Errors should not result in unintended data exposure or unsafe behaviour.

- **Support Recovery**  
  Errors are designed to enable retries, fallback, or graceful degradation.

- **Transparency Without Leakage**  
  Error responses provide useful context without exposing sensitive internals.

---

## Categories of Errors

Errors returned by PromptX APIs generally fall into the following categories.

### Client-Side Errors
These occur when a request cannot be processed due to client input or configuration.

Examples include:
- Authentication or authorisation failures
- Invalid or malformed requests
- Requests outside approved scope or policy

Client-side errors typically require **request correction**, not retries.

---

### Server-Side Errors
These occur when the platform encounters an internal issue.

Examples include:
- Temporary service unavailability
- Internal processing errors
- Dependency failures

Server-side errors are typically **transient** and may be retried safely.

---

### Policy and Governance Errors
These occur when a request violates governance or policy constraints.

Examples include:
- Exceeding approved usage limits
- Attempting unauthorised capabilities
- Accessing restricted resources

Such errors indicate a **governance boundary**, not a technical fault.

---

## Error Responses

PromptX API error responses are structured to provide:
- A clear error category
- A human-readable summary
- Context for diagnosis
- A stable structure for programmatic handling

Error responses avoid exposing:
- Internal system architecture
- Sensitive operational details
- Customer data or prompts

---

## Retry and Backoff Guidance

### When to Retry
Retries may be appropriate when:
- Errors indicate transient server-side issues
- Network interruptions occur
- Rate limiting responses advise retry-after behaviour

### When NOT to Retry
Retries should not be used when:
- Requests fail due to invalid input
- Authentication or authorisation fails
- Policy violations are returned

Uncontrolled retries can worsen failures and may trigger additional controls.

---

## Idempotency and Safe Replays

Where applicable, PromptX APIs are designed to support:
- Idempotent operations
- Safe replay of requests after transient failures

Developers should ensure:
- Requests can be safely retried
- Duplicate effects are avoided

---

## Graceful Degradation

For production systems, PromptX recommends:
- Fallback user experiences
- Clear user messaging when AI assistance is unavailable
- Continued operation of core business logic without AI dependency

AI should enhance systems, not become a single point of failure.

---

## Observability and Correlation

Error events are:
- Logged for audit and investigation
- Correlatable with request metadata
- Used to improve platform reliability

Where supported, error identifiers may be provided to assist with support requests.

---

## Customer Responsibilities

Customers are responsible for:
- Implementing appropriate error handling and retries
- Monitoring integration health
- Responding appropriately to policy-related errors

PromptX provides reliable signals but does not manage customer-side recovery logic.

---

## Reporting Reliability Issues

If you encounter repeated or unexpected errors, report the issue so it can be investigated.

<div style="margin-top:1.5rem">
<a href="mailto:promptx@ve3.global
?subject=PromptX%20API%20Reliability%20Issue
&body=Organisation:%0D%0AEnvironment:%0D%0AError%20Observed:%0D%0ATime%20Window:%0D%0AImpact:"
class="md-button md-button--primary">
⚠️ Report Reliability Issue
</a>
</div>
