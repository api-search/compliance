---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Proudly SOC 2 Compliant
    type: Proudly SOC 2 Compliant
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: AWS Infrastructure hosting controls
    text: AWS Infrastructure aligns with PCI DSS 3.2 compliant hosting controls
    type: AWS infrastructure alignment
  trust_center:
    url: https://inveriteinsights.com/security/
frameworks:
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Inverite Verification
provenance_date: '2026-11-09'
provider_name: Inverite Verification
provider_slug: inverite
slug: inverite-compliance
source_date: '2026-11-09'
source_filename: inverite-compliance.yml
source_heading: Compliance
source_page: https://inveriteinsights.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Inverite Verification\naid: inverite\nurl: https://inveriteinsights.com/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://inveriteinsights.com/security/\nattestations:\n- framework: SOC2\n  type: Proudly SOC 2 Compliant\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Proudly SOC 2 Compliant\n- framework: PCI-DSS\n  type: AWS infrastructure alignment\n  scope: AWS Infrastructure hosting controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS Infrastructure aligns with PCI DSS 3.2 compliant hosting controls\n"
source_yaml_url: https://artifacts.apis.io/inverite/compliance/inverite-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Inverite Verification's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Verification
- Risk Scoring
---
