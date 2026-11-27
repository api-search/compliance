---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001 v2022 Compliant
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Compliant
    type: attestation
  trust_center:
    url: https://trust.curity.io/
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Curity
provenance_date: '2026-11-09'
provider_name: Curity
provider_slug: curity
slug: curity-compliance
source_date: '2026-11-09'
source_filename: curity-compliance.yml
source_heading: Compliance
source_page: https://trust.curity.io/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Curity\naid: curity\nurl: https://trust.curity.io/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.curity.io/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 v2022 Compliant\n- framework: SOC2\n  type: attestation\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Compliant\n"
source_yaml_url: https://artifacts.apis.io/curity/compliance/curity-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Curity's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Identity
- OAuth
- OpenID Connect
- Authorization
- API Security
- Authentication
---
