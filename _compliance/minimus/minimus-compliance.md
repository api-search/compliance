---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Minimus is both SOC-2 and ISO 27001 certified. Reports are available by request.
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Minimus is both SOC-2 and ISO 27001 certified. Reports are available by request.
    type: certification
  trust_center:
    url: https://www.minimus.io/trust-center
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Minimus
provenance_date: '2026-11-10'
provider_name: Minimus
provider_slug: minimus
slug: minimus-compliance
source_date: '2026-11-10'
source_filename: minimus-compliance.yml
source_heading: Compliance
source_page: https://www.minimus.io/trust-center
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Minimus\naid: minimus\nurl: https://www.minimus.io/trust-center\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.minimus.io/trust-center\nattestations:\n- framework: SOC2\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Minimus is both SOC-2 and ISO 27001 certified. Reports are available by request.\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Minimus is both SOC-2 and ISO 27001 certified. Reports are available by request.\n"
source_yaml_url: https://artifacts.apis.io/minimus/compliance/minimus-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Minimus's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Container Images
- Container Security
- Supply Chain Security
- DevSecOps
- Compliance
- CLI
- Hardened Images
---
