---
api_specs:
- filename: convertapi-conversion-api-openapi.yml
  format: yaml
  label: ConvertAPI Conversion API
  slug: convertapi-conversion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convertapi/openapi/convertapi-conversion-api-openapi.yml
- filename: convertapi-file-server-api-openapi.yml
  format: yaml
  label: ConvertAPI File Server API
  slug: convertapi-file-server-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convertapi/openapi/convertapi-file-server-api-openapi.yml
- filename: convertapi-user-api-openapi.yml
  format: yaml
  label: ConvertAPI User API
  slug: convertapi-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convertapi/openapi/convertapi-user-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: TÜV Thüringen
    period: null
    report_access: unstated
    scope: ConvertAPI SaaS platform and file conversion service
    text: ConvertAPI has received the ISO 27001 Information Security Management certification from TÜV Thüringen, demonstrating our commitment to maintaining top-notch security and compliance for our SaaS platform and file conversion service.
    type: certification
  - framework: SOC2
    issuer: independent third-party firm
    period: null
    report_access: on_request
    scope: security, availability, and confidentiality criteria
    text: ConvertAPI has completed a SOC 2 Type 2 audit conducted by an independent third-party firm, validating that our security, availability, and confidentiality controls operate effectively over time.
    type: SOC 2 Type 2 audit
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: document processing service
    text: ConvertAPI is designed to meet the strict privacy and security standards required by the Health Insurance Portability and Accountability Act (HIPAA).
    type: compliance statement
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: ConvertAPI service
    text: our ConvertAPI service is GDPR compliant, so you can be sure that we follow strict data privacy requirements.
    type: compliance statement
  trust_center:
    url: https://www.convertapi.com/compliance
frameworks:
- GDPR
- HIPAA
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: ConvertAPI
provenance_date: '2026-11-09'
provider_name: ConvertAPI
provider_slug: convertapi
slug: convertapi-compliance
source_date: '2026-11-09'
source_filename: convertapi-compliance.yml
source_heading: Compliance
source_page: https://www.convertapi.com/compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: ConvertAPI\naid: convertapi\nurl: https://www.convertapi.com/compliance\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/convertapi-trust-center.yml\ntrust_center:\n  url: https://www.convertapi.com/compliance\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: ConvertAPI SaaS platform and file conversion service\n  period: null\n  issuer: TÜV Thüringen\n  report_access: unstated\n  text: ConvertAPI has received the ISO 27001 Information Security Management certification from TÜV Thüringen,\n    demonstrating our commitment to maintaining top-notch security and compliance for our\
  \ SaaS platform and file\n    conversion service.\n- framework: SOC2\n  type: SOC 2 Type 2 audit\n  scope: security, availability, and confidentiality criteria\n  period: null\n  issuer: independent third-party firm\n  report_access: on_request\n  text: ConvertAPI has completed a SOC 2 Type 2 audit conducted by an independent third-party firm, validating that\n    our security, availability, and confidentiality controls operate effectively over time.\n- framework: HIPAA\n  type: compliance statement\n  scope: document processing service\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ConvertAPI is designed to meet the strict privacy and security standards required by the Health Insurance\n    Portability and Accountability Act (HIPAA).\n- framework: GDPR\n  type: compliance statement\n  scope: ConvertAPI service\n  period: null\n  issuer: null\n  report_access: unstated\n  text: our ConvertAPI service is GDPR compliant, so you can be sure that we follow strict data\
  \ privacy requirements.\n"
source_yaml_url: https://artifacts.apis.io/convertapi/compliance/convertapi-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from ConvertAPI's own page on 2026-11-09.
synthetic: false
tags:
- File Conversion
- PDF
- Documents
- Image
- Audio
- Video
- Ebooks
- Office Documents
- Batch Processing
---
