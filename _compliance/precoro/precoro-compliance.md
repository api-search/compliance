---
api_specs:
- filename: precoro-openapi-generated.yml
  format: yaml
  label: Precoro API
  slug: precoro-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precoro/openapi/_ae-authored/precoro-openapi-generated.yml
- filename: precoro-invoices-api-openapi.yml
  format: yaml
  label: Precoro Invoices API
  slug: precoro-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precoro/openapi/precoro-invoices-api-openapi.yml
- filename: precoro-items-api-openapi.yml
  format: yaml
  label: Precoro Items API
  slug: precoro-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precoro/openapi/precoro-items-api-openapi.yml
- filename: precoro-legalentities-api-openapi.yml
  format: yaml
  label: Precoro Legalentities API
  slug: precoro-legalentities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precoro/openapi/precoro-legalentities-api-openapi.yml
- filename: precoro-locations-api-openapi.yml
  format: yaml
  label: Precoro Locations API
  slug: precoro-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precoro/openapi/precoro-locations-api-openapi.yml
- filename: precoro-purchaseorders-api-openapi.yml
  format: yaml
  label: Precoro Purchaseorders API
  slug: precoro-purchaseorders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precoro/openapi/precoro-purchaseorders-api-openapi.yml
- filename: precoro-purchaserequisitions-api-openapi.yml
  format: yaml
  label: Precoro Purchaserequisitions API
  slug: precoro-purchaserequisitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precoro/openapi/precoro-purchaserequisitions-api-openapi.yml
- filename: precoro-receipts-api-openapi.yml
  format: yaml
  label: Precoro Receipts API
  slug: precoro-receipts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precoro/openapi/precoro-receipts-api-openapi.yml
- filename: precoro-suppliers-api-openapi.yml
  format: yaml
  label: Precoro Suppliers API
  slug: precoro-suppliers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precoro/openapi/precoro-suppliers-api-openapi.yml
- filename: precoro-taxes-api-openapi.yml
  format: yaml
  label: Precoro Taxes API
  slug: precoro-taxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precoro/openapi/precoro-taxes-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: external AICPA-accredited auditor
    period: null
    report_access: unstated
    scope: 'AICPA Trust Service Criteria: security, availability, processing integrity, confidentiality, privacy'
    text: which issued an SOC 2 Type II report.
    type: Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: data protection
    text: We maintain compliance with leading data protection frameworks, including the General Data Protection Regulation (GDPR), the UK GDPR, the California Consumer Privacy Act (CCPA), and the Health Insurance Portability and Accountability Act (HIPAA).
    type: null
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: privacy
    text: We maintain compliance with leading data protection frameworks, including the General Data Protection Regulation (GDPR), the UK GDPR, the California Consumer Privacy Act (CCPA), and the Health Insurance Portability and Accountability Act (HIPAA).
    type: null
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: privacy
    text: 'Precoro strictly adheres to major compliance standards: GDPR, UK GDPR, SOC 2 Type II, CCPA, and HIPAA.'
    type: null
  trust_center:
    url: https://precoro.com/trust-and-security
frameworks:
- CCPA
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Precoro
provenance_date: '2026-11-10'
provider_name: Precoro
provider_slug: precoro
slug: precoro-compliance
source_date: '2026-11-10'
source_filename: precoro-compliance.yml
source_heading: Compliance
source_page: https://precoro.com/trust-and-security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Precoro\naid: precoro\nurl: https://precoro.com/trust-and-security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://precoro.com/trust-and-security\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: 'AICPA Trust Service Criteria: security, availability, processing integrity, confidentiality, privacy'\n  period: null\n  issuer: external AICPA-accredited auditor\n  report_access: unstated\n  text: which issued an SOC 2 Type II report.\n- framework: GDPR\n  type: null\n  scope: data protection\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We maintain compliance with leading\
  \ data protection frameworks, including the General Data Protection Regulation\n    (GDPR), the UK GDPR, the California Consumer Privacy Act (CCPA), and the Health Insurance Portability and Accountability\n    Act (HIPAA).\n- framework: CCPA\n  type: null\n  scope: privacy\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We maintain compliance with leading data protection frameworks, including the General Data Protection Regulation\n    (GDPR), the UK GDPR, the California Consumer Privacy Act (CCPA), and the Health Insurance Portability and Accountability\n    Act (HIPAA).\n- framework: HIPAA\n  type: null\n  scope: privacy\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'Precoro strictly adheres to major compliance standards: GDPR, UK GDPR, SOC 2 Type II, CCPA, and HIPAA.'\n"
source_yaml_url: https://artifacts.apis.io/precoro/compliance/precoro-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Precoro's own page on 2026-11-10.
synthetic: false
tags:
- Procurement
- Spend Management
- Vendor Management
- Purchase-To-Pay
- AP Automation
- Contract Management
- AI Procurement
---
