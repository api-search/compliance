---
api_specs:
- filename: phala-apps-api-openapi.yml
  format: yaml
  label: Phala Network Apps API
  slug: phala-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-apps-api-openapi.yml
- filename: phala-apps-kms-info-api-openapi.yml
  format: yaml
  label: Phala Network Apps Kms Info API
  slug: phala-apps-kms-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-apps-kms-info-api-openapi.yml
- filename: phala-apps-pending-updates-api-openapi.yml
  format: yaml
  label: Phala Network Apps Pending Updates API
  slug: phala-apps-pending-updates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-apps-pending-updates-api-openapi.yml
- filename: phala-attestations-api-openapi.yml
  format: yaml
  label: Phala Network Attestations API
  slug: phala-attestations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-attestations-api-openapi.yml
- filename: phala-cvms-api-openapi.yml
  format: yaml
  label: Phala Network CVMs API
  slug: phala-cvms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-cvms-api-openapi.yml
- filename: phala-cvms-network-config-api-openapi.yml
  format: yaml
  label: Phala Network Cvms Network Config API
  slug: phala-cvms-network-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-cvms-network-config-api-openapi.yml
- filename: phala-instance-types-api-openapi.yml
  format: yaml
  label: Phala Network Instance Types API
  slug: phala-instance-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-instance-types-api-openapi.yml
- filename: phala-kms-api-openapi.yml
  format: yaml
  label: Phala Network KMS API
  slug: phala-kms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-kms-api-openapi.yml
- filename: phala-ssh-keys-api-openapi.yml
  format: yaml
  label: Phala Network SSH Keys API
  slug: phala-ssh-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-ssh-keys-api-openapi.yml
- filename: phala-webhooks-api-openapi.yml
  format: yaml
  label: Phala Network Webhooks API
  slug: phala-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: unstated
    text: SOC 2 Type I report
    type: Type I report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: unstated
    text: HIPAA controls
    type: controls
  trust_center:
    url: https://phala.com/trust
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Phala Network
provenance_date: '2026-11-10'
provider_name: Phala Network
provider_slug: phala
slug: phala-compliance
source_date: '2026-11-10'
source_filename: phala-compliance.yml
source_heading: Compliance
source_page: https://phala.com/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Phala Network\naid: phala\nurl: https://phala.com/trust\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://phala.com/trust\nattestations:\n- framework: SOC2\n  type: Type I report\n  scope: unstated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type I report\n- framework: HIPAA\n  type: controls\n  scope: unstated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA controls\n"
source_yaml_url: https://artifacts.apis.io/phala/compliance/phala-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Phala Network's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Confidential Computing
- Trusted Execution Environments
- Inference
- Cloud Infrastructure
- Attestation
- LLM Router
---
