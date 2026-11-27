---
api_specs:
- filename: firma-dev-company-api-openapi.yml
  format: yaml
  label: Firma.dev Company API
  slug: firma-dev-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-company-api-openapi.yml
- filename: firma-dev-custom-fields-api-openapi.yml
  format: yaml
  label: Firma.dev Custom Fields API
  slug: firma-dev-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-custom-fields-api-openapi.yml
- filename: firma-dev-email-domains-api-openapi.yml
  format: yaml
  label: Firma.dev Email Domains API
  slug: firma-dev-email-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-email-domains-api-openapi.yml
- filename: firma-dev-email-templates-api-openapi.yml
  format: yaml
  label: Firma.dev Email Templates API
  slug: firma-dev-email-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-email-templates-api-openapi.yml
- filename: firma-dev-jwt-management-api-openapi.yml
  format: yaml
  label: Firma.dev JWT Management API
  slug: firma-dev-jwt-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-jwt-management-api-openapi.yml
- filename: firma-dev-organization-seals-api-openapi.yml
  format: yaml
  label: Firma.dev Organization Seals API
  slug: firma-dev-organization-seals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-organization-seals-api-openapi.yml
- filename: firma-dev-signer-terms-api-openapi.yml
  format: yaml
  label: Firma.dev Signer Terms API
  slug: firma-dev-signer-terms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-signer-terms-api-openapi.yml
- filename: firma-dev-signing-requests-api-openapi.yml
  format: yaml
  label: Firma.dev Signing Requests API
  slug: firma-dev-signing-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-signing-requests-api-openapi.yml
- filename: firma-dev-templates-api-openapi.yml
  format: yaml
  label: Firma.dev Templates API
  slug: firma-dev-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-templates-api-openapi.yml
- filename: firma-dev-webhooks-api-openapi.yml
  format: yaml
  label: Firma.dev Webhooks API
  slug: firma-dev-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-webhooks-api-openapi.yml
- filename: firma-dev-workspace-settings-api-openapi.yml
  format: yaml
  label: Firma.dev Workspace Settings API
  slug: firma-dev-workspace-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-workspace-settings-api-openapi.yml
- filename: firma-dev-workspaces-api-openapi.yml
  format: yaml
  label: Firma.dev Workspaces API
  slug: firma-dev-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-workspaces-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: AWS
    period: null
    report_access: unstated
    scope: underlying AWS infrastructure
    text: We run on AWS, which maintains SOC 2 Type II, ISO 27001, and HIPAA certifications for the underlying infrastructure.
    type: Type II (AWS infrastructure)
  - framework: ISO27001
    issuer: AWS
    period: null
    report_access: unstated
    scope: underlying AWS infrastructure
    text: We run on AWS, which maintains SOC 2 Type II, ISO 27001, and HIPAA certifications for the underlying infrastructure.
    type: certification (AWS infrastructure)
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: Firma.dev healthcare documents via HIPAA-compliant AWS infrastructure
    text: HIPAA Runs on HIPAA-compliant AWS infrastructure, suitable for healthcare documents. BAA available on request.
    type: compliant infrastructure; BAA available on request
  trust_center:
    url: https://firma.dev/trust
frameworks:
- HIPAA
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Firma.dev
provenance_date: '2026-11-09'
provider_name: Firma.dev
provider_slug: firma-dev
slug: firma-dev-compliance
source_date: '2026-11-09'
source_filename: firma-dev-compliance.yml
source_heading: Compliance
source_page: https://firma.dev/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Firma.dev\naid: firma-dev\nurl: https://firma.dev/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://firma.dev/trust\nattestations:\n- framework: SOC2\n  type: Type II (AWS infrastructure)\n  scope: underlying AWS infrastructure\n  period: null\n  issuer: AWS\n  report_access: unstated\n  text: We run on AWS, which maintains SOC 2 Type II, ISO 27001, and HIPAA certifications for the underlying infrastructure.\n- framework: ISO27001\n  type: certification (AWS infrastructure)\n  scope: underlying AWS infrastructure\n  period: null\n  issuer: AWS\n  report_access: unstated\n  text: We run on AWS, which\
  \ maintains SOC 2 Type II, ISO 27001, and HIPAA certifications for the underlying infrastructure.\n- framework: HIPAA\n  type: compliant infrastructure; BAA available on request\n  scope: Firma.dev healthcare documents via HIPAA-compliant AWS infrastructure\n  period: null\n  issuer: null\n  report_access: on_request\n  text: HIPAA Runs on HIPAA-compliant AWS infrastructure, suitable for healthcare documents. BAA available on request.\n"
source_yaml_url: https://artifacts.apis.io/firma-dev/compliance/firma-dev-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Firma.dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Signature
- Developer Tools
- LowCost
---
