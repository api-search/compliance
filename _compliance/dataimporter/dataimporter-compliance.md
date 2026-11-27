---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II compliance
    type: Type II
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: HIPAA BAA available on request
    type: Business Associate Agreement (BAA)
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Dataimporter.io complies with the European Union's Global Data Protection Regulation (GDPR).
    type: null
  trust_center:
    url: https://www.dataimporter.io/security
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Dataimporter
provenance_date: '2026-11-09'
provider_name: Dataimporter
provider_slug: dataimporter
slug: dataimporter-compliance
source_date: '2026-11-09'
source_filename: dataimporter-compliance.yml
source_heading: Compliance
source_page: https://www.dataimporter.io/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Dataimporter\naid: dataimporter\nurl: https://www.dataimporter.io/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.dataimporter.io/security\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II compliance\n- framework: HIPAA\n  type: Business Associate Agreement (BAA)\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: HIPAA BAA available on request\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text:\
  \ Dataimporter.io complies with the European Union's Global Data Protection Regulation (GDPR).\n"
source_yaml_url: https://artifacts.apis.io/dataimporter/compliance/dataimporter-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Dataimporter's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Salesforce
- Data Migration
- Import
- Backup
---
