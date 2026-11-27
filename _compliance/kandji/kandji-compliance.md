---
api_specs:
- filename: kandji-audit-api-openapi.yml
  format: yaml
  label: Iru Audit API
  slug: kandji-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kandji/openapi/kandji-audit-api-openapi.yml
- filename: kandji-behavioral-detections-api-openapi.yml
  format: yaml
  label: Iru Behavioral Detections API
  slug: kandji-behavioral-detections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kandji/openapi/kandji-behavioral-detections-api-openapi.yml
- filename: kandji-blueprints-api-openapi.yml
  format: yaml
  label: Iru Blueprints API
  slug: kandji-blueprints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kandji/openapi/kandji-blueprints-api-openapi.yml
- filename: kandji-devices-api-openapi.yml
  format: yaml
  label: Iru Devices API
  slug: kandji-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kandji/openapi/kandji-devices-api-openapi.yml
- filename: kandji-integrations-api-openapi.yml
  format: yaml
  label: Iru Integrations API
  slug: kandji-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kandji/openapi/kandji-integrations-api-openapi.yml
- filename: kandji-library-api-openapi.yml
  format: yaml
  label: Iru Library API
  slug: kandji-library-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kandji/openapi/kandji-library-api-openapi.yml
- filename: kandji-prism-api-openapi.yml
  format: yaml
  label: Iru Prism API
  slug: kandji-prism-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kandji/openapi/kandji-prism-api-openapi.yml
- filename: kandji-self-service-api-openapi.yml
  format: yaml
  label: Iru Self Service API
  slug: kandji-self-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kandji/openapi/kandji-self-service-api-openapi.yml
- filename: kandji-settings-api-openapi.yml
  format: yaml
  label: Iru Settings API
  slug: kandji-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kandji/openapi/kandji-settings-api-openapi.yml
- filename: kandji-tags-api-openapi.yml
  format: yaml
  label: Iru Tags API
  slug: kandji-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kandji/openapi/kandji-tags-api-openapi.yml
- filename: kandji-threat-details-api-openapi.yml
  format: yaml
  label: Iru Threat Details API
  slug: kandji-threat-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kandji/openapi/kandji-threat-details-api-openapi.yml
- filename: kandji-upload-to-s3-api-openapi.yml
  format: yaml
  label: Iru Upload To S3 API
  slug: kandji-upload-to-s3-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kandji/openapi/kandji-upload-to-s3-api-openapi.yml
- filename: kandji-users-api-openapi.yml
  format: yaml
  label: Iru Users API
  slug: kandji-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kandji/openapi/kandji-users-api-openapi.yml
- filename: kandji-vulnerability-management-api-openapi.yml
  format: yaml
  label: Iru Vulnerability Management API
  slug: kandji-vulnerability-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kandji/openapi/kandji-vulnerability-management-api-openapi.yml
- filename: how-to-set-up-the-iru-endpoint-api-in-postman.md
  format: yaml
  label: Iru Endpoint Management API
  slug: iru-endpoint-management-api
  spec_type: Postman
  url: https://docs.iru.com/en/endpoint/api/how-to-set-up-the-iru-endpoint-api-in-postman.md
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Certified SOC 2 Type 2
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Certified ISO 27001
    type: certification
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Certified ISO 42001 Aligned
    type: certification
  - framework: NIST-CSF
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: our program follows the NIST Cybersecurity Framework 2.0
    type: framework alignment
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: apply GDPR controls for consent, access requests, and cross-border transfers by default
    type: compliance
  trust_center:
    url: https://www.iru.com/security
frameworks:
- GDPR
- ISO27001
- ISO42001
- NIST-CSF
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Iru
provenance_date: '2026-11-09'
provider_name: Iru
provider_slug: kandji
slug: kandji-compliance
source_date: '2026-11-09'
source_filename: kandji-compliance.yml
source_heading: Compliance
source_page: https://www.iru.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Iru\naid: kandji\nurl: https://www.iru.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.iru.com/security\nattestations:\n- framework: SOC2\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Certified SOC 2 Type 2\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Certified ISO 27001\n- framework: ISO42001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Certified ISO 42001 Aligned\n- framework: NIST-CSF\n\
  \  type: framework alignment\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: our program follows the NIST Cybersecurity Framework 2.0\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: apply GDPR controls for consent, access requests, and cross-border transfers by default\n"
source_yaml_url: https://artifacts.apis.io/kandji/compliance/kandji-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Iru's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Device Management
- Mobile Device Management
- apple-management
- Endpoint Security
- Endpoint Detection and Response
- Vulnerability Management
- Compliance Automation
- Workforce Identity
- IT Operations
- MCP
- Agent-Native
---
