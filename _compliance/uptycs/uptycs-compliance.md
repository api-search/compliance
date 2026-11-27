---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Uptycs service
    text: Uptycs maintains active SOC 2 Type II compliance.
    type: Type II
  trust_center:
    url: https://www.uptycs.com/about/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Uptycs
provenance_date: '2026-11-10'
provider_name: Uptycs
provider_slug: uptycs
slug: uptycs-compliance
source_date: '2026-11-10'
source_filename: uptycs-compliance.yml
source_heading: Compliance
source_page: https://www.uptycs.com/about/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Uptycs\naid: uptycs\nurl: https://www.uptycs.com/about/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.uptycs.com/about/security\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: Uptycs service\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Uptycs maintains active SOC 2 Type II compliance.\n"
source_yaml_url: https://artifacts.apis.io/uptycs/compliance/uptycs-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Uptycs's own page on 2026-11-10.
synthetic: false
tags:
- Security
- Cybersecurity
- CNAPP
- XDR
- Cloud Security
- Endpoint Security
- Kubernetes Security
- osquery
- Threat Detection
- Compliance
---
