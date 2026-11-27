---
api_specs:
- filename: quilt-openapi-generated.yml
  format: yaml
  label: Quilt API
  slug: quilt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quilt/openapi/_ae-authored/quilt-openapi-generated.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: Quilt Cloud
    text: Quilt Cloud is SOC 2 Type II compliant. Report available under NDA for security reviews.
    type: Type II
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Runs on HIPAA-eligible AWS infrastructure
    text: Runs on HIPAA-eligible AWS infrastructure.
    type: HIPAA-eligible infrastructure
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Audit trails with full version history for every dataset
    text: GxP-ready audit trails with full version history for every dataset.
    type: GxP-ready
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Electronic records and audit trails for FDA-regulated workflows
    text: Part 11-ready electronic records and audit trails for FDA-regulated workflows.
    type: 21 CFR Part 11 Ready
  trust_center:
    url: https://www.quilt.bio/security
frameworks:
- HIPAA
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Quilt
provenance_date: '2026-11-10'
provider_name: Quilt
provider_slug: quilt
slug: quilt-compliance
source_date: '2026-11-10'
source_filename: quilt-compliance.yml
source_heading: Compliance
source_page: https://www.quilt.bio/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Quilt\naid: quilt\nurl: https://www.quilt.bio/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.quilt.bio/security\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: Quilt Cloud\n  period: null\n  issuer: null\n  report_access: nda\n  text: Quilt Cloud is SOC 2 Type II compliant. Report available under NDA for security reviews.\n- framework: HIPAA\n  type: HIPAA-eligible infrastructure\n  scope: Runs on HIPAA-eligible AWS infrastructure\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Runs on HIPAA-eligible AWS infrastructure.\n- framework: other\n  type: GxP-ready\n\
  \  scope: Audit trails with full version history for every dataset\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GxP-ready audit trails with full version history for every dataset.\n- framework: other\n  type: 21 CFR Part 11 Ready\n  scope: Electronic records and audit trails for FDA-regulated workflows\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Part 11-ready electronic records and audit trails for FDA-regulated workflows.\n"
source_yaml_url: https://artifacts.apis.io/quilt/compliance/quilt-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Quilt's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data Platform
- Life Sciences
- Amazon Web Services
- Artificial Intelligence
---
