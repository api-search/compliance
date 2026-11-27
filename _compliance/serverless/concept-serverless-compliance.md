---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: security trust service criteria
    text: Our SOC 2 Type I report is available, demonstrating that our security controls are properly designed and implemented to meet the security trust service criteria
    type: Type I report
  - framework: SOC2
    issuer: null
    period: over time
    report_access: on_request
    scope: security program controls
    text: Our SOC 2 Type II report is available, demonstrating that our security controls have been operating effectively over time.
    type: Type II report
  trust_center:
    url: https://www.serverless.com/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Serverless
provenance_date: '2026-11-09'
provider_name: Serverless
provider_slug: serverless
slug: concept-serverless-compliance
source_date: '2026-11-09'
source_filename: concept-serverless-compliance.yml
source_heading: Compliance
source_page: https://www.serverless.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Serverless\naid: concept-serverless\nurl: https://www.serverless.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.serverless.com/security\nattestations:\n- framework: SOC2\n  type: Type I report\n  scope: security trust service criteria\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Our SOC 2 Type I report is available, demonstrating that our security controls are properly designed and\n    implemented to meet the security trust service criteria\n- framework: SOC2\n  type: Type II report\n  scope: security program controls\n  period: over time\n  issuer: null\n\
  \  report_access: on_request\n  text: Our SOC 2 Type II report is available, demonstrating that our security controls have been operating effectively\n    over time.\n"
source_yaml_url: https://artifacts.apis.io/serverless/compliance/concept-serverless-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Serverless's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Serverless
- Infrastructure as Code
- Developer Tools
- AWS Lambda
- Deployment
- Cloud
- CLI
---
