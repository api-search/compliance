---
api_specs:
- filename: giftbit-brands-api-openapi.yml
  format: yaml
  label: Giftbit Brands API
  slug: giftbit-brands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giftbit/openapi/giftbit-brands-api-openapi.yml
- filename: giftbit-campaigns-api-openapi.yml
  format: yaml
  label: Giftbit Campaigns API
  slug: giftbit-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giftbit/openapi/giftbit-campaigns-api-openapi.yml
- filename: giftbit-direct-links-api-openapi.yml
  format: yaml
  label: Giftbit Direct Links API
  slug: giftbit-direct-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giftbit/openapi/giftbit-direct-links-api-openapi.yml
- filename: giftbit-embedded-rewards-api-openapi.yml
  format: yaml
  label: Giftbit Embedded Rewards API
  slug: giftbit-embedded-rewards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giftbit/openapi/giftbit-embedded-rewards-api-openapi.yml
- filename: giftbit-funds-api-openapi.yml
  format: yaml
  label: Giftbit Funds API
  slug: giftbit-funds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giftbit/openapi/giftbit-funds-api-openapi.yml
- filename: giftbit-ping-api-openapi.yml
  format: yaml
  label: Giftbit Ping API
  slug: giftbit-ping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giftbit/openapi/giftbit-ping-api-openapi.yml
- filename: giftbit-regions-api-openapi.yml
  format: yaml
  label: Giftbit Regions API
  slug: giftbit-regions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giftbit/openapi/giftbit-regions-api-openapi.yml
- filename: giftbit-rewards-api-openapi.yml
  format: yaml
  label: Giftbit Rewards API
  slug: giftbit-rewards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giftbit/openapi/giftbit-rewards-api-openapi.yml
- filename: giftbit-short-links-api-openapi.yml
  format: yaml
  label: Giftbit Short Links API
  slug: giftbit-short-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giftbit/openapi/giftbit-short-links-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: annually updated
    report_access: on_request
    scope: Giftbit platform
    text: Giftbit is SOC 2 Type II compliant, with an annually updated report available to support vendor risk assessments and security reviews.
    type: SOC 2 Type II report
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: handling payment card data
    text: Giftbit is a PCI SAQ-D compliant processor, meeting industry standards for handling payment card data securely.
    type: PCI SAQ-D compliant processor
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: privacy by design in systems
    text: Giftbit is a GDPR compliant processor, with privacy built into its systems by design rather than added on afterward.
    type: GDPR compliant processor
  trust_center:
    url: https://www.giftbit.com/security
frameworks:
- GDPR
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Giftbit
provenance_date: '2026-11-09'
provider_name: Giftbit
provider_slug: giftbit
slug: giftbit-compliance
source_date: '2026-11-09'
source_filename: giftbit-compliance.yml
source_heading: Compliance
source_page: https://www.giftbit.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Giftbit\naid: giftbit\nurl: https://www.giftbit.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/giftbit-trust-center.yml\ntrust_center:\n  url: https://www.giftbit.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: Giftbit platform\n  period: annually updated\n  issuer: null\n  report_access: on_request\n  text: Giftbit is SOC 2 Type II compliant, with an annually updated report available to support vendor risk assessments\n    and security reviews.\n- framework: PCI-DSS\n  type: PCI SAQ-D compliant processor\n  scope: handling payment card data\n  period:\
  \ null\n  issuer: null\n  report_access: unstated\n  text: Giftbit is a PCI SAQ-D compliant processor, meeting industry standards for handling payment card data securely.\n- framework: GDPR\n  type: GDPR compliant processor\n  scope: privacy by design in systems\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Giftbit is a GDPR compliant processor, with privacy built into its systems by design rather than added on\n    afterward.\n"
source_yaml_url: https://artifacts.apis.io/giftbit/compliance/giftbit-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Giftbit's own page on 2026-11-09.
synthetic: false
tags:
- Gift Cards
- Digital Rewards
- Incentives
- Payments
- Reward Distribution
- Prepaid Cards
- Loyalty
- Loyalty & Incentives
---
