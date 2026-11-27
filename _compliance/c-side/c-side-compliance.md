---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Certified
    type: certification
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI DSS Compliant
    type: compliance
  - framework: other
    issuer: VikingCloud
    period: null
    report_access: unstated
    scope: null
    text: VikingCloud solution assessment Certified
    type: certification
  trust_center:
    url: https://trust.cside.com
frameworks:
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: c/side
provenance_date: '2026-11-09'
provider_name: c/side
provider_slug: c-side
slug: c-side-compliance
source_date: '2026-11-09'
source_filename: c-side-compliance.yml
source_heading: Compliance
source_page: https://trust.cside.com
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: c/side\naid: c-side\nurl: https://trust.cside.com\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.cside.com\nattestations:\n- framework: SOC2\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Certified\n- framework: PCI-DSS\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS Compliant\n- framework: other\n  type: certification\n  scope: null\n  period: null\n  issuer: VikingCloud\n  report_access: unstated\n  text: VikingCloud solution assessment Certified\n"
source_yaml_url: https://artifacts.apis.io/c-side/compliance/c-side-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from c/side's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Client-Side Security
- Application Security
- Fraud Prevention
- PCI DSS Compliance
- Device Fingerprinting
- Bot Detection
- Web Security
- Script Monitoring
---
