---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA compliant · SOC 2 Type II report available under NDA
    type: compliance statement
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: SOC 2 Type II report available under NDA
    type: Type II report
  trust_center:
    url: https://www.banquethealth.com/security
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Banquet Health
provenance_date: '2026-11-09'
provider_name: Banquet Health
provider_slug: banquet-health
slug: banquet-health-compliance
source_date: '2026-11-09'
source_filename: banquet-health-compliance.yml
source_heading: Compliance
source_page: https://www.banquethealth.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Banquet Health\naid: banquet-health\nurl: https://www.banquethealth.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.banquethealth.com/security\nattestations:\n- framework: HIPAA\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA compliant · SOC 2 Type II report available under NDA\n- framework: SOC2\n  type: Type II report\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: SOC 2 Type II report available under NDA\n"
source_yaml_url: https://artifacts.apis.io/banquet-health/compliance/banquet-health-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Banquet Health's own page on 2026-11-09.
synthetic: false
tags:
- Food Service Management
- Hospital Software
- Meal Management
- Healthcare Analytics
- Clinical Nutrition
---
