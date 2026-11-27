---
api_specs:
- filename: torii-apps-api-openapi.yml
  format: yaml
  label: Torii Apps API
  slug: torii-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/torii/openapi/torii-apps-api-openapi.yml
- filename: torii-audit-api-openapi.yml
  format: yaml
  label: Torii Audit API
  slug: torii-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/torii/openapi/torii-audit-api-openapi.yml
- filename: torii-contracts-api-openapi.yml
  format: yaml
  label: Torii Contracts API
  slug: torii-contracts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/torii/openapi/torii-contracts-api-openapi.yml
- filename: torii-files-api-openapi.yml
  format: yaml
  label: Torii Files API
  slug: torii-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/torii/openapi/torii-files-api-openapi.yml
- filename: torii-metadata-api-openapi.yml
  format: yaml
  label: Torii Metadata API
  slug: torii-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/torii/openapi/torii-metadata-api-openapi.yml
- filename: torii-parsings-api-openapi.yml
  format: yaml
  label: Torii Parsings API
  slug: torii-parsings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/torii/openapi/torii-parsings-api-openapi.yml
- filename: torii-scim-api-openapi.yml
  format: yaml
  label: Torii SCIM API
  slug: torii-scim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/torii/openapi/torii-scim-api-openapi.yml
- filename: torii-services-api-openapi.yml
  format: yaml
  label: Torii Services API
  slug: torii-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/torii/openapi/torii-services-api-openapi.yml
- filename: torii-users-api-openapi.yml
  format: yaml
  label: Torii Users API
  slug: torii-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/torii/openapi/torii-users-api-openapi.yml
- filename: torii-workflows-api-openapi.yml
  format: yaml
  label: Torii Workflows API
  slug: torii-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/torii/openapi/torii-workflows-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent auditor
    period: null
    report_access: nda
    scope: security, availability, and confidentiality
    text: Independently audited SOC 2 Type II report covering security, availability, and confidentiality.
    type: SOC 2 Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: EU General Data Protection Regulation compliant data handling
    text: EU General Data Protection Regulation compliant data handling.
    type: GDPR compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: California Consumer Privacy Act
    text: CCPA California Consumer Privacy Act compliant.
    type: CCPA compliance
  - framework: CSA-STAR
    issuer: Cloud Security Alliance
    period: null
    report_access: unstated
    scope: Cloud Security Alliance STAR registry
    text: Listed in the Cloud Security Alliance STAR registry.
    type: CSA STAR registry listing
  trust_center:
    url: https://trust.toriihq.com/trust
frameworks:
- CCPA
- CSA-STAR
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Torii
provenance_date: '2026-11-10'
provider_name: Torii
provider_slug: torii
slug: torii-compliance
source_date: '2026-11-10'
source_filename: torii-compliance.yml
source_heading: Compliance
source_page: https://trust.toriihq.com/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Torii\naid: torii\nurl: https://trust.toriihq.com/trust\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/torii-trust-center.yml\ntrust_center:\n  url: https://trust.toriihq.com/trust\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: security, availability, and confidentiality\n  period: null\n  issuer: independent auditor\n  report_access: nda\n  text: Independently audited SOC 2 Type II report covering security, availability, and confidentiality.\n- framework: GDPR\n  type: GDPR compliance\n  scope: EU General Data Protection Regulation compliant data handling\n  period: null\n  issuer:\
  \ null\n  report_access: unstated\n  text: EU General Data Protection Regulation compliant data handling.\n- framework: CCPA\n  type: CCPA compliance\n  scope: California Consumer Privacy Act\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA California Consumer Privacy Act compliant.\n- framework: CSA-STAR\n  type: CSA STAR registry listing\n  scope: Cloud Security Alliance STAR registry\n  period: null\n  issuer: Cloud Security Alliance\n  report_access: unstated\n  text: Listed in the Cloud Security Alliance STAR registry.\n"
source_yaml_url: https://artifacts.apis.io/torii/compliance/torii-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Torii's own page on 2026-11-10.
synthetic: false
tags:
- Application
- Compliance
- Cost Optimization
- Governance
- IT Management
- SaaS Management
---
