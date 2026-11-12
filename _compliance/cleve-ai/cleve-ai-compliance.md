---
api_specs:
- filename: cleve-ai-folders-api-openapi.yml
  format: yaml
  label: Cleve Folders API
  slug: cleve-ai-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cleve-ai/openapi/cleve-ai-folders-api-openapi.yml
- filename: cleve-ai-notes-api-openapi.yml
  format: yaml
  label: Cleve Notes API
  slug: cleve-ai-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cleve-ai/openapi/cleve-ai-notes-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: services that process personal data (subprocessors)
    text: All services that process personal data are SOC 2 Type II certified.
    type: SOC 2 Type II (services processing personal data)
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: payment processing via Stripe
    text: 'PCI DSS Level 1 : payment processing via Stripe.'
    type: PCI DSS Level 1 (payment processing via Stripe)
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: personal data of California residents
    text: 'CCPA : we do not sell personal data.'
    type: compliance statement
  trust_center:
    url: https://www.cleve.ai/security
frameworks:
- CCPA
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Cleve
provenance_date: '2026-11-09'
provider_name: Cleve
provider_slug: cleve-ai
slug: cleve-ai-compliance
source_date: '2026-11-09'
source_filename: cleve-ai-compliance.yml
source_heading: Compliance
source_page: https://www.cleve.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Cleve\naid: cleve-ai\nurl: https://www.cleve.ai/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.cleve.ai/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II (services processing personal data)\n  scope: services that process personal data (subprocessors)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: All services that process personal data are SOC 2 Type II certified.\n- framework: PCI-DSS\n  type: PCI DSS Level 1 (payment processing via Stripe)\n  scope: payment processing via Stripe\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'PCI\
  \ DSS Level 1 : payment processing via Stripe.'\n- framework: CCPA\n  type: compliance statement\n  scope: personal data of California residents\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'CCPA : we do not sell personal data.'\n"
source_yaml_url: https://artifacts.apis.io/cleve-ai/compliance/cleve-ai-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Cleve's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Writing
- Knowledge Management
- Note Taking
- Collaboration
- Model Context Protocol
- Productivity
---
