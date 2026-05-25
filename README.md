# FusionAuth (fusionauth)

FusionAuth is a developer-focused customer identity and access management (CIAM) platform that delivers authentication, authorization, registration, multi-factor authentication, single sign-on, OAuth2 and OpenID Connect, and user management capabilities through a comprehensive REST API and self-hostable identity service.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/fusionauth/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Authentication, Authorization, Identity, CIAM, OAuth, OpenID Connect, Single Sign-On, Multi-Factor Authentication

## Timestamps

- **Created:** 2024-09-26
- **Modified:** 2026-05-25

## APIs

### FusionAuth API

The FusionAuth API exposes the platform's complete authentication, authorization, user management, OAuth2/OIDC, multi-factor, tenant, application, and administrative surface as a REST API. An upstream OpenAPI 3.0 specification is published and maintained by FusionAuth.

**Human URL:** [https://fusionauth.io/docs/](https://fusionauth.io/docs/)

**Base URL:** [https://sandbox.fusionauth.io](https://sandbox.fusionauth.io)

#### Tags

 - Authentication, Authorization, Identity, CIAM, OAuth, OpenID Connect

#### Properties

- [Documentation](https://fusionauth.io/docs/apis/)
- [OpenAPI (upstream)](https://raw.githubusercontent.com/FusionAuth/fusionauth-openapi/main/openapi.yaml)
- [OpenAPI (local)](openapi/fusionauth-openapi.yaml)
- [SDKs](https://fusionauth.io/docs/sdks/)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/fusionauth)
- [Getting Started](https://fusionauth.io/docs/get-started/)
- [SDKs](https://fusionauth.io/docs/sdks/)
- [Change Log](https://fusionauth.io/docs/release-notes/)
- [Blog](https://fusionauth.io/blog/)
- [Login](https://login.fusionauth.io/oauth2/authorize)
- [Sign Up](https://login.fusionauth.io/oauth2/register)
- [Privacy Policy](https://fusionauth.io/privacy-policy)
- [GitHub Organization](https://github.com/fusionauth)
- [Pricing](https://fusionauth.io/pricing)
- [Integrations](https://fusionauth.io/partners)
- [MCP Server](https://github.com/FusionAuth/fusionauth-mcp-api)
- [Agent Skills](https://github.com/FusionAuth/webhook-skills)
- [llms.txt](https://fusionauth.io/llms.txt)

## Integrations

| Slug | Partner | Category | Use Case |
|------|---------|----------|----------|
| [fusionauth-stripe](integrations/fusionauth-stripe.yaml) | Stripe | Billing | Promote FusionAuth users to Stripe customers |
| [fusionauth-salesforce](integrations/fusionauth-salesforce.yaml) | Salesforce | CRM | Sync FusionAuth users to Salesforce contacts |
| [fusionauth-hubspot](integrations/fusionauth-hubspot.yaml) | HubSpot | CRM | Push FusionAuth registrations into HubSpot contacts and lifecycle |
| [fusionauth-slack](integrations/fusionauth-slack.yaml) | Slack | ChatOps | Stream FusionAuth login + admin events to Slack |
| [fusionauth-microsoft-entra](integrations/fusionauth-microsoft-entra.yaml) | Microsoft Entra | Federation | Federate FusionAuth with Microsoft Entra ID |
| [fusionauth-google-workspace](integrations/fusionauth-google-workspace.yaml) | Google Workspace | Federation | Federate FusionAuth with Google Workspace SSO |
| [fusionauth-okta](integrations/fusionauth-okta.yaml) | Okta | Migration | Migrate Okta users into FusionAuth |
| [fusionauth-auth0](integrations/fusionauth-auth0.yaml) | Auth0 | Migration | Migrate Auth0 users into FusionAuth |
| [fusionauth-github](integrations/fusionauth-github.yaml) | GitHub | Social Login | Add GitHub OAuth login to FusionAuth applications |
| [fusionauth-anthropic](integrations/fusionauth-anthropic.yaml) | Anthropic | AI Telemetry | Attribute Anthropic spend back to FusionAuth users |
| [fusionauth-splunk](integrations/fusionauth-splunk.yaml) | Splunk | Audit | Forward FusionAuth audit + event logs to Splunk HEC |
| [fusionauth-twilio](integrations/fusionauth-twilio.yaml) | Twilio | MFA | Deliver FusionAuth MFA codes via Twilio SMS |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [FusionAuth API (upstream-mirrored, v1.66.0)](openapi/fusionauth-openapi.yaml)

## Capabilities

Naftiko capabilities organized as per-resource definitions covering the FusionAuth API surface.

| Capability | File | Operations |
|------------|------|------------|
| API Key | [fusionauth-api-key.yaml](capabilities/fusionauth-api-key.yaml) | 6 |
| Application | [fusionauth-application.yaml](capabilities/fusionauth-application.yaml) | 20 |
| Connector | [fusionauth-connector.yaml](capabilities/fusionauth-connector.yaml) | 6 |
| Consent | [fusionauth-consent.yaml](capabilities/fusionauth-consent.yaml) | 7 |
| Email Template | [fusionauth-email-template.yaml](capabilities/fusionauth-email-template.yaml) | 10 |
| Entity | [fusionauth-entity.yaml](capabilities/fusionauth-entity.yaml) | 24 |
| Form | [fusionauth-form.yaml](capabilities/fusionauth-form.yaml) | 12 |
| Group | [fusionauth-group.yaml](capabilities/fusionauth-group.yaml) | 11 |
| Health | [fusionauth-health.yaml](capabilities/fusionauth-health.yaml) | 1 |
| Identity | [fusionauth-identity.yaml](capabilities/fusionauth-identity.yaml) | 4 |
| Identity Provider | [fusionauth-identity-provider.yaml](capabilities/fusionauth-identity-provider.yaml) | 17 |
| Integration | [fusionauth-integration.yaml](capabilities/fusionauth-integration.yaml) | 2 |
| IP ACL | [fusionauth-ip-acl.yaml](capabilities/fusionauth-ip-acl.yaml) | 7 |
| JWT | [fusionauth-jwt.yaml](capabilities/fusionauth-jwt.yaml) | 10 |
| Key | [fusionauth-key.yaml](capabilities/fusionauth-key.yaml) | 9 |
| Lambda | [fusionauth-lambda.yaml](capabilities/fusionauth-lambda.yaml) | 8 |
| Login | [fusionauth-login.yaml](capabilities/fusionauth-login.yaml) | 3 |
| Logout | [fusionauth-logout.yaml](capabilities/fusionauth-logout.yaml) | 1 |
| Messenger | [fusionauth-messenger.yaml](capabilities/fusionauth-messenger.yaml) | 14 |
| OAuth2 | [fusionauth-oauth2.yaml](capabilities/fusionauth-oauth2.yaml) | 10 |
| Passwordless | [fusionauth-passwordless.yaml](capabilities/fusionauth-passwordless.yaml) | 3 |
| Reactor | [fusionauth-reactor.yaml](capabilities/fusionauth-reactor.yaml) | 2 |
| Report | [fusionauth-report.yaml](capabilities/fusionauth-report.yaml) | 5 |
| System | [fusionauth-system.yaml](capabilities/fusionauth-system.yaml) | 14 |
| Tenant | [fusionauth-tenant.yaml](capabilities/fusionauth-tenant.yaml) | 9 |
| Tenant Manager | [fusionauth-tenant-manager.yaml](capabilities/fusionauth-tenant-manager.yaml) | 6 |
| Theme | [fusionauth-theme.yaml](capabilities/fusionauth-theme.yaml) | 7 |
| Two-Factor | [fusionauth-two-factor.yaml](capabilities/fusionauth-two-factor.yaml) | 7 |
| User | [fusionauth-user.yaml](capabilities/fusionauth-user.yaml) | 55 |
| User Action | [fusionauth-user-action.yaml](capabilities/fusionauth-user-action.yaml) | 7 |
| User Action Reason | [fusionauth-user-action-reason.yaml](capabilities/fusionauth-user-action-reason.yaml) | 7 |
| WebAuthn | [fusionauth-webauthn.yaml](capabilities/fusionauth-webauthn.yaml) | 10 |
| Webhook | [fusionauth-webhook.yaml](capabilities/fusionauth-webhook.yaml) | 8 |

## Commercial Surface

- [Plans & Pricing](plans/fusionauth-plans-pricing.yml) — API Commons Plans 0.1
- [Rate Limits](rate-limits/fusionauth-rate-limits.yml) — API Commons Rate Limits 0.1
- [FinOps](finops/fusionauth-finops.yml) — FinOps Framework / FOCUS alignment

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
