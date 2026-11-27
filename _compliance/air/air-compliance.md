---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent third-party auditor
    period: performed annually
    report_access: nda
    scope: null
    text: A SOC 2 Type II audit is performed annually by an independent third-party auditor.
    type: SOC 2 Type II report
  - framework: ISO27001
    issuer: external vendor
    period: annually
    report_access: nda
    scope: ISMS
    text: Our ISMS is evaluated against ISO/IEC 27001:2022 annually by an external vendor.
    type: ISO/IEC 27001:2022 certificate
  - framework: HIPAA
    issuer: independent third party
    period: null
    report_access: nda
    scope: null
    text: AIR is HIPAA compliant through audits conducted by an independent third party.
    type: HIPAA compliance audit
  trust_center:
    url: https://trust.air.security/
frameworks:
- HIPAA
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: AIR
provenance_date: '2026-11-09'
provider_name: AIR
provider_slug: air
slug: air-compliance
source_date: '2026-11-09'
source_filename: air-compliance.yml
source_heading: Compliance
source_page: https://trust.air.security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: AIR\naid: air\nurl: https://trust.air.security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.air.security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: performed annually\n  issuer: independent third-party auditor\n  report_access: nda\n  text: A SOC 2 Type II audit is performed annually by an independent third-party auditor.\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 certificate\n  scope: ISMS\n  period: annually\n  issuer: external vendor\n  report_access: nda\n  text: Our ISMS is evaluated against ISO/IEC 27001:2022 annually by an external\
  \ vendor.\n- framework: HIPAA\n  type: HIPAA compliance audit\n  scope: null\n  period: null\n  issuer: independent third party\n  report_access: nda\n  text: AIR is HIPAA compliant through audits conducted by an independent third party.\n"
source_yaml_url: https://artifacts.apis.io/air/compliance/air-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from AIR's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Cloud
- Artificial Intelligence
- Security
---
