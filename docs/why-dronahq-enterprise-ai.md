# Why DronaHQ for Enterprise AI Apps

A concise brief for security, governance, and operational readiness of AI apps at enterprise scale.

## Centralized Control Plane
- Single pane to register LLM providers, vector stores, and data connectors.
- Enforce org-wide policies for prompts, templates, and guardrails with versioning.
- Monitor usage, cost, and latency per app/team with alerts and budgets.
- Roll out changes safely via environments, approvals, and staged rollbacks.

## Credential Vaulting for DB/REST
- Store DB, REST, and SaaS secrets in a vault — never in app code or frontends.
- Per-connector rotation and masking; short-lived tokens for outbound requests.
- All egress goes through policy checks and data loss prevention controls.
- Full audit trail of secret creation, access, and rotation events.

## RBAC  SSO
- Enterprise SSO (Okta, Azure AD, Google) with just-in-time provisioning.
- Role- and attribute-based policies on apps, actions, and data scopes.
- Least-privilege defaults across admin, developer, operator, and end-user roles.
- Identity context captured on every call for end-to-end traceability.

## Time-Bound, Governed Access
- Grant temporary, expiring access windows to sensitive data and actions.
- Policy conditions: time of day, IP range, device posture, session risk.
- Automatic revocation, re-approval workflows, and scheduled access reviews.
- Tamper-evident logs with export to SIEM for compliance.

## Reduced Credential Sprawl
- Platform-managed adapters call external systems using platform identity.
- End users and app builders never handle API keys or DB passwords directly.
- Rotate once in the vault; every dependent app benefits immediately.
- Fewer shadow tokens in notebooks, scripts, and dashboards.
