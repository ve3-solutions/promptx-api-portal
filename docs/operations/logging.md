# Audit, Logging & Observability

PromptX is designed to support enterprise governance, security oversight, and compliance requirements through **structured logging and auditability**.

This page explains **what is logged**, **why it is logged**, and **how audit information is used**, without exposing sensitive operational details.

---

## Purpose of Audit Logging

Audit logging in PromptX exists to:
- Support security monitoring and incident investigation
- Enable compliance and regulatory review
- Provide traceability of API usage
- Detect misuse or anomalous behaviour
- Support operational reliability

Logging is designed for **accountability and assurance**, not surveillance.

---

## What Is Logged

PromptX logs relevant metadata associated with API and platform activity, which may include:
- Authentication and access events
- API invocation metadata (e.g. timestamp, capability invoked)
- Tenant and credential identifiers
- Success and failure indicators
- Administrative and configuration changes

Logs focus on **who did what and when**, not on monitoring user intent.

---

## What Is Not Logged

To protect privacy and data minimisation principles:
- Full prompt or content payloads are not logged by default
- Sensitive customer data is not logged unnecessarily
- Logs are not used for behavioural profiling

Logging is aligned with PromptX data protection and privacy commitments.

---

## Auditability and Traceability

Audit logs are designed to provide:
- Traceability of actions across users, services, and tenants
- Evidence for internal and external audits
- Support for forensic analysis when required

Audit data supports accountability without exposing proprietary or personal content.

---

## Log Access and Visibility

Access to logs is restricted and governed:
- Logs are accessible only to authorised personnel
- Administrative access is role-controlled
- Customer visibility into logs may vary by deployment and agreement

Logs are not publicly accessible.

---

## Retention and Protection of Logs

Audit logs are:
- Retained for defined periods based on operational and regulatory needs
- Protected against unauthorised access
- Stored securely with appropriate access controls

Retention periods may vary depending on environment and contractual context.

---

## Monitoring and Alerting

PromptX uses logs and telemetry to:
- Detect abnormal or suspicious activity
- Identify reliability or performance issues
- Trigger alerts for operational or security review

Monitoring is focused on **platform health and risk**, not individual user behaviour.

---

## Customer Responsibilities

Customers are responsible for:
- Using audit information appropriately
- Aligning PromptX usage with organisational policies
- Integrating PromptX audit outputs with their own governance processes where applicable

PromptX provides audit support but does not replace organisational oversight.

---

## Questions About Audit and Logging

If you have questions about audit logging, compliance support, or observability, contact the PromptX team.

<div style="margin-top:1.5rem">
<a href="mailto:promptx@ve3.global
?subject=PromptX%20Audit%20and%20Logging%20Query
&body=Organisation:%0D%0AUse%20Case:%0D%0ACompliance%20Context:%0D%0AQuestion:"
class="md-button md-button--primary">
📊 Contact About Audit & Logs
</a>
</div>
