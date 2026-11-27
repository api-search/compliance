---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: availability, confidentiality, and security of data
    text: Accelo maintains a confidential SOC 2 Type 2 report attesting to its commitment to meeting rigorous industry standards
    type: Type 2
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: AWS services used via Key Management Service (KMS)
    text: PCI DSS Level 1.
    type: Level 1
  - framework: ISO27017
    issuer: null
    period: null
    report_access: unstated
    scope: AWS services used via Key Management Service (KMS)
    text: ISO 27017.
    type: certification
  - framework: ISO27018
    issuer: null
    period: null
    report_access: unstated
    scope: AWS services used via Key Management Service (KMS)
    text: ISO 27018.
    type: certification
  trust_center:
    url: https://www.accelo.com/company/security
frameworks:
- ISO27017
- ISO27018
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: forecast
provenance_date: '2026-11-09'
provider_name: forecast
provider_slug: forecast
slug: forecast-compliance
source_date: '2026-11-09'
source_filename: forecast-compliance.yml
source_heading: Compliance
source_page: https://www.accelo.com/company/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: forecast\naid: forecast\nurl: https://www.accelo.com/company/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/forecast-trust-center.yml\ntrust_center:\n  url: https://www.accelo.com/company/security\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: availability, confidentiality, and security of data\n  period: null\n  issuer: null\n  report_access: nda\n  text: Accelo maintains a confidential SOC 2 Type 2 report attesting to its commitment to meeting rigorous industry\n    standards\n- framework: PCI-DSS\n  type: Level 1\n  scope: AWS services used via Key Management Service (KMS)\n\
  \  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS Level 1.\n- framework: ISO27017\n  type: certification\n  scope: AWS services used via Key Management Service (KMS)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27017.\n- framework: ISO27018\n  type: certification\n  scope: AWS services used via Key Management Service (KMS)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27018.\n"
source_yaml_url: https://artifacts.apis.io/forecast/compliance/forecast-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from forecast's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Project Management
- Resource Management
- Professional Services Automation
- Time Tracking
- PSA
---
