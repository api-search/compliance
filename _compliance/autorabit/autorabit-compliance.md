---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: Salesforce security and compliance
    text: backed by a FedRAMP® Moderate ATO
    type: ATO
  trust_center:
    url: https://www.autorabit.com/trust-center/
frameworks:
- FedRAMP
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: AutoRABIT
provenance_date: '2026-11-09'
provider_name: AutoRABIT
provider_slug: autorabit
slug: autorabit-compliance
source_date: '2026-11-09'
source_filename: autorabit-compliance.yml
source_heading: Compliance
source_page: https://www.autorabit.com/trust-center/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: AutoRABIT\naid: autorabit\nurl: https://www.autorabit.com/trust-center/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.autorabit.com/trust-center/\nattestations:\n- framework: FedRAMP\n  type: ATO\n  scope: Salesforce security and compliance\n  period: null\n  issuer: null\n  report_access: unstated\n  text: backed by a FedRAMP® Moderate ATO\n"
source_yaml_url: https://artifacts.apis.io/autorabit/compliance/autorabit-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from AutoRABIT's own page on 2026-11-09.
synthetic: false
tags:
- Salesforce
- DevSecOps
- CI/CD
- Compliance
- Automation
---
