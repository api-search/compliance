---
api_specs:
- filename: kareo-administrative-api-openapi.yml
  format: yaml
  label: Kareo Administrative API
  slug: kareo-administrative-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kareo/openapi/kareo-administrative-api-openapi.yml
- filename: kareo-appointments-api-openapi.yml
  format: yaml
  label: Kareo Appointments API
  slug: kareo-appointments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kareo/openapi/kareo-appointments-api-openapi.yml
- filename: kareo-billing-api-openapi.yml
  format: yaml
  label: Kareo Billing API
  slug: kareo-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kareo/openapi/kareo-billing-api-openapi.yml
- filename: kareo-encounters-api-openapi.yml
  format: yaml
  label: Kareo Encounters API
  slug: kareo-encounters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kareo/openapi/kareo-encounters-api-openapi.yml
- filename: kareo-patients-api-openapi.yml
  format: yaml
  label: Kareo Patients API
  slug: kareo-patients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kareo/openapi/kareo-patients-api-openapi.yml
- filename: kareo-providers-api-openapi.yml
  format: yaml
  label: Kareo Providers API
  slug: kareo-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kareo/openapi/kareo-providers-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: HITRUST
    issuer: null
    period: null
    report_access: on_request
    scope: Tebra security program based on HITRUST CSF
    text: Current customers can request a copy of our current security attestations or certification reports by emailing our team
    type: certification/framework
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Controls related to security, availability, and confidentiality
    text: Tebra has obtained a service auditor’s examination report, which includes an opinion on the suitability of the design and operating effectiveness of the controls based on the American Institute of Certified Public Accountants’ (AICPA) Trust Services Principles and Criteria
    type: service auditor examination report
  - framework: PCI-DSS
    issuer: independent auditors
    period: annual
    report_access: on_request
    scope: Handling of credit card information through Tebra Payments
    text: Tebra engages independent auditors to perform annual audits under the Payment Card Industry (PCI) Data Security Standard (DSS) for the handling of credit card information through Tebra Payments.
    type: annual audit
  - framework: NIST-CSF
    issuer: null
    period: null
    report_access: unstated
    scope: Information security framework and policies
    text: National Institute of Standards and Technology (NIST) Cybersecurity Framework
    type: framework
  trust_center:
    url: https://www.tebra.com/security
frameworks:
- HITRUST
- NIST-CSF
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Kareo
provenance_date: '2026-11-09'
provider_name: Kareo
provider_slug: kareo
slug: kareo-compliance
source_date: '2026-11-09'
source_filename: kareo-compliance.yml
source_heading: Compliance
source_page: https://www.tebra.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Kareo\naid: kareo\nurl: https://www.tebra.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/kareo-trust-center.yml\ntrust_center:\n  url: https://www.tebra.com/security\nattestations:\n- framework: HITRUST\n  type: certification/framework\n  scope: Tebra security program based on HITRUST CSF\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Current customers can request a copy of our current security attestations or certification reports by emailing\n    our team\n- framework: SOC2\n  type: service auditor examination report\n  scope: Controls related to security, availability,\
  \ and confidentiality\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Tebra has obtained a service auditor’s examination report, which includes an opinion on the suitability\n    of the design and operating effectiveness of the controls based on the American Institute of Certified Public\n    Accountants’ (AICPA) Trust Services Principles and Criteria\n- framework: PCI-DSS\n  type: annual audit\n  scope: Handling of credit card information through Tebra Payments\n  period: annual\n  issuer: independent auditors\n  report_access: on_request\n  text: Tebra engages independent auditors to perform annual audits under the Payment Card Industry (PCI) Data Security\n    Standard (DSS) for the handling of credit card information through Tebra Payments.\n- framework: NIST-CSF\n  type: framework\n  scope: Information security framework and policies\n  period: null\n  issuer: null\n  report_access: unstated\n  text: National Institute of Standards and Technology (NIST) Cybersecurity\
  \ Framework\n"
source_yaml_url: https://artifacts.apis.io/kareo/compliance/kareo-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Kareo's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Medical Software
- Electronic Health Records
- Practice Management
- Medical Billing
- Patient Scheduling
- Clinical Data
- Insurance Eligibility
- HIPAA
---
