---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    text: Operant is SOC 2, Type II Compliant.
    type: SOC 2 Type II
  trust_center:
    url: https://www.operant.ai/company/about
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Operant
provenance_date: '2026-11-10'
provider_name: Operant
provider_slug: operant
slug: operant-compliance
source_date: '2026-11-10'
source_filename: operant-compliance.yml
source_heading: Compliance
source_page: https://www.operant.ai/company/about
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Operant\naid: operant\nurl: https://www.operant.ai/company/about\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/operant-trust-center.yml\ntrust_center:\n  url: https://www.operant.ai/company/about\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: Operant is SOC 2, Type II Compliant.\n"
source_yaml_url: https://artifacts.apis.io/operant/compliance/operant-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Operant's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- API Security
- AI Security
- Runtime Security
- Cloud Security
- Kubernetes
- AI Agents
- CADR
- Detection and Response
---
