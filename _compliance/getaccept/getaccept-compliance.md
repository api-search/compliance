---
api_specs:
- filename: getaccept-archive-api-openapi.yml
  format: yaml
  label: GetAccept Archive API
  slug: getaccept-archive-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getaccept/openapi/getaccept-archive-api-openapi.yml
- filename: getaccept-attachments-api-openapi.yml
  format: yaml
  label: GetAccept Attachments API
  slug: getaccept-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getaccept/openapi/getaccept-attachments-api-openapi.yml
- filename: getaccept-authentication-api-openapi.yml
  format: yaml
  label: GetAccept Authentication API
  slug: getaccept-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getaccept/openapi/getaccept-authentication-api-openapi.yml
- filename: getaccept-communication-templates-api-openapi.yml
  format: yaml
  label: GetAccept Communication Templates API
  slug: getaccept-communication-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getaccept/openapi/getaccept-communication-templates-api-openapi.yml
- filename: getaccept-contacts-api-openapi.yml
  format: yaml
  label: GetAccept Contacts API
  slug: getaccept-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getaccept/openapi/getaccept-contacts-api-openapi.yml
- filename: getaccept-custom-data-api-openapi.yml
  format: yaml
  label: GetAccept Custom Data API
  slug: getaccept-custom-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getaccept/openapi/getaccept-custom-data-api-openapi.yml
- filename: getaccept-documents-api-openapi.yml
  format: yaml
  label: GetAccept Documents API
  slug: getaccept-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getaccept/openapi/getaccept-documents-api-openapi.yml
- filename: getaccept-others-api-openapi.yml
  format: yaml
  label: GetAccept Others API
  slug: getaccept-others-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getaccept/openapi/getaccept-others-api-openapi.yml
- filename: getaccept-subscriptions-api-openapi.yml
  format: yaml
  label: GetAccept Subscriptions API
  slug: getaccept-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getaccept/openapi/getaccept-subscriptions-api-openapi.yml
- filename: getaccept-templates-api-openapi.yml
  format: yaml
  label: GetAccept Templates API
  slug: getaccept-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getaccept/openapi/getaccept-templates-api-openapi.yml
- filename: getaccept-users-api-openapi.yml
  format: yaml
  label: GetAccept Users API
  slug: getaccept-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getaccept/openapi/getaccept-users-api-openapi.yml
- filename: getaccept-videos-api-openapi.yml
  format: yaml
  label: GetAccept Videos API
  slug: getaccept-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getaccept/openapi/getaccept-videos-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: reputable certified third party auditor
    period: null
    report_access: on_request
    scope: GetAccept services
    text: The latest SOC 2 type 2 report may be requested by reaching out to our support.
    type: SOC 2 Type 2 report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: GetAccept platform and data processing
    text: Fully compliant with GDPR and SOC 2 requirements
    type: compliance with GDPR requirements
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: GetAccept platform and data processing
    text: ensures your data is processed and stored securely in full compliance with Europe’s GDPR and California's CCPA regulation
    type: compliance with CCPA regulation
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: GetAccept eSignatures
    text: GetAccept’s eSignatures are compliant with eIDAS and EU electronic signature technical standards.
    type: eIDAS compliance for electronic signatures
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: GetAccept eSignature solution in the United States
    text: GetAccept complies with the requirements of the U.S. Electronic Signature in Global and National Commerce Act of 2000 (ESIGN), the Uniform Electronic Transactions Act (UETA)
    type: ESIGN and UETA compliance for electronic signatures
  trust_center:
    url: https://www.getaccept.com/security
frameworks:
- CCPA
- GDPR
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: GetAccept
provenance_date: '2026-11-09'
provider_name: GetAccept
provider_slug: getaccept
slug: getaccept-compliance
source_date: '2026-11-09'
source_filename: getaccept-compliance.yml
source_heading: Compliance
source_page: https://www.getaccept.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: GetAccept\naid: getaccept\nurl: https://www.getaccept.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.getaccept.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: GetAccept services\n  period: null\n  issuer: reputable certified third party auditor\n  report_access: on_request\n  text: The latest SOC 2 type 2 report may be requested by reaching out to our support.\n- framework: GDPR\n  type: compliance with GDPR requirements\n  scope: GetAccept platform and data processing\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Fully compliant\
  \ with GDPR and SOC 2 requirements\n- framework: CCPA\n  type: compliance with CCPA regulation\n  scope: GetAccept platform and data processing\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ensures your data is processed and stored securely in full compliance with Europe’s GDPR and California's\n    CCPA regulation\n- framework: other\n  type: eIDAS compliance for electronic signatures\n  scope: GetAccept eSignatures\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GetAccept’s eSignatures are compliant with eIDAS and EU electronic signature technical standards.\n- framework: other\n  type: ESIGN and UETA compliance for electronic signatures\n  scope: GetAccept eSignature solution in the United States\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GetAccept complies with the requirements of the U.S. Electronic Signature in Global and National Commerce\n    Act of 2000 (ESIGN), the Uniform Electronic Transactions Act (UETA)\n"
source_yaml_url: https://artifacts.apis.io/getaccept/compliance/getaccept-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from GetAccept's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud
- Sales Enablement
- E-Signature
- Digital Sales Room
- Document Management
- Contract Management
- Proposals
- Software-as-a-Service
---
