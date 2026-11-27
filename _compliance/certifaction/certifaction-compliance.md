---
api_specs:
- filename: certifaction-account-api-openapi.yml
  format: yaml
  label: Certifaction Account API
  slug: certifaction-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifaction/openapi/certifaction-account-api-openapi.yml
- filename: certifaction-documents-api-openapi.yml
  format: yaml
  label: Certifaction Documents API
  slug: certifaction-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifaction/openapi/certifaction-documents-api-openapi.yml
- filename: certifaction-organization-api-openapi.yml
  format: yaml
  label: Certifaction Organization API
  slug: certifaction-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifaction/openapi/certifaction-organization-api-openapi.yml
- filename: certifaction-server-api-openapi.yml
  format: yaml
  label: Certifaction Server API
  slug: certifaction-server-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifaction/openapi/certifaction-server-api-openapi.yml
- filename: certifaction-signing-api-openapi.yml
  format: yaml
  label: Certifaction Signing API
  slug: certifaction-signing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifaction/openapi/certifaction-signing-api-openapi.yml
- filename: certifaction-teamspace-api-openapi.yml
  format: yaml
  label: Certifaction Teamspace API
  slug: certifaction-teamspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifaction/openapi/certifaction-teamspace-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: TÜV SÜD
    period: null
    report_access: unstated
    scope: information security management system
    text: Certifaction has ISO 27001:2022 certification from TÜV SÜD.
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: data protection
    text: From GDPR and the new Federal Data Protection Act (revFADP) to ZertES and eIDAS - our solution fulfils most regulatory standards in Europe
    type: regulatory compliance
  trust_center:
    url: https://certifaction.com/security-esigning-and-data/
frameworks:
- GDPR
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Certifaction
provenance_date: '2026-11-09'
provider_name: Certifaction
provider_slug: certifaction
slug: certifaction-compliance
source_date: '2026-11-09'
source_filename: certifaction-compliance.yml
source_heading: Compliance
source_page: https://certifaction.com/security-esigning-and-data/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Certifaction\naid: certifaction\nurl: https://certifaction.com/security-esigning-and-data/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://certifaction.com/security-esigning-and-data/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: information security management system\n  period: null\n  issuer: TÜV SÜD\n  report_access: unstated\n  text: Certifaction has ISO 27001:2022 certification from TÜV SÜD.\n- framework: GDPR\n  type: regulatory compliance\n  scope: data protection\n  period: null\n  issuer: null\n  report_access: unstated\n  text: From GDPR and the new Federal Data Protection\
  \ Act (revFADP) to ZertES and eIDAS - our solution fulfils most\n    regulatory standards in Europe\n"
source_yaml_url: https://artifacts.apis.io/certifaction/compliance/certifaction-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Certifaction's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Ai Enterprise Software
- E-Signature
- Digital Signature
- Qualified Electronic Signature
- eIDAS
- Privacy
- Compliance
- Identity Verification
- Switzerland
---
