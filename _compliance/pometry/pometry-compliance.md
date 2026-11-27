---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: information security management
    text: Information security management is certified to ISO 27001, covering risk treatment, access control and incident handling.
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Pometry software deployed in the customer's environment
    text: Pometry runs as software in your environment and meets all GDPR requirements.
    type: self-stated compliance
  trust_center:
    url: https://www.pometry.com/security/
frameworks:
- GDPR
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Pometry
provenance_date: '2026-11-10'
provider_name: Pometry
provider_slug: pometry
slug: pometry-compliance
source_date: '2026-11-10'
source_filename: pometry-compliance.yml
source_heading: Compliance
source_page: https://www.pometry.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Pometry\naid: pometry\nurl: https://www.pometry.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.pometry.com/security/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: information security management\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Information security management is certified to ISO 27001, covering risk treatment, access control and incident\n    handling.\n- framework: GDPR\n  type: self-stated compliance\n  scope: Pometry software deployed in the customer's environment\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: Pometry runs as software in your environment and meets all GDPR requirements.\n"
source_yaml_url: https://artifacts.apis.io/pometry/compliance/pometry-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Pometry's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Institutional-Intelligence
- Analytics
- Enterprise Software
- Platform
---
