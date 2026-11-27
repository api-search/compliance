---
api_specs:
- filename: avian-openapi-generated.yml
  format: yaml
  label: Avian.io API
  slug: avian-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avian/openapi/_ae-authored/avian-openapi-generated.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Avian is in the process of obtaining SOC 2 Type II certification.
    type: certification in progress
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We comply with applicable data protection regulations, including GDPR and CCPA/CPRA
    type: regulatory compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We comply with applicable data protection regulations, including GDPR and CCPA/CPRA
    type: regulatory compliance
  trust_center:
    url: https://avian.io/security/
frameworks:
- CCPA
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Avian.io
provenance_date: '2026-11-09'
provider_name: Avian.io
provider_slug: avian
slug: avian-compliance
source_date: '2026-11-09'
source_filename: avian-compliance.yml
source_heading: Compliance
source_page: https://avian.io/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Avian.io\naid: avian\nurl: https://avian.io/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://avian.io/security/\nattestations:\n- framework: SOC2\n  type: certification in progress\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Avian is in the process of obtaining SOC 2 Type II certification.\n- framework: GDPR\n  type: regulatory compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We comply with applicable data protection regulations, including GDPR and CCPA/CPRA\n- framework: CCPA\n  type: regulatory compliance\n\
  \  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We comply with applicable data protection regulations, including GDPR and CCPA/CPRA\n"
source_yaml_url: https://artifacts.apis.io/avian/compliance/avian-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Avian.io's own page on 2026-11-09.
synthetic: false
tags:
- Inference
- Compute
- OpenAI Compatibility
- GPU Compute
- Enterprise Security
---
