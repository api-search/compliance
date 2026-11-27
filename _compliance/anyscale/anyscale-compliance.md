---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: 12-month period
    report_access: on_request
    scope: security, availability and confidentiality criteria
    text: An annual audit covers security, availability and confidentiality criteria, demonstrating effective control operation over a 12-month period.
    type: SOC 2 Type II
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: ISO/IEC 27001 Certificate Request access
    type: ISO/IEC 27001 certificate
  trust_center:
    url: https://trust.anyscale.com/
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Anyscale
provenance_date: '2026-11-09'
provider_name: Anyscale
provider_slug: anyscale
slug: anyscale-compliance
source_date: '2026-11-09'
source_filename: anyscale-compliance.yml
source_heading: Compliance
source_page: https://trust.anyscale.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Anyscale\naid: anyscale\nurl: https://trust.anyscale.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/anyscale-trust-center.yml\ntrust_center:\n  url: https://trust.anyscale.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: security, availability and confidentiality criteria\n  period: 12-month period\n  issuer: null\n  report_access: on_request\n  text: An annual audit covers security, availability and confidentiality criteria, demonstrating effective control\n    operation over a 12-month period.\n- framework: ISO27001\n  type: ISO/IEC 27001 certificate\n  scope: null\n\
  \  period: null\n  issuer: null\n  report_access: on_request\n  text: ISO/IEC 27001 Certificate Request access\n"
source_yaml_url: https://artifacts.apis.io/anyscale/compliance/anyscale-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Anyscale's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Distributed Computing
- Ray
- ML Platform
- Inference
- GPU
---
