---
api_specs:
- filename: astra-accounts-api-openapi.yml
  format: yaml
  label: Astra Accounts API
  slug: astra-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astra/openapi/astra-accounts-api-openapi.yml
- filename: astra-authorization-api-openapi.yml
  format: yaml
  label: Astra Authorization API
  slug: astra-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astra/openapi/astra-authorization-api-openapi.yml
- filename: astra-cards-api-openapi.yml
  format: yaml
  label: Astra Cards API
  slug: astra-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astra/openapi/astra-cards-api-openapi.yml
- filename: astra-instant-payment-eligibility-api-openapi.yml
  format: yaml
  label: Astra Instant Payment Eligibility API
  slug: astra-instant-payment-eligibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astra/openapi/astra-instant-payment-eligibility-api-openapi.yml
- filename: astra-payment-instruments-api-openapi.yml
  format: yaml
  label: Astra Payment Instruments API
  slug: astra-payment-instruments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astra/openapi/astra-payment-instruments-api-openapi.yml
- filename: astra-routines-api-openapi.yml
  format: yaml
  label: Astra Routines API
  slug: astra-routines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astra/openapi/astra-routines-api-openapi.yml
- filename: astra-transfers-api-openapi.yml
  format: yaml
  label: Astra Transfers API
  slug: astra-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astra/openapi/astra-transfers-api-openapi.yml
- filename: astra-user-api-openapi.yml
  format: yaml
  label: Astra User API
  slug: astra-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astra/openapi/astra-user-api-openapi.yml
claim_count: 10
description: ''
doc:
  attestations:
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 1 Type II
    type: Type II
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II
    type: Type II
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI DSS 4.0.1
    type: DSS 4.0.1
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022
    type: 27001:2022
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: US Data Privacy
    type: US Data Privacy
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: null
  - framework: other
    issuer: External auditors (not named)
    period: null
    report_access: on_request
    scope: Not stated
    source: https://astrafi.com/security-and-privacy/
    text: Astra regularly undergoes external audits, including SOC, PCI, and vulnerability testing
    type: External audit (SOC, unspecified version)
  - framework: PCI-DSS
    issuer: External auditors (not named)
    period: null
    report_access: on_request
    scope: Not stated
    source: https://astrafi.com/security-and-privacy/
    text: Astra regularly undergoes external audits, including SOC, PCI, and vulnerability testing
    type: External audit
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: Privacy Policy
    source: https://astrafi.com/security-and-privacy/
    text: Astra’s Privacy Policy complies with CCPA/CPRA and GDPR frameworks
    type: Privacy regulation compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: All products and services
    source: https://astrafi.com/security-and-privacy/
    text: Astra strictly adheres to data privacy requirements, including CCPA in the U.S. and GDPR in the European Union, across all products and services.
    type: Privacy regulation compliance
  trust_center:
    url: https://trust.astrafi.com/
frameworks:
- CCPA
- GDPR
- ISO27001
- PCI-DSS
- SOC1
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Astra
provenance_date: '2026-11-09'
provider_name: Astra
provider_slug: astra
slug: astra-compliance
source_date: '2026-11-09'
source_filename: astra-compliance.yml
source_heading: Compliance
source_page: https://trust.astrafi.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Astra\naid: astra\nurl: https://trust.astrafi.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://astrafi.com/security-and-privacy/\n  - https://trust.astrafi.com/\ntrust_center:\n  url: https://trust.astrafi.com/\nattestations:\n- framework: SOC1\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 1 Type II\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n- framework: PCI-DSS\n  type: DSS 4.0.1\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: PCI DSS 4.0.1\n- framework: ISO27001\n  type: 27001:2022\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022\n- framework: other\n  type: US Data Privacy\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: US Data Privacy\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: other\n  type: External audit (SOC, unspecified version)\n  scope: Not stated\n  period: null\n  issuer: External auditors (not named)\n  report_access: on_request\n  text: Astra regularly undergoes external audits, including SOC, PCI, and vulnerability testing\n  source: https://astrafi.com/security-and-privacy/\n- framework: PCI-DSS\n  type: External audit\n  scope: Not stated\n  period: null\n  issuer: External auditors (not named)\n  report_access: on_request\n  text: Astra regularly undergoes external audits, including SOC, PCI, and vulnerability\
  \ testing\n  source: https://astrafi.com/security-and-privacy/\n- framework: CCPA\n  type: Privacy regulation compliance\n  scope: Privacy Policy\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Astra’s Privacy Policy complies with CCPA/CPRA and GDPR frameworks\n  source: https://astrafi.com/security-and-privacy/\n- framework: GDPR\n  type: Privacy regulation compliance\n  scope: All products and services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Astra strictly adheres to data privacy requirements, including CCPA in the U.S. and GDPR in the European\n    Union, across all products and services.\n  source: https://astrafi.com/security-and-privacy/\n"
source_yaml_url: https://artifacts.apis.io/astra/compliance/astra-compliance.yml
stated_fields:
- attestations
summary_line: 10 quoted statements, read from Astra's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Fintech
- Money Movement
- ACH
- Instant Payments
- Bank Transfers
- Disbursements
---
