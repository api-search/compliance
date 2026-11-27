---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Application Lucis Compliance
    text: ISO 27001 (2022)
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Hosting of health data in France
    text: HDS certified
    type: certification
  trust_center:
    url: https://compliance.lucis.life/en
frameworks:
- GDPR
- ISO27001
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Lucis
provenance_date: '2026-11-09'
provider_name: Lucis
provider_slug: lucis
slug: lucis-compliance
source_date: '2026-11-09'
source_filename: lucis-compliance.yml
source_heading: Compliance
source_page: https://compliance.lucis.life/en
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Lucis\naid: lucis\nurl: https://compliance.lucis.life/en\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://compliance.lucis.life/en\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Application Lucis Compliance\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 (2022)\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: other\n  type: certification\n  scope: Hosting of health data in France\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HDS certified\n"
source_yaml_url: https://artifacts.apis.io/lucis/compliance/lucis-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Lucis's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Preventative Health
- Longevity
- Biomarkers
- Blood Testing
- Wearables
- Artificial Intelligence
- Consumer Health
- Digital Health
---
