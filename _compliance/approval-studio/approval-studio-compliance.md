---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Data treatment
    text: Your data is treated according to ISO/IEC 27001:2013 and best security practices.
    type: null
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Payments
    text: all payments comply with PCI DSS
    type: null
  trust_center:
    url: https://approval.studio/security/
frameworks:
- ISO27001
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Approval Studio
provenance_date: '2026-11-09'
provider_name: Approval Studio
provider_slug: approval-studio
slug: approval-studio-compliance
source_date: '2026-11-09'
source_filename: approval-studio-compliance.yml
source_heading: Compliance
source_page: https://approval.studio/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Approval Studio\naid: approval-studio\nurl: https://approval.studio/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://approval.studio/security/\nattestations:\n- framework: ISO27001\n  type: null\n  scope: Data treatment\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Your data is treated according to ISO/IEC 27001:2013 and best security practices.\n- framework: PCI-DSS\n  type: null\n  scope: Payments\n  period: null\n  issuer: null\n  report_access: unstated\n  text: all payments comply with PCI DSS\n"
source_yaml_url: https://artifacts.apis.io/approval-studio/compliance/approval-studio-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Approval Studio's own page on 2026-11-09.
synthetic: false
tags:
- Artwork
- Design
- Approval
- Collaboration
- Artificial Intelligence
---
