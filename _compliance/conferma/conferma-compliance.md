---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: Jan 2026
    report_access: unstated
    scope: PCI DSS v4.0.1
    text: Conferma PCI DSS v4.0.1 AoC Jan 2026
    type: Attestation of Compliance
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Information Security Management System (ISMS)
    text: This independent assessment confirms that our Information Security Management System (ISMS) continues to meet the requirements of ISO/IEC 27001:2022.
    type: Certification
  trust_center:
    url: https://trust.conferma.com/
frameworks:
- ISO27001
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Conferma
provenance_date: '2026-11-09'
provider_name: Conferma
provider_slug: conferma
slug: conferma-compliance
source_date: '2026-11-09'
source_filename: conferma-compliance.yml
source_heading: Compliance
source_page: https://trust.conferma.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Conferma\naid: conferma\nurl: https://trust.conferma.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/conferma-trust-center.yml\ntrust_center:\n  url: https://trust.conferma.com/\nattestations:\n- framework: PCI-DSS\n  type: Attestation of Compliance\n  scope: PCI DSS v4.0.1\n  period: Jan 2026\n  issuer: null\n  report_access: unstated\n  text: Conferma PCI DSS v4.0.1 AoC Jan 2026\n- framework: ISO27001\n  type: Certification\n  scope: Information Security Management System (ISMS)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: This independent assessment confirms that our\
  \ Information Security Management System (ISMS) continues to\n    meet the requirements of ISO/IEC 27001:2022.\n"
source_yaml_url: https://artifacts.apis.io/conferma/compliance/conferma-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Conferma's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Virtual Card
- Fintech
- B2B
---
