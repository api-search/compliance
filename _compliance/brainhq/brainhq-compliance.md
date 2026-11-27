---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: BrainHQ
    text: BrainHQ complies with the HIPAA technical safeguards
    type: technical safeguards compliance
  - framework: SOC2
    issuer: null
    period: each year
    report_access: unstated
    scope: BrainHQ user data
    text: each year, Posit Science undergoes a security audit following the SOC-2 standard
    type: security audit
  trust_center:
    url: https://www.brainhq.com/en-us/security
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: BrainHQ
provenance_date: '2026-11-09'
provider_name: BrainHQ
provider_slug: brainhq
slug: brainhq-compliance
source_date: '2026-11-09'
source_filename: brainhq-compliance.yml
source_heading: Compliance
source_page: https://www.brainhq.com/en-us/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: BrainHQ\naid: brainhq\nurl: https://www.brainhq.com/en-us/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.brainhq.com/en-us/security\nattestations:\n- framework: HIPAA\n  type: technical safeguards compliance\n  scope: BrainHQ\n  period: null\n  issuer: null\n  report_access: unstated\n  text: BrainHQ complies with the HIPAA technical safeguards\n- framework: SOC2\n  type: security audit\n  scope: BrainHQ user data\n  period: each year\n  issuer: null\n  report_access: unstated\n  text: each year, Posit Science undergoes a security audit following the SOC-2 standard\n"
source_yaml_url: https://artifacts.apis.io/brainhq/compliance/brainhq-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from BrainHQ's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Brain Training
- Cognitive Health
- Software-as-a-Service
- Posit-Science
---
