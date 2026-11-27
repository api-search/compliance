---
api_specs:
- filename: missive-analytics-api-openapi.yml
  format: yaml
  label: Missive Analytics API
  slug: missive-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/missive/openapi/missive-analytics-api-openapi.yml
- filename: missive-contact-books-api-openapi.yml
  format: yaml
  label: Missive Contact Books API
  slug: missive-contact-books-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/missive/openapi/missive-contact-books-api-openapi.yml
- filename: missive-contact-groups-api-openapi.yml
  format: yaml
  label: Missive Contact Groups API
  slug: missive-contact-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/missive/openapi/missive-contact-groups-api-openapi.yml
- filename: missive-contacts-api-openapi.yml
  format: yaml
  label: Missive Contacts API
  slug: missive-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/missive/openapi/missive-contacts-api-openapi.yml
- filename: missive-conversations-api-openapi.yml
  format: yaml
  label: Missive Conversations API
  slug: missive-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/missive/openapi/missive-conversations-api-openapi.yml
- filename: missive-drafts-api-openapi.yml
  format: yaml
  label: Missive Drafts API
  slug: missive-drafts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/missive/openapi/missive-drafts-api-openapi.yml
- filename: missive-messages-api-openapi.yml
  format: yaml
  label: Missive Messages API
  slug: missive-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/missive/openapi/missive-messages-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent third-party CPA based in California, USA
    period: null
    report_access: on_request
    scope: security controls of Missive service
    text: Our SOC 2 report is available upon request.
    type: SOC 2 Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Missive
    text: Missive is compliant with the General Data Protection Regulation (GDPR).
    type: GDPR compliance
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: payment processing by Stripe, not Missive
    text: Stripe which is certified as a PCI Level 1 Service Provider.
    type: PCI Level 1 Service Provider (Stripe)
  trust_center:
    url: https://missiveapp.com/security
frameworks:
- GDPR
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Missive
provenance_date: '2026-11-10'
provider_name: Missive
provider_slug: missive
slug: missive-compliance
source_date: '2026-11-10'
source_filename: missive-compliance.yml
source_heading: Compliance
source_page: https://missiveapp.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Missive\naid: missive\nurl: https://missiveapp.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/missive-trust-center.yml\ntrust_center:\n  url: https://missiveapp.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: security controls of Missive service\n  period: null\n  issuer: independent third-party CPA based in California, USA\n  report_access: on_request\n  text: Our SOC 2 report is available upon request.\n- framework: GDPR\n  type: GDPR compliance\n  scope: Missive\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Missive is compliant\
  \ with the General Data Protection Regulation (GDPR).\n- framework: PCI-DSS\n  type: PCI Level 1 Service Provider (Stripe)\n  scope: payment processing by Stripe, not Missive\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Stripe which is certified as a PCI Level 1 Service Provider.\n"
source_yaml_url: https://artifacts.apis.io/missive/compliance/missive-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Missive's own page on 2026-11-10.
synthetic: false
tags:
- Team Inbox
- Collaboration
- Email
- Messaging
- Conversations
- Contacts
- Webhook
- Automation
- REST API
---
