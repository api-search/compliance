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
    text: ISO 27001:2022
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Rimsys 2026 SOC2 Type II Section 1
    type: SOC 2 Type II
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO/IEC 42001:2023
    type: certification
  - framework: SOC2
    issuer: third-party assessors
    period: annually
    report_access: unstated
    scope: null
    source: https://www.rimsys.io/security-compliance
    text: We undergo a SOC 2 Type 2 audit annually and an ISO 27001 audit every three years by third-party assessors.
    type: SOC 2 Type 2 audit
  - framework: ISO27001
    issuer: third-party assessors
    period: every three years
    report_access: unstated
    scope: null
    source: https://www.rimsys.io/security-compliance
    text: We undergo a SOC 2 Type 2 audit annually and an ISO 27001 audit every three years by third-party assessors.
    type: ISO 27001 audit
  trust_center:
    url: https://trust.rimsys.io/
frameworks:
- ISO27001
- ISO42001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Rimsys
provenance_date: '2026-11-10'
provider_name: Rimsys
provider_slug: rimsys
slug: rimsys-compliance
source_date: '2026-11-10'
source_filename: rimsys-compliance.yml
source_heading: Compliance
source_page: https://trust.rimsys.io/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Rimsys\naid: rimsys\nurl: https://trust.rimsys.io/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/rimsys-trust-center.yml\n  sources:\n  - https://trust.rimsys.io/\n  - https://www.rimsys.io/security-compliance\ntrust_center:\n  url: https://trust.rimsys.io/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Rimsys 2026 SOC2 Type II Section 1\n- framework: ISO42001\n \
  \ type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 42001:2023\n- framework: SOC2\n  type: SOC 2 Type 2 audit\n  scope: null\n  period: annually\n  issuer: third-party assessors\n  report_access: unstated\n  text: We undergo a SOC 2 Type 2 audit annually and an ISO 27001 audit every three years by third-party assessors.\n  source: https://www.rimsys.io/security-compliance\n- framework: ISO27001\n  type: ISO 27001 audit\n  scope: null\n  period: every three years\n  issuer: third-party assessors\n  report_access: unstated\n  text: We undergo a SOC 2 Type 2 audit annually and an ISO 27001 audit every three years by third-party assessors.\n  source: https://www.rimsys.io/security-compliance\n"
source_yaml_url: https://artifacts.apis.io/rimsys/compliance/rimsys-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Rimsys's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Vertical Software
- Regulatory
- Medical Devices
- Medical Technology
- Regulatory Information Management
- UDI
- Compliance
- Life Sciences
---
