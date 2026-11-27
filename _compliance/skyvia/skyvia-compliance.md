---
api_specs:
- filename: index.html
  format: yaml
  label: Skyvia Public API
  slug: skyvia-public-api
  spec_type: OpenAPI
  url: https://api.skyvia.com/swagger/index.html
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: controls relevant to security, availability, and confidentiality
    text: Skyvia has completed a SOC 2 Type 2 examination covering controls relevant to security, availability, and confidentiality.
    type: SOC 2 Type 2 examination
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data
    text: Skyvia supports customers’ GDPR obligations through a Data Processing Agreement and contractual safeguards for personal data.
    type: GDPR obligations support through Data Processing Agreement
  trust_center:
    url: https://skyvia.com/security
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Skyvia
provenance_date: '2026-11-10'
provider_name: Skyvia
provider_slug: skyvia
slug: skyvia-compliance
source_date: '2026-11-10'
source_filename: skyvia-compliance.yml
source_heading: Compliance
source_page: https://skyvia.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Skyvia\naid: skyvia\nurl: https://skyvia.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://skyvia.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 examination\n  scope: controls relevant to security, availability, and confidentiality\n  period: null\n  issuer: null\n  report_access: nda\n  text: Skyvia has completed a SOC 2 Type 2 examination covering controls relevant to security, availability, and\n    confidentiality.\n- framework: GDPR\n  type: GDPR obligations support through Data Processing Agreement\n  scope: personal data\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: Skyvia supports customers’ GDPR obligations through a Data Processing Agreement and contractual safeguards\n    for personal data.\n"
source_yaml_url: https://artifacts.apis.io/skyvia/compliance/skyvia-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Skyvia's own page on 2026-11-10.
synthetic: false
tags:
- Data Integration
- iPaaS
- ETL
- ELT
- Data Replication
- Cloud Backup
- OData
- SQL
- Workflow Automation
- No-Code
- Connectors
- Data Management
- MCP
- Agent-Native
- Data Access
---
