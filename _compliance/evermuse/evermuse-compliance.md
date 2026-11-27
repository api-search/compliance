---
api_specs:
- filename: evermuse-ingestion-api-openapi.yml
  format: yaml
  label: Evermuse Ingestion API
  slug: evermuse-ingestion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evermuse/openapi/evermuse-ingestion-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Sensiba LLP
    period: null
    report_access: nda
    scope: security, availability, and confidentiality
    text: SOC 2 Type 2 Certified
    type: Type 2 certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: EU data protection requirements
    text: Full compliance with EU data protection requirements.
    type: compliance statement
  trust_center:
    url: https://www.evermuse.com/security
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Evermuse
provenance_date: '2026-11-09'
provider_name: Evermuse
provider_slug: evermuse
slug: evermuse-compliance
source_date: '2026-11-09'
source_filename: evermuse-compliance.yml
source_heading: Compliance
source_page: https://www.evermuse.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Evermuse\naid: evermuse\nurl: https://www.evermuse.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.evermuse.com/security\nattestations:\n- framework: SOC2\n  type: Type 2 certification\n  scope: security, availability, and confidentiality\n  period: null\n  issuer: Sensiba LLP\n  report_access: nda\n  text: SOC 2 Type 2 Certified\n- framework: GDPR\n  type: compliance statement\n  scope: EU data protection requirements\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Full compliance with EU data protection requirements.\n"
source_yaml_url: https://artifacts.apis.io/evermuse/compliance/evermuse-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Evermuse's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Product Management
- Customer Feedback
- Voice of Customer
- Artificial Intelligence
- Data Ingestion
- Product Analytics
- MCP
- Developer Tools
---
