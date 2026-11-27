---
api_specs:
- filename: ledge-sources-api-openapi.yml
  format: yaml
  label: Ledge Sources API
  slug: ledge-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ledge/openapi/ledge-sources-api-openapi.yml
- filename: ledge-transactions-api-openapi.yml
  format: yaml
  label: Ledge Transactions API
  slug: ledge-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ledge/openapi/ledge-transactions-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC1
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 1 and SOC 2 reports are available through trust.ledge.co or upon request from your account team.
    type: SOC 1 report
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Self-serve access to SOC reports, compliance certifications, and security policies
    type: SOC 2 report
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ✓ ISO 42001
    type: ISO 42001 certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: 🔒 GDPR
    type: GDPR compliance
  trust_center:
    url: https://www.ledge.co/security
frameworks:
- GDPR
- ISO42001
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Ledge
provenance_date: '2026-11-09'
provider_name: Ledge
provider_slug: ledge
slug: ledge-compliance
source_date: '2026-11-09'
source_filename: ledge-compliance.yml
source_heading: Compliance
source_page: https://www.ledge.co/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Ledge\naid: ledge\nurl: https://www.ledge.co/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/ledge-trust-center.yml\ntrust_center:\n  url: https://www.ledge.co/security\nattestations:\n- framework: SOC1\n  type: SOC 1 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 1 and SOC 2 reports are available through trust.ledge.co or upon request from your account team.\n- framework: SOC2\n  type: SOC 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Self-serve access to SOC reports, compliance certifications,\
  \ and security policies\n- framework: ISO42001\n  type: ISO 42001 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ✓ ISO 42001\n- framework: GDPR\n  type: GDPR compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: \U0001F512 GDPR\n"
source_yaml_url: https://artifacts.apis.io/ledge/compliance/ledge-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Ledge's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Accounting
- Reconciliation
- Financial Close
- Payment Operations
- Transaction Matching
- Cash Application
- Journal Entries
- AI Agents
- ERP Integration
- Finance Automation
---
