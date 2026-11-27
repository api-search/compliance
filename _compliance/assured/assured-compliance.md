---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent auditing firm
    period: null
    report_access: unstated
    scope: Assured's security systems and protocols
    text: SOC 2 Type II audit establishes that an independent auditing firm has reviewed, examined, and tested Assured’s security systems and protocols
    type: SOC 2 Type II audit
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: PHI across the Assured Platform
    text: HIPAA certification ensures Assured is compliant with the Health Insurance Portability and Accountability Act
    type: HIPAA certification
  - framework: ISO27001
    issuer: independent accredited auditor
    period: null
    report_access: unstated
    scope: Assured's Information Security Management System (ISMS)
    text: ISO 27001 certification confirms that an independent accredited auditor has validated Assured's Information Security Management System (ISMS)
    type: ISO 27001 certification
  trust_center:
    url: https://www.assured.com/security
frameworks:
- HIPAA
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Assured
provenance_date: '2026-11-09'
provider_name: Assured
provider_slug: assured
slug: assured-compliance
source_date: '2026-11-09'
source_filename: assured-compliance.yml
source_heading: Compliance
source_page: https://www.assured.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Assured\naid: assured\nurl: https://www.assured.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.assured.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: Assured's security systems and protocols\n  period: null\n  issuer: independent auditing firm\n  report_access: unstated\n  text: SOC 2 Type II audit establishes that an independent auditing firm has reviewed, examined, and tested Assured’s\n    security systems and protocols\n- framework: HIPAA\n  type: HIPAA certification\n  scope: PHI across the Assured Platform\n  period: null\n  issuer: null\n\
  \  report_access: unstated\n  text: HIPAA certification ensures Assured is compliant with the Health Insurance Portability and Accountability\n    Act\n- framework: ISO27001\n  type: ISO 27001 certification\n  scope: Assured's Information Security Management System (ISMS)\n  period: null\n  issuer: independent accredited auditor\n  report_access: unstated\n  text: ISO 27001 certification confirms that an independent accredited auditor has validated Assured's Information\n    Security Management System (ISMS)\n"
source_yaml_url: https://artifacts.apis.io/assured/compliance/assured-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Assured's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurtech
- Insurance
- Claims
- Artificial Intelligence
- Property and Casualty
- Claims Automation
- FNOL
- Fraud Prevention
---
