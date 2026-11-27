---
api_specs:
- filename: paytabs-payments-api-openapi.yml
  format: yaml
  label: PayTabs Payments API
  slug: paytabs-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paytabs/openapi/paytabs-payments-api-openapi.yml
- filename: paytabs-transactions-api-openapi.yml
  format: yaml
  label: PayTabs Transactions API
  slug: paytabs-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paytabs/openapi/paytabs-transactions-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: PayTabs products
    text: certified as Level 1 PCI DSS compliant
    type: Level 1 PCI DSS compliance certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: PayTabs
    text: we comply with various cybersecurity frameworks such as the UAE IA standard and the SAMA cybersecurity framework
    type: cybersecurity standard compliance (UAE IA standard)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: PayTabs
    text: the SAMA cybersecurity framework
    type: cybersecurity framework compliance (SAMA)
  trust_center:
    url: https://ai.paytabs.com/en/security-compliance/
frameworks:
- PCI-DSS
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: PayTabs
provenance_date: '2026-11-10'
provider_name: PayTabs
provider_slug: paytabs
slug: paytabs-compliance
source_date: '2026-11-10'
source_filename: paytabs-compliance.yml
source_heading: Compliance
source_page: https://ai.paytabs.com/en/security-compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: PayTabs\naid: paytabs\nurl: https://ai.paytabs.com/en/security-compliance/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://ai.paytabs.com/en/security-compliance/\nattestations:\n- framework: PCI-DSS\n  type: Level 1 PCI DSS compliance certification\n  scope: PayTabs products\n  period: null\n  issuer: null\n  report_access: unstated\n  text: certified as Level 1 PCI DSS compliant\n- framework: other\n  type: cybersecurity standard compliance (UAE IA standard)\n  scope: PayTabs\n  period: null\n  issuer: null\n  report_access: unstated\n  text: we comply with various cybersecurity frameworks such as the\
  \ UAE IA standard and the SAMA cybersecurity framework\n- framework: other\n  type: cybersecurity framework compliance (SAMA)\n  scope: PayTabs\n  period: null\n  issuer: null\n  report_access: unstated\n  text: the SAMA cybersecurity framework\n"
source_yaml_url: https://artifacts.apis.io/paytabs/compliance/paytabs-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from PayTabs's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Payment Gateway
- Fintech
- MENA
- Saudi Arabia
- Cards
- mada
---
