---
api_specs:
- filename: suger-billing-api-openapi.yml
  format: yaml
  label: Suger Billing API
  slug: suger-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suger/openapi/suger-billing-api-openapi.yml
- filename: suger-buyer-api-openapi.yml
  format: yaml
  label: Suger Buyer API
  slug: suger-buyer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suger/openapi/suger-buyer-api-openapi.yml
- filename: suger-contact-api-openapi.yml
  format: yaml
  label: Suger Contact API
  slug: suger-contact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suger/openapi/suger-contact-api-openapi.yml
- filename: suger-entitlement-api-openapi.yml
  format: yaml
  label: Suger Entitlement API
  slug: suger-entitlement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suger/openapi/suger-entitlement-api-openapi.yml
- filename: suger-metering-api-openapi.yml
  format: yaml
  label: Suger Metering API
  slug: suger-metering-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suger/openapi/suger-metering-api-openapi.yml
- filename: suger-notification-api-openapi.yml
  format: yaml
  label: Suger Notification API
  slug: suger-notification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suger/openapi/suger-notification-api-openapi.yml
- filename: suger-offer-api-openapi.yml
  format: yaml
  label: Suger Offer API
  slug: suger-offer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suger/openapi/suger-offer-api-openapi.yml
- filename: suger-product-api-openapi.yml
  format: yaml
  label: Suger Product API
  slug: suger-product-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suger/openapi/suger-product-api-openapi.yml
- filename: suger-report-api-openapi.yml
  format: yaml
  label: Suger Report API
  slug: suger-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suger/openapi/suger-report-api-openapi.yml
- filename: suger-support-api-openapi.yml
  format: yaml
  label: Suger Support API
  slug: suger-support-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suger/openapi/suger-support-api-openapi.yml
- filename: suger-org-api-openapi.yml
  format: yaml
  label: Suger Org API
  slug: suger-org-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suger/openapi/suger-org-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: annual third-party audits
    report_access: nda
    scope: security, availability, and confidentiality
    text: Fours is SOC 2 Type II certified, with annual third-party audits covering security, availability, and confidentiality.
    type: SOC 2 Type II
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: information security management systems
    text: The certificate is available to enterprise customers on request.
    type: ISO/IEC 27001 certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: EU data protection requirements
    text: Fours complies with GDPR requirements for EU data protection, including lawful processing, data subject rights, and cross-border transfer safeguards.
    type: GDPR compliance
  trust_center:
    url: https://www.fours.com/resources/security/
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Suger
provenance_date: '2026-11-10'
provider_name: Suger
provider_slug: suger
slug: suger-compliance
source_date: '2026-11-10'
source_filename: suger-compliance.yml
source_heading: Compliance
source_page: https://www.fours.com/resources/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Suger\naid: suger\nurl: https://www.fours.com/resources/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/suger-trust-center.yml\ntrust_center:\n  url: https://www.fours.com/resources/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: security, availability, and confidentiality\n  period: annual third-party audits\n  issuer: null\n  report_access: nda\n  text: Fours is SOC 2 Type II certified, with annual third-party audits covering security, availability, and confidentiality.\n- framework: ISO27001\n  type: ISO/IEC 27001 certification\n  scope: information security\
  \ management systems\n  period: null\n  issuer: null\n  report_access: on_request\n  text: The certificate is available to enterprise customers on request.\n- framework: GDPR\n  type: GDPR compliance\n  scope: EU data protection requirements\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Fours complies with GDPR requirements for EU data protection, including lawful processing, data subject\n    rights, and cross-border transfer safeguards.\n"
source_yaml_url: https://artifacts.apis.io/suger/compliance/suger-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Suger's own page on 2026-11-10.
synthetic: false
tags:
- Cloud Marketplace
- Go-To-Market
- Software-as-a-Service
- Billing
- Entitlements
- Revenue
- Co-Sell
- Usage-Based Billing
---
