---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We are undergoing an independent SOC 2 Type 1 audit and continuously monitor our security controls through Vanta.
    type: Type 1 audit (in progress)
  trust_center:
    url: https://trust.zeabur.com/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Zeabur
provenance_date: '2026-11-10'
provider_name: Zeabur
provider_slug: zeabur
slug: zeabur-compliance
source_date: '2026-11-10'
source_filename: zeabur-compliance.yml
source_heading: Compliance
source_page: https://trust.zeabur.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Zeabur\naid: zeabur\nurl: https://trust.zeabur.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/zeabur-trust-center.yml\ntrust_center:\n  url: https://trust.zeabur.com/\nattestations:\n- framework: SOC2\n  type: Type 1 audit (in progress)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are undergoing an independent SOC 2 Type 1 audit and continuously monitor our security controls through\n    Vanta.\n"
source_yaml_url: https://artifacts.apis.io/zeabur/compliance/zeabur-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Zeabur's own page on 2026-11-10.
synthetic: false
tags:
- Platform-as-a-Service
- Deployment
- Cloud
- DevOps
- GraphQL
---
