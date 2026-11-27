---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: HITRUST
    issuer: null
    period: '2024'
    report_access: unstated
    scope: Phreesia CSF certification
    text: HITRUST CSF Certification (2024) Phreesia achieved HITRUST CSF certification
    type: certification
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: PCI DSS Level 1 Service Provider
    text: As a PCI DSS Level 1 Service Provider, Phreesia is committed to upholding industry security standards for cardholder data.
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: security, availability and confidentiality
    text: Phreesia has completed the SOC 2 Type 2 certification process to evaluate our security, availability and confidentiality protocols.
    type: SOC 2 Type 2 certification
  trust_center:
    url: https://www.phreesia.com/platform/#security
frameworks:
- HITRUST
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Phreesia
provenance_date: '2026-11-10'
provider_name: Phreesia
provider_slug: phreesia
slug: phreesia-compliance
source_date: '2026-11-10'
source_filename: phreesia-compliance.yml
source_heading: Compliance
source_page: https://www.phreesia.com/platform/#security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Phreesia\naid: phreesia\nurl: https://www.phreesia.com/platform/#security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/phreesia-trust-center.yml\ntrust_center:\n  url: https://www.phreesia.com/platform/#security\nattestations:\n- framework: HITRUST\n  type: certification\n  scope: Phreesia CSF certification\n  period: '2024'\n  issuer: null\n  report_access: unstated\n  text: HITRUST CSF Certification (2024) Phreesia achieved HITRUST CSF certification\n- framework: PCI-DSS\n  type: certification\n  scope: PCI DSS Level 1 Service Provider\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: As a PCI DSS Level 1 Service Provider, Phreesia is committed to upholding industry security standards for\n    cardholder data.\n- framework: SOC2\n  type: SOC 2 Type 2 certification\n  scope: security, availability and confidentiality\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Phreesia has completed the SOC 2 Type 2 certification process to evaluate our security, availability and\n    confidentiality protocols.\n"
source_yaml_url: https://artifacts.apis.io/phreesia/compliance/phreesia-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Phreesia's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- Patient Intake
- Patient Registration
- Patient Engagement
- Scheduling
- Payments
- Insurance Eligibility
- HL7
- FHIR
- Interoperability
- EHR Integration
- Partner API
---
