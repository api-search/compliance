---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: third party auditor
    period: null
    report_access: on_request
    scope: Arrows application and security practices
    text: A copy of our most recent SOC 2 Type II report is available in our trust center .
    type: SOC 2 Type II report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Arrows
    text: Yes, Arrows is GDPR compliant.
    type: compliance statement
  trust_center:
    url: https://arrows.to/security/
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Arrows
provenance_date: '2026-11-09'
provider_name: Arrows
provider_slug: arrows
slug: arrows-compliance
source_date: '2026-11-09'
source_filename: arrows-compliance.yml
source_heading: Compliance
source_page: https://arrows.to/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Arrows\naid: arrows\nurl: https://arrows.to/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://arrows.to/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: Arrows application and security practices\n  period: null\n  issuer: third party auditor\n  report_access: on_request\n  text: A copy of our most recent SOC 2 Type II report is available in our trust center .\n- framework: GDPR\n  type: compliance statement\n  scope: Arrows\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Yes, Arrows is GDPR compliant.\n"
source_yaml_url: https://artifacts.apis.io/arrows/compliance/arrows-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Arrows's own page on 2026-11-09.
synthetic: false
tags:
- Sales
- Artificial Intelligence
- Automation
- CRM
- Software-as-a-Service
- Productivity
---
