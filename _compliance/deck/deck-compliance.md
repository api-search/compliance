---
api_specs:
- filename: deck-connection-api-openapi.yml
  format: yaml
  label: Deck Connection API
  slug: deck-connection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deck/openapi/deck-connection-api-openapi.yml
- filename: deck-jobs-api-openapi.yml
  format: yaml
  label: Deck Jobs API
  slug: deck-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deck/openapi/deck-jobs-api-openapi.yml
- filename: deck-link-api-openapi.yml
  format: yaml
  label: Deck Link API
  slug: deck-link-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deck/openapi/deck-link-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: '2025'
    report_access: unstated
    scope: null
    text: SOC 2 Type II Report - 2025
    type: Type II
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA Compliant
    type: null
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliant
    type: null
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI DSS Compliant
    type: null
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PIPEDA Compliant
    type: null
  trust_center:
    url: https://trust.deck.co/
frameworks:
- GDPR
- HIPAA
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Deck
provenance_date: '2026-11-09'
provider_name: Deck
provider_slug: deck
slug: deck-compliance
source_date: '2026-11-09'
source_filename: deck-compliance.yml
source_heading: Compliance
source_page: https://trust.deck.co/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Deck\naid: deck\nurl: https://trust.deck.co/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.deck.co/\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: '2025'\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II Report - 2025\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Compliant\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliant\n- framework: PCI-DSS\n  type: null\n  scope: null\n  period: null\n  issuer:\
  \ null\n  report_access: unstated\n  text: PCI DSS Compliant\n- framework: other\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PIPEDA Compliant\n"
source_yaml_url: https://artifacts.apis.io/deck/compliance/deck-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Deck's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Automation
- API Integration
- Enterprise
- Security
---
