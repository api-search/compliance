---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Prescient Assurance
    period: null
    report_access: unstated
    scope: security
    text: RigUp Inc successfully completed the AICPA Service Organization Control (SOC) 2 Type I audit.
    type: SOC 2 Type 1 audit
  trust_center:
    url: https://trust.rigup.com/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Workrise
provenance_date: '2026-11-10'
provider_name: Workrise
provider_slug: workrise
slug: workrise-compliance
source_date: '2026-11-10'
source_filename: workrise-compliance.yml
source_heading: Compliance
source_page: https://trust.rigup.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Workrise\naid: workrise\nurl: https://trust.rigup.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/workrise-trust-center.yml\ntrust_center:\n  url: https://trust.rigup.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 1 audit\n  scope: security\n  period: null\n  issuer: Prescient Assurance\n  report_access: unstated\n  text: RigUp Inc successfully completed the AICPA Service Organization Control (SOC) 2 Type I audit.\n"
source_yaml_url: https://artifacts.apis.io/workrise/compliance/workrise-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Workrise's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Energy
- Oil and Gas
- Workforce Management
- Vendor Management
- Procurement
- Source-to-Pay
- Workforce
- Software-as-a-Service
---
