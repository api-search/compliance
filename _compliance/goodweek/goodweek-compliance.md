---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: SOC 2 Type 2 report available under NDA
    type: Type 2 audit
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliant
    type: compliance
  trust_center:
    url: https://www.goodweek.com/en/security
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Goodweek
provenance_date: '2026-11-09'
provider_name: Goodweek
provider_slug: goodweek
slug: goodweek-compliance
source_date: '2026-11-09'
source_filename: goodweek-compliance.yml
source_heading: Compliance
source_page: https://www.goodweek.com/en/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Goodweek\naid: goodweek\nurl: https://www.goodweek.com/en/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.goodweek.com/en/security\nattestations:\n- framework: SOC2\n  type: Type 2 audit\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: SOC 2 Type 2 report available under NDA\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliant\n"
source_yaml_url: https://artifacts.apis.io/goodweek/compliance/goodweek-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Goodweek's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Platform
- Governance
- Enterprise
---
