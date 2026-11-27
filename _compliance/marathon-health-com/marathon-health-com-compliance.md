---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA 1 Document
    type: null
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 1 Document
    type: null
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI 1 Document
    type: null
  trust_center:
    url: https://trust.marathon-health.com/
frameworks:
- HIPAA
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Marathon Health
provenance_date: '2026-11-10'
provider_name: Marathon Health
provider_slug: marathon-health-com
slug: marathon-health-com-compliance
source_date: '2026-11-10'
source_filename: marathon-health-com-compliance.yml
source_heading: Compliance
source_page: https://trust.marathon-health.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Marathon Health\naid: marathon-health-com\nurl: https://trust.marathon-health.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.marathon-health.com/\nattestations:\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA 1 Document\n- framework: SOC2\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 1 Document\n- framework: PCI-DSS\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI 1 Document\n"
source_yaml_url: https://artifacts.apis.io/marathon-health-com/compliance/marathon-health-com-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Marathon Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Primary Care
- Employer Benefits
- Value-Based Care
---
