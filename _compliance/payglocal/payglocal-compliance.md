---
api_specs:
- filename: payglocal-openapi-generated.yml
  format: yaml
  label: PayGlocal API
  slug: payglocal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payglocal/openapi/_ae-authored/payglocal-openapi-generated.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: payment card information and infrastructure
    text: Our PCI DSS (Payment Card Industry Data Security Standard) certification reflects our commitment to securing payment card information.
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Information Security Management System (ISMS)
    text: ISO/IEC 27001 certification represents our systematic, enterprise-wide approach to information security.
    type: certification
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: Privacy Information Management System (PIMS)
    text: By establishing a mature Privacy Information Management System (PIMS), we ensure that Personally Identifiable Information (PII) is handled responsibly and transparently.
    type: certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: PCI Secure Software Framework for payment applications
    text: Achieving PCI SSF certification showcases our dedication to building and maintaining secure payment applications.
    type: certification
  - framework: SOC2
    issuer: null
    period: Type II
    report_access: unstated
    scope: 'five trust service principles: Security, Availability, Processing Integrity, Confidentiality, and Privacy'
    text: SOC 2 Type II audit affirms that our systems and processes are designed and implemented to meet the highest standards across all five trust service principles
    type: audit
  trust_center:
    url: https://payglocal.in/compliance
frameworks:
- ISO27001
- ISO27701
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: PayGlocal
provenance_date: '2026-11-10'
provider_name: PayGlocal
provider_slug: payglocal
slug: payglocal-compliance
source_date: '2026-11-10'
source_filename: payglocal-compliance.yml
source_heading: Compliance
source_page: https://payglocal.in/compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: PayGlocal\naid: payglocal\nurl: https://payglocal.in/compliance\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://payglocal.in/compliance\nattestations:\n- framework: PCI-DSS\n  type: certification\n  scope: payment card information and infrastructure\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our PCI DSS (Payment Card Industry Data Security Standard) certification reflects our commitment to securing\n    payment card information.\n- framework: ISO27001\n  type: certification\n  scope: Information Security Management System (ISMS)\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: ISO/IEC 27001 certification represents our systematic, enterprise-wide approach to information security.\n- framework: ISO27701\n  type: certification\n  scope: Privacy Information Management System (PIMS)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: By establishing a mature Privacy Information Management System (PIMS), we ensure that Personally Identifiable\n    Information (PII) is handled responsibly and transparently.\n- framework: other\n  type: certification\n  scope: PCI Secure Software Framework for payment applications\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Achieving PCI SSF certification showcases our dedication to building and maintaining secure payment applications.\n- framework: SOC2\n  type: audit\n  scope: 'five trust service principles: Security, Availability, Processing Integrity, Confidentiality, and Privacy'\n  period: Type II\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II audit\
  \ affirms that our systems and processes are designed and implemented to meet the highest\n    standards across all five trust service principles\n"
source_yaml_url: https://artifacts.apis.io/payglocal/compliance/payglocal-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from PayGlocal's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Fintech
- Cross-Border
- RBI-Authorized
---
