---
api_specs:
- filename: xata-api-keys-api-openapi.yml
  format: yaml
  label: Xata API Keys API
  slug: xata-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xata/openapi/xata-api-keys-api-openapi.yml
- filename: xata-billing-api-openapi.yml
  format: yaml
  label: Xata Billing API
  slug: xata-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xata/openapi/xata-billing-api-openapi.yml
- filename: xata-branches-api-openapi.yml
  format: yaml
  label: Xata Branches API
  slug: xata-branches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xata/openapi/xata-branches-api-openapi.yml
- filename: xata-gateway-api-openapi.yml
  format: yaml
  label: Xata Gateway API
  slug: xata-gateway-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xata/openapi/xata-gateway-api-openapi.yml
- filename: xata-github-app-api-openapi.yml
  format: yaml
  label: Xata GitHub App API
  slug: xata-github-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xata/openapi/xata-github-app-api-openapi.yml
- filename: xata-logs-api-openapi.yml
  format: yaml
  label: Xata Logs API
  slug: xata-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xata/openapi/xata-logs-api-openapi.yml
- filename: xata-marketplace-api-openapi.yml
  format: yaml
  label: Xata Marketplace API
  slug: xata-marketplace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xata/openapi/xata-marketplace-api-openapi.yml
- filename: xata-metrics-api-openapi.yml
  format: yaml
  label: Xata Metrics API
  slug: xata-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xata/openapi/xata-metrics-api-openapi.yml
- filename: xata-organizations-api-openapi.yml
  format: yaml
  label: Xata Organizations API
  slug: xata-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xata/openapi/xata-organizations-api-openapi.yml
- filename: xata-projects-api-openapi.yml
  format: yaml
  label: Xata Projects API
  slug: xata-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xata/openapi/xata-projects-api-openapi.yml
- filename: xata-projects-webhooks-api-openapi.yml
  format: yaml
  label: Xata Projects Webhooks API
  slug: xata-projects-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xata/openapi/xata-projects-webhooks-api-openapi.yml
- filename: xata-webhooks-api-openapi.yml
  format: yaml
  label: Xata Webhooks API
  slug: xata-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xata/openapi/xata-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: If you require the SOC-2 or HIPAA reports for your own compliance, please contact support.
    type: null
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: If you require the SOC-2 or HIPAA reports for your own compliance, please contact support.
    type: null
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Xata is SOC-2, HIPAA and GDPR compliant and will be seeking more compliance certifications in the future.
    type: null
  trust_center:
    url: https://xata.io/security
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Xata
provenance_date: '2026-11-10'
provider_name: Xata
provider_slug: xata
slug: xata-compliance
source_date: '2026-11-10'
source_filename: xata-compliance.yml
source_heading: Compliance
source_page: https://xata.io/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Xata\naid: xata\nurl: https://xata.io/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/xata-trust-center.yml\ntrust_center:\n  url: https://xata.io/security\nattestations:\n- framework: SOC2\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: If you require the SOC-2 or HIPAA reports for your own compliance, please contact support.\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: If you require the SOC-2 or HIPAA reports for your own compliance, please contact support.\n- framework:\
  \ GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Xata is SOC-2, HIPAA and GDPR compliant and will be seeking more compliance certifications in the future.\n"
source_yaml_url: https://artifacts.apis.io/xata/compliance/xata-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Xata's own page on 2026-11-10.
synthetic: false
tags:
- Database
- PostgreSQL
- Serverless
- Developer Tools
- Branching
- AI Agents
---
