---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: information security management system
    text: Our information security management system is independently audited and certified to ISO/IEC 27001:2022
    type: certification
  - framework: SOC2
    issuer: Advantage Partners
    period: null
    report_access: unstated
    scope: design and controls in protecting customer data
    text: Advantage Partners, an independent auditor, has confirmed that Lumana's design and controls in protecting customer data meet the requirements outlined in the AICPA 2017 Trust Services Criteria for Security.
    type: Type 2 auditor confirmation
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Lumana cameras
    text: Lumana cameras comply with the US 2019 National Defense Authorization Act (Section 889)
    type: compliance statement (NDAA Section 889)
  trust_center:
    url: https://www.lumana.ai/trust
frameworks:
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Lumana
provenance_date: '2026-11-09'
provider_name: Lumana
provider_slug: lumana
slug: lumana-compliance
source_date: '2026-11-09'
source_filename: lumana-compliance.yml
source_heading: Compliance
source_page: https://www.lumana.ai/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Lumana\naid: lumana\nurl: https://www.lumana.ai/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.lumana.ai/trust\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: information security management system\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our information security management system is independently audited and certified to ISO/IEC 27001:2022\n- framework: SOC2\n  type: Type 2 auditor confirmation\n  scope: design and controls in protecting customer data\n  period: null\n  issuer: Advantage Partners\n  report_access: unstated\n  text: Advantage\
  \ Partners, an independent auditor, has confirmed that Lumana's design and controls in protecting\n    customer data meet the requirements outlined in the AICPA 2017 Trust Services Criteria for Security.\n- framework: other\n  type: compliance statement (NDAA Section 889)\n  scope: Lumana cameras\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Lumana cameras comply with the US 2019 National Defense Authorization Act (Section 889)\n"
source_yaml_url: https://artifacts.apis.io/lumana/compliance/lumana-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Lumana's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Video Security
- Artificial Intelligence
- Computer Vision
- Physical Security
- Surveillance
- Video Management
- Access Control
---
