---
claim_count: 6
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: ISO 27001:2022
    type: ISO 27001:2022 badge
  - framework: HITRUST
    issuer: null
    period: null
    report_access: nda
    scope: symplr solutions
    text: HITRUST recertification for symplr solutions
    type: HITRUST recertification
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: symplr SOC 2 Type 2 Report
    type: SOC 2 Type II
  - framework: SOC1
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: SOC 1 Type II
    type: SOC 1 Type II
  - framework: HIPAA
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: symplr Letter of Attestation - HIPAA
    type: HIPAA letter of attestation
  - framework: other
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: NIST
    type: NIST badge (version not stated)
  trust_center:
    url: https://trust.symplr.com/
frameworks:
- HIPAA
- HITRUST
- ISO27001
- SOC1
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: symplr
provenance_date: '2026-11-10'
provider_name: symplr
provider_slug: symplr
slug: symplr-compliance
source_date: '2026-11-10'
source_filename: symplr-compliance.yml
source_heading: Compliance
source_page: https://trust.symplr.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: symplr\naid: symplr\nurl: https://trust.symplr.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/symplr-trust-center.yml\ntrust_center:\n  url: https://trust.symplr.com/\nattestations:\n- framework: ISO27001\n  type: ISO 27001:2022 badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: ISO 27001:2022\n- framework: HITRUST\n  type: HITRUST recertification\n  scope: symplr solutions\n  period: null\n  issuer: null\n  report_access: nda\n  text: HITRUST recertification for symplr solutions\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer:\
  \ null\n  report_access: nda\n  text: symplr SOC 2 Type 2 Report\n- framework: SOC1\n  type: SOC 1 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: SOC 1 Type II\n- framework: HIPAA\n  type: HIPAA letter of attestation\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: symplr Letter of Attestation - HIPAA\n- framework: other\n  type: NIST badge (version not stated)\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: NIST\n"
source_yaml_url: https://artifacts.apis.io/symplr/compliance/symplr-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from symplr's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Healthcare Operations
- Provider Data Management
- Credentialing
- Workforce Management
- Compliance
- Supply Chain
---
