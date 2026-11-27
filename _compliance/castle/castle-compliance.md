---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II
    type: Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Ready
    type: Ready
  trust_center:
    url: https://castle.io/trust/
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Castle
provenance_date: '2026-11-09'
provider_name: Castle
provider_slug: castle
slug: castle-compliance
source_date: '2026-11-09'
source_filename: castle-compliance.yml
source_heading: Compliance
source_page: https://castle.io/trust/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Castle\naid: castle\nurl: https://castle.io/trust/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/castle-trust-center.yml\ntrust_center:\n  url: https://castle.io/trust/\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n- framework: GDPR\n  type: Ready\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Ready\n"
source_yaml_url: https://artifacts.apis.io/castle/compliance/castle-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Castle's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Fraud Prevention
- Bot Detection
- Device Fingerprinting
- Account Takeover
- Risk Scoring
- Identity
---
