---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC3
    issuer: null
    period: null
    report_access: public
    scope: operational controls
    text: No NDA is required, so it is perfect for our Small and Medium sized business partners and their compliance needs.
    type: SOC 3 report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal information handling
    text: Matterport's CIO ensures compliance with the privacy regulations and security standards it is subject to, including the California Consumer Privacy Act (CCPA), the General Data Protection Regulation (GDPR)
    type: regulation compliance statement
  trust_center:
    url: https://matterport.com/trust
frameworks:
- GDPR
- SOC3
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: MatterPort
provenance_date: '2026-11-10'
provider_name: MatterPort
provider_slug: matterport
slug: matterport-compliance
source_date: '2026-11-10'
source_filename: matterport-compliance.yml
source_heading: Compliance
source_page: https://matterport.com/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: MatterPort\naid: matterport\nurl: https://matterport.com/trust\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://matterport.com/trust\nattestations:\n- framework: SOC3\n  type: SOC 3 report\n  scope: operational controls\n  period: null\n  issuer: null\n  report_access: public\n  text: No NDA is required, so it is perfect for our Small and Medium sized business partners and their compliance\n    needs.\n- framework: GDPR\n  type: regulation compliance statement\n  scope: personal information handling\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Matterport's CIO ensures compliance\
  \ with the privacy regulations and security standards it is subject to,\n    including the California Consumer Privacy Act (CCPA), the General Data Protection Regulation (GDPR)\n"
source_yaml_url: https://artifacts.apis.io/matterport/compliance/matterport-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from MatterPort's own page on 2026-11-10.
synthetic: false
tags:
- Company
- 3D
- Digital Twin
- Spatial Data
- Real Estate
- Construction
- GraphQL
- SDK
- Computer Vision
- Property Intelligence
---
