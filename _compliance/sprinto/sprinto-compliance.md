---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001 Compliant
    type: certification badge
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Compliant
    type: compliance badge
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliant
    type: compliance badge
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 42001 v2023 Compliant
    type: compliance badge
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA Compliant
    type: compliance badge
  trust_center:
    url: https://trust.sprinto.com/
frameworks:
- GDPR
- HIPAA
- ISO27001
- ISO42001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Sprinto
provenance_date: '2026-11-10'
provider_name: Sprinto
provider_slug: sprinto
slug: sprinto-compliance
source_date: '2026-11-10'
source_filename: sprinto-compliance.yml
source_heading: Compliance
source_page: https://trust.sprinto.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Sprinto\naid: sprinto\nurl: https://trust.sprinto.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/sprinto-trust-center.yml\ntrust_center:\n  url: https://trust.sprinto.com/\nattestations:\n- framework: ISO27001\n  type: certification badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 Compliant\n- framework: SOC2\n  type: compliance badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Compliant\n- framework: GDPR\n  type: compliance badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: GDPR Compliant\n- framework: ISO42001\n  type: compliance badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 42001 v2023 Compliant\n- framework: HIPAA\n  type: compliance badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Compliant\n"
source_yaml_url: https://artifacts.apis.io/sprinto/compliance/sprinto-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Sprinto's own page on 2026-11-10.
synthetic: false
tags:
- GRC
- Compliance
- SOC 2
- ISO 27001
- Security
- Risk Management
---
