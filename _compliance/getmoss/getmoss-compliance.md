---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: platform
    text: ISO/IEC 27001:2022 certified
    type: ISO/IEC 27001:2022 certification
  - framework: DORA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliant with Digital Operational Resilience Act (DORA)
    type: regulatory compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: upholding GDPR compliance
    type: regulatory compliance
  - framework: other
    issuer: BaFin
    period: null
    report_access: unstated
    scope: null
    text: BaFin-regulated financial institution under PSD2 framework
    type: BaFin-regulated financial institution under PSD2 framework
  trust_center:
    url: https://www.getmoss.com/security
frameworks:
- DORA
- GDPR
- ISO27001
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Moss
provenance_date: '2026-11-09'
provider_name: Moss
provider_slug: getmoss
slug: getmoss-compliance
source_date: '2026-11-09'
source_filename: getmoss-compliance.yml
source_heading: Compliance
source_page: https://www.getmoss.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Moss\naid: getmoss\nurl: https://www.getmoss.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.getmoss.com/security\nattestations:\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 certification\n  scope: platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 27001:2022 certified\n- framework: DORA\n  type: regulatory compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliant with Digital Operational Resilience Act (DORA)\n- framework: GDPR\n  type: regulatory compliance\n  scope: null\n  period: null\n  issuer:\
  \ null\n  report_access: unstated\n  text: upholding GDPR compliance\n- framework: other\n  type: BaFin-regulated financial institution under PSD2 framework\n  scope: null\n  period: null\n  issuer: BaFin\n  report_access: unstated\n  text: BaFin-regulated financial institution under PSD2 framework\n"
source_yaml_url: https://artifacts.apis.io/getmoss/compliance/getmoss-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Moss's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Automation
- Artificial Intelligence
- European
---
