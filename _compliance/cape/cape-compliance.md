---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: all five Trusted Service Criteria (TSCs)
    text: Cape is SOC 2 Type 2 Compliant
    type: SOC 2 Type 2
  - framework: SOC2
    issuer: null
    period: '2025'
    report_access: unstated
    scope: null
    text: 2025 Cape SOC 2 Type 1 Report
    type: SOC 2 Type 1 report
  - framework: SOC3
    issuer: null
    period: '2025'
    report_access: unstated
    scope: null
    text: 2025 Cape SOC 3 Report
    type: SOC 3 report
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CMMC Level 2 (Final, C3PAO)
    type: CMMC Level 2 (Final, C3PAO)
  trust_center:
    url: https://trust.cape.co/
frameworks:
- SOC2
- SOC3
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Cape
provenance_date: '2026-11-09'
provider_name: Cape
provider_slug: cape
slug: cape-compliance
source_date: '2026-11-09'
source_filename: cape-compliance.yml
source_heading: Compliance
source_page: https://trust.cape.co/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Cape\naid: cape\nurl: https://trust.cape.co/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.cape.co/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: all five Trusted Service Criteria (TSCs)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Cape is SOC 2 Type 2 Compliant\n- framework: SOC2\n  type: SOC 2 Type 1 report\n  scope: null\n  period: '2025'\n  issuer: null\n  report_access: unstated\n  text: 2025 Cape SOC 2 Type 1 Report\n- framework: SOC3\n  type: SOC 3 report\n  scope: null\n  period: '2025'\n  issuer: null\n  report_access: unstated\n  text: 2025\
  \ Cape SOC 3 Report\n- framework: other\n  type: CMMC Level 2 (Final, C3PAO)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CMMC Level 2 (Final, C3PAO)\n"
source_yaml_url: https://artifacts.apis.io/cape/compliance/cape-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Cape's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Privacy
- Mobile
- Telecommunications
- Carrier
- MVNO
- Security
- Consumer
---
