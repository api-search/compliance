---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: 4/1/2025 through 3/31/2026
    report_access: nda
    scope: Signiant Platform
    text: The new report covers audit period 4/1/2025 through 3/31/2026.
    type: SOC 2 Type II report
  - framework: SOC3
    issuer: null
    period: null
    report_access: public
    scope: null
    text: Additionally, Signiant has also obtained a SOC 3 report.
    type: SOC 3 report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: null
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://www.signiant.com/technology/security/
    text: Signiant is SOC 2 compliant.
    type: SOC 2 compliance
  - framework: other
    issuer: Independent Security Evaluators (ISE)
    period: null
    report_access: unstated
    scope: null
    source: https://www.signiant.com/technology/security/
    text: Signiant’s TPN Gold assessment was conducted by Independent Security Evaluators (ISE), a TPN-accredited assessor
    type: TPN Gold assessment
  trust_center:
    url: https://trust.signiant.com/
frameworks:
- GDPR
- SOC2
- SOC3
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Signiant
provenance_date: '2026-11-10'
provider_name: Signiant
provider_slug: signiant
slug: signiant-compliance
source_date: '2026-11-10'
source_filename: signiant-compliance.yml
source_heading: Compliance
source_page: https://trust.signiant.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Signiant\naid: signiant\nurl: https://trust.signiant.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://trust.signiant.com/\n  - https://www.signiant.com/technology/security/\ntrust_center:\n  url: https://trust.signiant.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: Signiant Platform\n  period: 4/1/2025 through 3/31/2026\n  issuer: null\n  report_access: nda\n  text: The new report covers audit period 4/1/2025 through 3/31/2026.\n- framework: SOC3\n  type: SOC 3 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: public\n  text: Additionally, Signiant\
  \ has also obtained a SOC 3 report.\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: SOC2\n  type: SOC 2 compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Signiant is SOC 2 compliant.\n  source: https://www.signiant.com/technology/security/\n- framework: other\n  type: TPN Gold assessment\n  scope: null\n  period: null\n  issuer: Independent Security Evaluators (ISE)\n  report_access: unstated\n  text: Signiant’s TPN Gold assessment was conducted by Independent Security Evaluators (ISE), a TPN-accredited\n    assessor\n  source: https://www.signiant.com/technology/security/\n"
source_yaml_url: https://artifacts.apis.io/signiant/compliance/signiant-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Signiant's own page on 2026-11-10.
synthetic: false
tags:
- File Transfer
- Media Supply Chain
- Managed File Transfer
- Content Delivery
- Storage
- Webhook
- OAuth
- Media and Entertainment
- Authentication
---
