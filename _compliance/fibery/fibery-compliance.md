---
api_specs:
- filename: openapi.json
  format: json
  label: Fibery HTTP API
  slug: fibery-http-api
  spec_type: OpenAPI
  url: https://developers.fibery.com/api-reference/openapi.json
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent auditing firm
    period: null
    report_access: on_request
    scope: security policies and controls
    text: We have a SOC 2 Type II report performed by an independent auditing firm certifying that our security policies and controls continuously meet the highest industry standards.
    type: SOC 2 Type II report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Fibery practices, sub-processors, Data Processing Agreement
    text: We are committed to GDPR compliance and offer several data portability and management tools.
    type: GDPR compliance commitment
  - framework: PCI-DSS
    issuer: Braintree
    period: null
    report_access: unstated
    scope: payments processed through Braintree
    text: All payments made to us go through our payments provider, Braintree. Details about their security setup and PCI compliance can be found on Braintree's security page.
    type: PCI compliance via payments provider
  trust_center:
    url: https://fibery.com/security
frameworks:
- GDPR
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Fibery
provenance_date: '2026-11-09'
provider_name: Fibery
provider_slug: fibery
slug: fibery-compliance
source_date: '2026-11-09'
source_filename: fibery-compliance.yml
source_heading: Compliance
source_page: https://fibery.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Fibery\naid: fibery\nurl: https://fibery.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/fibery-trust-center.yml\ntrust_center:\n  url: https://fibery.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: security policies and controls\n  period: null\n  issuer: independent auditing firm\n  report_access: on_request\n  text: We have a SOC 2 Type II report performed by an independent auditing firm certifying that our security policies\n    and controls continuously meet the highest industry standards.\n- framework: GDPR\n  type: GDPR compliance commitment\n\
  \  scope: Fibery practices, sub-processors, Data Processing Agreement\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are committed to GDPR compliance and offer several data portability and management tools.\n- framework: PCI-DSS\n  type: PCI compliance via payments provider\n  scope: payments processed through Braintree\n  period: null\n  issuer: Braintree\n  report_access: unstated\n  text: All payments made to us go through our payments provider, Braintree. Details about their security setup\n    and PCI compliance can be found on Braintree's security page.\n"
source_yaml_url: https://artifacts.apis.io/fibery/compliance/fibery-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Fibery's own page on 2026-11-09.
synthetic: false
tags:
- Work Management
- Project Management
- Collaboration
- No-Code
- Automation
- GraphQL
- Webhook
---
