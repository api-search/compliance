---
api_specs:
- filename: evergiving-openapi-generated.yml
  format: yaml
  label: EverGiving API
  slug: evergiving-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evergiving/openapi/_ae-authored/evergiving-openapi-generated.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: independent auditors
    period: null
    report_access: unstated
    scope: entire business
    text: Evergiving is Level 1 PCI DSS Certified across the entire business.
    type: Level 1 PCI DSS Certified
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Evergiving complies fully with GDPR.
    type: compliance statement
  trust_center:
    url: https://www.evergiving.com/security/
frameworks:
- GDPR
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: EverGiving
provenance_date: '2026-11-09'
provider_name: EverGiving
provider_slug: evergiving
slug: evergiving-compliance
source_date: '2026-11-09'
source_filename: evergiving-compliance.yml
source_heading: Compliance
source_page: https://www.evergiving.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: EverGiving\naid: evergiving\nurl: https://www.evergiving.com/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.evergiving.com/security/\nattestations:\n- framework: PCI-DSS\n  type: Level 1 PCI DSS Certified\n  scope: entire business\n  period: null\n  issuer: independent auditors\n  report_access: unstated\n  text: Evergiving is Level 1 PCI DSS Certified across the entire business.\n- framework: GDPR\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Evergiving complies fully with GDPR.\n"
source_yaml_url: https://artifacts.apis.io/evergiving/compliance/evergiving-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from EverGiving's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fundraising
- Non-Profit
- Integration
---
