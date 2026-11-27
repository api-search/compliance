---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: Security, Trust, Assurance and Risk (STAR)
    text: CSA - Security, Trust, Assurance and Risk (STAR)
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC2 Type II Certification
    type: SOC2 Type II certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: listed compliance
  trust_center:
    url: https://www.cloudnuro.ai/security
frameworks:
- CSA-STAR
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: CloudNuro
provenance_date: '2026-11-09'
provider_name: CloudNuro
provider_slug: cloudnuro
slug: cloudnuro-compliance
source_date: '2026-11-09'
source_filename: cloudnuro-compliance.yml
source_heading: Compliance
source_page: https://www.cloudnuro.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: CloudNuro\naid: cloudnuro\nurl: https://www.cloudnuro.ai/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/cloudnuro-trust-center.yml\ntrust_center:\n  url: https://www.cloudnuro.ai/security\nattestations:\n- framework: CSA-STAR\n  type: certification\n  scope: Security, Trust, Assurance and Risk (STAR)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CSA - Security, Trust, Assurance and Risk (STAR)\n- framework: SOC2\n  type: SOC2 Type II certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC2 Type II Certification\n- framework:\
  \ GDPR\n  type: listed compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n"
source_yaml_url: https://artifacts.apis.io/cloudnuro/compliance/cloudnuro-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from CloudNuro's own page on 2026-11-09.
synthetic: false
tags:
- Cloud FinOps
- Compliance
- Cost Optimization
- License Management
- SaaS Management
- Shadow IT
- SSPM
---
