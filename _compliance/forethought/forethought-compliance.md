---
api_specs:
- filename: forethought-conversations-api-openapi.yml
  format: yaml
  label: Forethought Conversations API
  slug: forethought-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forethought/openapi/forethought-conversations-api-openapi.yml
- filename: forethought-metadata-api-openapi.yml
  format: yaml
  label: Forethought Metadata API
  slug: forethought-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forethought/openapi/forethought-metadata-api-openapi.yml
- filename: forethought-predictions-api-openapi.yml
  format: yaml
  label: Forethought Predictions API
  slug: forethought-predictions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forethought/openapi/forethought-predictions-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: security and availability trust services criteria
    text: Forethought has successfully completed the SOC 2 Type II
    type: SOC 2 Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: customer and employee personal data
    text: Forethought is committed to ensuring that all our customer and employee personal data are treated in a way that complies with the EU’s General Data Protection Regulation (GDPR).
    type: commitment to comply with GDPR
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: personal information of Californian residents
    text: Forethought is committed to be compliant with the CCPA.
    type: commitment to be compliant with CCPA
  trust_center:
    url: https://forethought.ai/compliance
frameworks:
- CCPA
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Forethought
provenance_date: '2026-11-09'
provider_name: Forethought
provider_slug: forethought
slug: forethought-compliance
source_date: '2026-11-09'
source_filename: forethought-compliance.yml
source_heading: Compliance
source_page: https://forethought.ai/compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Forethought\naid: forethought\nurl: https://forethought.ai/compliance\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/forethought-trust-center.yml\ntrust_center:\n  url: https://forethought.ai/compliance\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: security and availability trust services criteria\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Forethought has successfully completed the SOC 2 Type II\n- framework: GDPR\n  type: commitment to comply with GDPR\n  scope: customer and employee personal data\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: Forethought is committed to ensuring that all our customer and employee personal data are treated in a way\n    that complies with the EU’s General Data Protection Regulation (GDPR).\n- framework: CCPA\n  type: commitment to be compliant with CCPA\n  scope: personal information of Californian residents\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Forethought is committed to be compliant with the CCPA.\n"
source_yaml_url: https://artifacts.apis.io/forethought/compliance/forethought-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Forethought's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Customer Service
- Generative AI
- SupportGPT
- Conversational AI
- Ticket Triage
- AI Agents
- Voice AI
- Help Desk
- Multi-Agent
---
