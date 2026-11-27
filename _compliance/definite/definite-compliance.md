---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: not stated
    text: SOC 2 report Type I available; Type II in progress
    type: Type I report available; Type II in progress
  - framework: GDPR
    issuer: null
    period: null
    report_access: on_request
    scope: EU data processing
    text: Compliant GDPR DPA available; EU data processing agreements supported.
    type: DPA available
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: California residents
    text: Honors consumer data rights for California residents.
    type: consumer data rights compliance statement
  - framework: other
    issuer: null
    period: null
    report_access: on_request
    scope: Enterprise customers with PHI workloads
    text: BAA available for Enterprise customers with PHI workloads.
    type: HIPAA BAA available
  trust_center:
    url: https://www.definite.app/security
frameworks:
- CCPA
- GDPR
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Definite
provenance_date: '2026-11-09'
provider_name: Definite
provider_slug: definite
slug: definite-compliance
source_date: '2026-11-09'
source_filename: definite-compliance.yml
source_heading: Compliance
source_page: https://www.definite.app/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Definite\naid: definite\nurl: https://www.definite.app/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.definite.app/security\nattestations:\n- framework: SOC2\n  type: Type I report available; Type II in progress\n  scope: not stated\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 report Type I available; Type II in progress\n- framework: GDPR\n  type: DPA available\n  scope: EU data processing\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Compliant GDPR DPA available; EU data processing agreements supported.\n- framework: CCPA\n  type:\
  \ consumer data rights compliance statement\n  scope: California residents\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Honors consumer data rights for California residents.\n- framework: other\n  type: HIPAA BAA available\n  scope: Enterprise customers with PHI workloads\n  period: null\n  issuer: null\n  report_access: on_request\n  text: BAA available for Enterprise customers with PHI workloads.\n"
source_yaml_url: https://artifacts.apis.io/definite/compliance/definite-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Definite's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Analytics
- Business Intelligence
- Data Integration
- Data Warehouse
- Lakehouse
- Semantic Layer
- Artificial Intelligence
- AI Agents
- MCP
- ETL
---
