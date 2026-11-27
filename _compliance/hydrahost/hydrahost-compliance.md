---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 2 Type 2 Compliant
    type: Type 2
  trust_center:
    url: https://security.hydrahost.com/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Hydrahost
provenance_date: '2026-11-09'
provider_name: Hydrahost
provider_slug: hydrahost
slug: hydrahost-compliance
source_date: '2026-11-09'
source_filename: hydrahost-compliance.yml
source_heading: Compliance
source_page: https://security.hydrahost.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Hydrahost\naid: hydrahost\nurl: https://security.hydrahost.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/hydrahost-trust-center.yml\ntrust_center:\n  url: https://security.hydrahost.com/\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type 2 Compliant\n"
source_yaml_url: https://artifacts.apis.io/hydrahost/compliance/hydrahost-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Hydrahost's own page on 2026-11-09.
synthetic: false
tags:
- Company
- GPU Cloud
- Bare Metal
- Artificial Intelligence
- Machine Learning
- Cloud Infrastructure
- Compute
- Neocloud
---
