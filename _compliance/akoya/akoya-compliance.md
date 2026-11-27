---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Akoya platform
    text: Akoya is SOC 2 Type 2 certified, which is independently audited annually against the AICPA's Trust Services Criteria.
    type: Type 2
  trust_center:
    url: https://akoya.com/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Akoya
provenance_date: '2026-11-09'
provider_name: Akoya
provider_slug: akoya
slug: akoya-compliance
source_date: '2026-11-09'
source_filename: akoya-compliance.yml
source_heading: Compliance
source_page: https://akoya.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Akoya\naid: akoya\nurl: https://akoya.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://akoya.com/security\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: Akoya platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Akoya is SOC 2 Type 2 certified, which is independently audited annually against the AICPA's Trust Services\n    Criteria.\n"
source_yaml_url: https://artifacts.apis.io/akoya/compliance/akoya-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Akoya's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Open Banking
- Open Finance
- Aggregator
- Data Access Network
- Tokenized
- Consumer-Permissioned
- FDX
- Account Aggregation
- United States
- Data Aggregation
---
