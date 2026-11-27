---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: 'SOC 2 Type 2: Our SOC 2 Type II report proves our commitment to security as we aim to keep our customer data secure.'
    type: SOC 2 Type 2
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Protected Health Information
    text: 'HIPAA: In order to handle the most sensitive types of customer information, Dagster Labs (the company behind Dagster) is HIPAA compliant to secure Protected Health Information.'
    type: HIPAA compliance
  trust_center:
    url: https://dagster.io/security
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Elementl
provenance_date: '2026-11-09'
provider_name: Elementl
provider_slug: elementl
slug: elementl-compliance
source_date: '2026-11-09'
source_filename: elementl-compliance.yml
source_heading: Compliance
source_page: https://dagster.io/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Elementl\naid: elementl\nurl: https://dagster.io/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://dagster.io/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: 'SOC 2 Type 2: Our SOC 2 Type II report proves our commitment to security as we aim to keep our customer\n    data secure.'\n- framework: HIPAA\n  type: HIPAA compliance\n  scope: Protected Health Information\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'HIPAA: In order to handle the most sensitive types of customer\
  \ information, Dagster Labs (the company behind\n    Dagster) is HIPAA compliant to secure Protected Health Information.'\n"
source_yaml_url: https://artifacts.apis.io/elementl/compliance/elementl-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Elementl's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Open Source
- Data Orchestration
- Data Engineering
- Data Pipeline
- DataOps
- Observability
- Analytics
- Machine Learning
- Cloud
- Workflow Automation
- Python
---
