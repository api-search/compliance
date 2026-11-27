---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: '2026'
    report_access: unstated
    scope: null
    text: SOC 2 Type II Report (2026)
    type: Type II
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: null
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: null
  trust_center:
    url: https://trust.neostella.com/
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Neostella
provenance_date: '2026-11-10'
provider_name: Neostella
provider_slug: neostella
slug: neostella-compliance
source_date: '2026-11-10'
source_filename: neostella-compliance.yml
source_heading: Compliance
source_page: https://trust.neostella.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Neostella\naid: neostella\nurl: https://trust.neostella.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.neostella.com/\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II Report (2026)\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n"
source_yaml_url: https://artifacts.apis.io/neostella/compliance/neostella-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Neostella's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Legal Tech
- Software-as-a-Service
- Case Management
- Enterprise
---
