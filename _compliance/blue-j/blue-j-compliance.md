---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent auditor
    period: annual
    report_access: nda
    scope: Blue J platform controls
    text: We work with an independent auditor to maintain a SOC 2 Type 2 report, on an annual basis, which objectively certifies our controls
    type: SOC 2 Type 2 report
  trust_center:
    url: https://www.bluej.com/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Blue J
provenance_date: '2026-11-09'
provider_name: Blue J
provider_slug: blue-j
slug: blue-j-compliance
source_date: '2026-11-09'
source_filename: blue-j-compliance.yml
source_heading: Compliance
source_page: https://www.bluej.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Blue J\naid: blue-j\nurl: https://www.bluej.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/blue-j-trust-center.yml\ntrust_center:\n  url: https://www.bluej.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: Blue J platform controls\n  period: annual\n  issuer: independent auditor\n  report_access: nda\n  text: We work with an independent auditor to maintain a SOC 2 Type 2 report, on an annual basis, which objectively\n    certifies our controls\n"
source_yaml_url: https://artifacts.apis.io/blue-j/compliance/blue-j-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Blue J's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Tax
- Legal
- Research
- Compliance
- Software-as-a-Service
- Professional Services
---
