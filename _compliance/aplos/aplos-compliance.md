---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Aplos payment processing
    text: Aplos is fully PCI compliant
    type: PCI compliance statement
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: E.U.-U.S. Privacy Shield Frameworks
    text: We participate in the E.U.-U.S. Privacy Shield Frameworks and comply with the Privacy Shield Principles
    type: Privacy Shield framework participation
  trust_center:
    url: https://www.aplos.com/security
frameworks:
- PCI-DSS
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Aplos
provenance_date: '2026-11-09'
provider_name: Aplos
provider_slug: aplos
slug: aplos-compliance
source_date: '2026-11-09'
source_filename: aplos-compliance.yml
source_heading: Compliance
source_page: https://www.aplos.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Aplos\naid: aplos\nurl: https://www.aplos.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.aplos.com/security\nattestations:\n- framework: PCI-DSS\n  type: PCI compliance statement\n  scope: Aplos payment processing\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Aplos is fully PCI compliant\n- framework: other\n  type: Privacy Shield framework participation\n  scope: E.U.-U.S. Privacy Shield Frameworks\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We participate in the E.U.-U.S. Privacy Shield Frameworks and comply with the Privacy Shield Principles\n"
source_yaml_url: https://artifacts.apis.io/aplos/compliance/aplos-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Aplos's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Accounting
- Non-Profit
- Software
- Cloud
---
