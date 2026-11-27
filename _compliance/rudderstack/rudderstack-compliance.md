---
api_specs:
- filename: rudderstack-event-streaming-asyncapi.yml
  format: yaml
  label: RudderStack Webhook Source API
  slug: rudderstack-webhook-source-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/rudderstack/asyncapi/rudderstack-event-streaming-asyncapi.yml
- filename: rudderstack-http-api-api-openapi.yml
  format: yaml
  label: RudderStack HTTP API
  slug: rudderstack-http-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rudderstack/openapi/rudderstack-http-api-api-openapi.yml
- filename: rudderstack-internal-api-api-openapi.yml
  format: yaml
  label: RudderStack Internal API
  slug: rudderstack-internal-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rudderstack/openapi/rudderstack-internal-api-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We have obtained SOC 2 Type 2 compliance and regularly audit our policies and procedures to ensure continued compliance
    type: SOC 2 Type 2 compliance
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: PHI
    text: We comply with HIPAA requirements for PHI and can sign a BAA
    type: HIPAA compliance for PHI
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: EU data protection requirements
    text: We compliant with GDPR and are constantly adding features to enable you to meet your EU data protection requirements
    type: GDPR compliance
  trust_center:
    url: https://www.rudderstack.com/security/
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: RudderStack
provenance_date: '2026-11-10'
provider_name: RudderStack
provider_slug: rudderstack
slug: rudderstack-compliance
source_date: '2026-11-10'
source_filename: rudderstack-compliance.yml
source_heading: Compliance
source_page: https://www.rudderstack.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: RudderStack\naid: rudderstack\nurl: https://www.rudderstack.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/rudderstack-trust-center.yml\ntrust_center:\n  url: https://www.rudderstack.com/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We have obtained SOC 2 Type 2 compliance and regularly audit our policies and procedures to ensure continued\n    compliance\n- framework: HIPAA\n  type: HIPAA compliance for PHI\n  scope: PHI\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: We comply with HIPAA requirements for PHI and can sign a BAA\n- framework: GDPR\n  type: GDPR compliance\n  scope: EU data protection requirements\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We compliant with GDPR and are constantly adding features to enable you to meet your EU data protection\n    requirements\n"
source_yaml_url: https://artifacts.apis.io/rudderstack/compliance/rudderstack-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from RudderStack's own page on 2026-11-10.
synthetic: false
tags:
- Customer Data Platform
- CDP
- Data Pipeline
- Open Source
- Event Streaming
- Reverse ETL
- Analytics
- Identity Resolution
---
