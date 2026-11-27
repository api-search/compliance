---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: information security program
    text: maintains a valid ISO/IEC 27001:2022 certification
    type: certification
  - framework: SOC2
    issuer: A-LIGN
    period: null
    report_access: unstated
    scope: null
    text: Globality has completed its SOC2 examination with the guidance of third-party auditing firm A-LIGN.
    type: examination
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Globality closely observes the European Union General Data Protection Regulation and continuously performs audits to ensure compliance.
    type: compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Financial Supplier Qualification System (FSQS) supplier registration
    text: Globality has met all requirements to become fully registered within the Financial Supplier Qualification System (FSQS)
    type: registration
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Glo is not currently FedRAMP Certified.
    type: not certified
  trust_center:
    url: https://www.globality.com/security-trust/
frameworks:
- FedRAMP
- GDPR
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Globality
provenance_date: '2026-11-09'
provider_name: Globality
provider_slug: globality
slug: globality-compliance
source_date: '2026-11-09'
source_filename: globality-compliance.yml
source_heading: Compliance
source_page: https://www.globality.com/security-trust/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Globality\naid: globality\nurl: https://www.globality.com/security-trust/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.globality.com/security-trust/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: information security program\n  period: null\n  issuer: null\n  report_access: unstated\n  text: maintains a valid ISO/IEC 27001:2022 certification\n- framework: SOC2\n  type: examination\n  scope: null\n  period: null\n  issuer: A-LIGN\n  report_access: unstated\n  text: Globality has completed its SOC2 examination with the guidance of third-party auditing firm A-LIGN.\n- framework:\
  \ GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Globality closely observes the European Union General Data Protection Regulation and continuously performs\n    audits to ensure compliance.\n- framework: other\n  type: registration\n  scope: Financial Supplier Qualification System (FSQS) supplier registration\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Globality has met all requirements to become fully registered within the Financial Supplier Qualification\n    System (FSQS)\n- framework: FedRAMP\n  type: not certified\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Glo is not currently FedRAMP Certified.\n"
source_yaml_url: https://artifacts.apis.io/globality/compliance/globality-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Globality's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise
- Procurement
- Sourcing
- Spend Management
- Artificial Intelligence
- Webhook
---
