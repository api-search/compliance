---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: security controls
    text: SOC 2 Type 2 Report Independent audit of our security controls and operational effectiveness.
    type: SOC 2 Type 2 Report
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: on_request
    scope: cardholder data handling
    text: Payment Card Industry Data Security Standard compliance documentation.
    type: PCI DSS 4.0 (SAQ-A)
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliance GDPR SOC 2 Type 2 Request PCI Request
    type: compliance listing
  trust_center:
    url: https://trust.joinsherpa.com/
frameworks:
- GDPR
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Sherpa
provenance_date: '2026-11-09'
provider_name: Sherpa
provider_slug: joinsherpa-com
slug: joinsherpa-com-compliance
source_date: '2026-11-09'
source_filename: joinsherpa-com-compliance.yml
source_heading: Compliance
source_page: https://trust.joinsherpa.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Sherpa\naid: joinsherpa-com\nurl: https://trust.joinsherpa.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.joinsherpa.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 Report\n  scope: security controls\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type 2 Report Independent audit of our security controls and operational effectiveness.\n- framework: PCI-DSS\n  type: PCI DSS 4.0 (SAQ-A)\n  scope: cardholder data handling\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Payment Card Industry Data Security Standard compliance documentation.\n\
  - framework: GDPR\n  type: compliance listing\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance GDPR SOC 2 Type 2 Request PCI Request\n"
source_yaml_url: https://artifacts.apis.io/joinsherpa-com/compliance/joinsherpa-com-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Sherpa's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- eVisa
- Airlines
- TravelTech
---
