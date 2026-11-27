---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Security, Availability, and Confidentiality trust service criteria
    text: Nira has achieved its SOC 2 Type 2 certification for three trust service criteria (Security, Availability, and Confidentiality) and is audited annually.
    type: SOC 2 Type 2 certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: customers providing HIPAA-regulated data
    text: Nira has a Business Associate Agreement (BAA) that we will enter into with the customer.
    type: Business Associate Agreement
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: EU and UK Data Processing Addendum available
    text: We are GDPR compliant as a data processor, and a EU and UK Data Processing Addendum (DPA) is available for customers to sign.
    type: GDPR compliant as a data processor
  trust_center:
    url: https://nira.com/security/
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Nira
provenance_date: '2026-11-10'
provider_name: Nira
provider_slug: nira
slug: nira-compliance
source_date: '2026-11-10'
source_filename: nira-compliance.yml
source_heading: Compliance
source_page: https://nira.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Nira\naid: nira\nurl: https://nira.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://nira.com/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 certification\n  scope: Security, Availability, and Confidentiality trust service criteria\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Nira has achieved its SOC 2 Type 2 certification for three trust service criteria (Security, Availability,\n    and Confidentiality) and is audited annually.\n- framework: HIPAA\n  type: Business Associate Agreement\n  scope: customers providing HIPAA-regulated data\n  period:\
  \ null\n  issuer: null\n  report_access: unstated\n  text: Nira has a Business Associate Agreement (BAA) that we will enter into with the customer.\n- framework: GDPR\n  type: GDPR compliant as a data processor\n  scope: EU and UK Data Processing Addendum available\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are GDPR compliant as a data processor, and a EU and UK Data Processing Addendum (DPA) is available for\n    customers to sign.\n"
source_yaml_url: https://artifacts.apis.io/nira/compliance/nira-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Nira's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data Management
- Security
- Cloud
- File Sharing
- Access Control
---
