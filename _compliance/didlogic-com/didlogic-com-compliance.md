---
api_specs:
- filename: didlogic-com-account-balance-api-openapi.yml
  format: yaml
  label: DID Logic Account Balance API
  slug: didlogic-com-account-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/didlogic-com/openapi/didlogic-com-account-balance-api-openapi.yml
- filename: didlogic-com-api-access-api-openapi.yml
  format: yaml
  label: DID Logic API Access API
  slug: didlogic-com-api-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/didlogic-com/openapi/didlogic-com-api-access-api-openapi.yml
- filename: didlogic-com-calls-api-openapi.yml
  format: yaml
  label: DID Logic Calls API
  slug: didlogic-com-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/didlogic-com/openapi/didlogic-com-calls-api-openapi.yml
- filename: didlogic-com-click2call-api-openapi.yml
  format: yaml
  label: DID Logic Click2 Call API
  slug: didlogic-com-click2call-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/didlogic-com/openapi/didlogic-com-click2call-api-openapi.yml
- filename: didlogic-com-hlr-lookups-api-openapi.yml
  format: yaml
  label: DID Logic HLR Lookups API
  slug: didlogic-com-hlr-lookups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/didlogic-com/openapi/didlogic-com-hlr-lookups-api-openapi.yml
- filename: didlogic-com-identities-api-openapi.yml
  format: yaml
  label: DID Logic Identities API
  slug: didlogic-com-identities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/didlogic-com/openapi/didlogic-com-identities-api-openapi.yml
- filename: didlogic-com-inbound-destinations-api-openapi.yml
  format: yaml
  label: DID Logic Inbound Destinations API
  slug: didlogic-com-inbound-destinations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/didlogic-com/openapi/didlogic-com-inbound-destinations-api-openapi.yml
- filename: didlogic-com-kyc-documents-api-openapi.yml
  format: yaml
  label: DID Logic KYC Documents API
  slug: didlogic-com-kyc-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/didlogic-com/openapi/didlogic-com-kyc-documents-api-openapi.yml
- filename: didlogic-com-numbers-inventory-api-openapi.yml
  format: yaml
  label: DID Logic Numbers & Inventory API
  slug: didlogic-com-numbers-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/didlogic-com/openapi/didlogic-com-numbers-inventory-api-openapi.yml
- filename: didlogic-com-purchases-api-openapi.yml
  format: yaml
  label: DID Logic Purchases API
  slug: didlogic-com-purchases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/didlogic-com/openapi/didlogic-com-purchases-api-openapi.yml
- filename: didlogic-com-reports-api-openapi.yml
  format: yaml
  label: DID Logic Reports API
  slug: didlogic-com-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/didlogic-com/openapi/didlogic-com-reports-api-openapi.yml
- filename: didlogic-com-risk-checks-api-openapi.yml
  format: yaml
  label: DID Logic Risk Checks API
  slug: didlogic-com-risk-checks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/didlogic-com/openapi/didlogic-com-risk-checks-api-openapi.yml
- filename: didlogic-com-sip-accounts-api-openapi.yml
  format: yaml
  label: DID Logic SIP Accounts API
  slug: didlogic-com-sip-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/didlogic-com/openapi/didlogic-com-sip-accounts-api-openapi.yml
- filename: didlogic-com-sms-api-openapi.yml
  format: yaml
  label: DID Logic SMS API
  slug: didlogic-com-sms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/didlogic-com/openapi/didlogic-com-sms-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: TÜV AUSTRIA Hellas
    period: Valid until 3 May 2029
    report_access: unstated
    scope: Information security management system covering voice infrastructure, customer voice traffic, CDRs, and DID data across development, operations, and support
    text: ISO/IEC 27001:2022 Information Security Management System Certificate No. 20201260019137 Valid until 3 May 2029 Issued by TÜV AUSTRIA Hellas
    type: Certification (ISO/IEC 27001:2022)
  - framework: ISO9001
    issuer: TÜV AUSTRIA Hellas
    period: Valid until 3 May 2029
    report_access: unstated
    scope: Quality management system covering how telecommunication services are built, delivered, and supported
    text: EN ISO 9001:2015 Quality Management System Certificate No. 20001260019136 Valid until 3 May 2029 Issued by TÜV AUSTRIA Hellas
    type: Certification (EN ISO 9001:2015)
  trust_center:
    url: https://didlogic.com/security/
frameworks:
- ISO27001
- ISO9001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: DID Logic
provenance_date: '2026-11-09'
provider_name: DID Logic
provider_slug: didlogic-com
slug: didlogic-com-compliance
source_date: '2026-11-09'
source_filename: didlogic-com-compliance.yml
source_heading: Compliance
source_page: https://didlogic.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: DID Logic\naid: didlogic-com\nurl: https://didlogic.com/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://didlogic.com/security/\nattestations:\n- framework: ISO27001\n  type: Certification (ISO/IEC 27001:2022)\n  scope: Information security management system covering voice infrastructure, customer voice traffic, CDRs, and\n    DID data across development, operations, and support\n  period: Valid until 3 May 2029\n  issuer: TÜV AUSTRIA Hellas\n  report_access: unstated\n  text: ISO/IEC 27001:2022 Information Security Management System Certificate No. 20201260019137 Valid until 3 May\n    2029\
  \ Issued by TÜV AUSTRIA Hellas\n- framework: ISO9001\n  type: Certification (EN ISO 9001:2015)\n  scope: Quality management system covering how telecommunication services are built, delivered, and supported\n  period: Valid until 3 May 2029\n  issuer: TÜV AUSTRIA Hellas\n  report_access: unstated\n  text: EN ISO 9001:2015 Quality Management System Certificate No. 20001260019136 Valid until 3 May 2029 Issued\n    by TÜV AUSTRIA Hellas\n"
source_yaml_url: https://artifacts.apis.io/didlogic-com/compliance/didlogic-com-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from DID Logic's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Telecommunications
- VoIP
- SIP Trunking
- DID Numbers
- SMS
- Voice
- MCP
---
