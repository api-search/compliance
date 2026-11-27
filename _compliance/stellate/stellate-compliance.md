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
    text: Stellate continuously monitors and reports primarily using System and Organization Controls (SOC) 2 Type 1 I and 2 II .
    type: Type 1 and Type 2
  trust_center:
    url: https://stellate.co/trust
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Stellate
provenance_date: '2026-11-10'
provider_name: Stellate
provider_slug: stellate
slug: stellate-compliance
source_date: '2026-11-10'
source_filename: stellate-compliance.yml
source_heading: Compliance
source_page: https://stellate.co/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Stellate\naid: stellate\nurl: https://stellate.co/trust\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/stellate-trust-center.yml\ntrust_center:\n  url: https://stellate.co/trust\nattestations:\n- framework: SOC2\n  type: Type 1 and Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Stellate continuously monitors and reports primarily using System and Organization Controls (SOC) 2 Type\n    1 I and 2 II .\n"
source_yaml_url: https://artifacts.apis.io/stellate/compliance/stellate-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Stellate's own page on 2026-11-10.
synthetic: false
tags:
- GraphQL
- CDN
- Edge Caching
- API Management
- Rate Limiting
- GraphQL Security
- Developer Tools
---
