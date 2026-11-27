---
api_specs:
- filename: pimloc-account-api-openapi.yml
  format: yaml
  label: Pimloc Account API
  slug: pimloc-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pimloc/openapi/pimloc-account-api-openapi.yml
- filename: pimloc-authentication-api-openapi.yml
  format: yaml
  label: Pimloc Authentication API
  slug: pimloc-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pimloc/openapi/pimloc-authentication-api-openapi.yml
- filename: pimloc-media-api-openapi.yml
  format: yaml
  label: Pimloc Media API
  slug: pimloc-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pimloc/openapi/pimloc-media-api-openapi.yml
- filename: pimloc-projects-api-openapi.yml
  format: yaml
  label: Pimloc Projects API
  slug: pimloc-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pimloc/openapi/pimloc-projects-api-openapi.yml
- filename: pimloc-secure-redact-api-api-openapi.yml
  format: yaml
  label: Pimloc Secure Redact API
  slug: pimloc-secure-redact-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pimloc/openapi/pimloc-secure-redact-api-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: we have completed SOC 2 Type 2 which includes ensuring proper management of personal information (including PHI)
    type: Type 2
  - framework: CyberEssentials
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Cyber Essentials+ certified
    type: null
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: UK and EU
    text: Secure Redact follows UK and EU GDPR, and CCPA compliance.
    type: null
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Secure Redact follows UK and EU GDPR, and CCPA compliance.
    type: null
  trust_center:
    url: https://www.secureredact.ai/
frameworks:
- CCPA
- CyberEssentials
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Pimloc
provenance_date: '2026-11-10'
provider_name: Pimloc
provider_slug: pimloc
slug: pimloc-compliance
source_date: '2026-11-10'
source_filename: pimloc-compliance.yml
source_heading: Compliance
source_page: https://www.secureredact.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Pimloc\naid: pimloc\nurl: https://www.secureredact.ai/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.secureredact.ai/\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: we have completed SOC 2 Type 2 which includes ensuring proper management of personal information (including\n    PHI)\n- framework: CyberEssentials\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Cyber Essentials+ certified\n- framework: GDPR\n  type: null\n  scope: UK and EU\n  period: null\n  issuer:\
  \ null\n  report_access: unstated\n  text: Secure Redact follows UK and EU GDPR, and CCPA compliance.\n- framework: CCPA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Secure Redact follows UK and EU GDPR, and CCPA compliance.\n"
source_yaml_url: https://artifacts.apis.io/pimloc/compliance/pimloc-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Pimloc's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Privacy
- Video Redaction
- Anonymization
- PII
- Data Protection
- Artificial Intelligence
- Compliance
- Video Analytics
---
