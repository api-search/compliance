---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: third-party examination
    period: null
    report_access: on_request
    scope: system and services
    text: AiDASH has successfully completed a SOC 2 Type 2 ® Service Organization Control (SOC) audit for our system and services
    type: SOC 2 Type 2 audit
  - framework: SOC3
    issuer: null
    period: null
    report_access: public
    scope: null
    text: SOC 3 ® report. Download publicly available report .
    type: SOC 3 report
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: unstated
    source: https://security.aidash.com/
    text: SOC 2 Compliant
    type: compliance
  trust_center:
    url: https://www.aidash.com/security-compliance-and-responsible-ai/
frameworks:
- SOC2
- SOC3
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: AiDASH
provenance_date: '2026-11-09'
provider_name: AiDASH
provider_slug: aidash
slug: aidash-compliance
source_date: '2026-11-09'
source_filename: aidash-compliance.yml
source_heading: Compliance
source_page: https://www.aidash.com/security-compliance-and-responsible-ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: AiDASH\naid: aidash\nurl: https://www.aidash.com/security-compliance-and-responsible-ai/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/aidash-trust-center.yml\n  sources:\n  - https://security.aidash.com/\n  - https://www.aidash.com/security-compliance-and-responsible-ai/\ntrust_center:\n  url: https://www.aidash.com/security-compliance-and-responsible-ai/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 audit\n  scope: system and services\n  period: null\n  issuer: third-party examination\n  report_access: on_request\n  text: AiDASH has successfully completed a SOC 2 Type 2 ® Service Organization\
  \ Control (SOC) audit for our system\n    and services\n- framework: SOC3\n  type: SOC 3 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: public\n  text: SOC 3 ® report. Download publicly available report .\n- framework: SOC2\n  type: compliance\n  scope: unstated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Compliant\n  source: https://security.aidash.com/\n"
source_yaml_url: https://artifacts.apis.io/aidash/compliance/aidash-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from AiDASH's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Satellite
- Artificial Intelligence
- Geospatial
- Utilities
- Energy
- Vegetation Management
- Wildfire
- Climate Risk
- Asset Management
- Remote Sensing
- Vertical SaaS
---
