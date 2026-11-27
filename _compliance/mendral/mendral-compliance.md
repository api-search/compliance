---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: MJD Advisors, LLC
    period: null
    report_access: nda
    scope: Security, Availability, Confidentiality
    text: Mendral has completed its SOC 2 Type II examination. The report is available to customers and prospects under NDA upon request through our Trust Center .
    type: Type II examination
  trust_center:
    url: https://mendral.com/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Mendral
provenance_date: '2026-11-10'
provider_name: Mendral
provider_slug: mendral
slug: mendral-compliance
source_date: '2026-11-10'
source_filename: mendral-compliance.yml
source_heading: Compliance
source_page: https://mendral.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Mendral\naid: mendral\nurl: https://mendral.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://mendral.com/security\nattestations:\n- framework: SOC2\n  type: Type II examination\n  scope: Security, Availability, Confidentiality\n  period: null\n  issuer: MJD Advisors, LLC\n  report_access: nda\n  text: Mendral has completed its SOC 2 Type II examination. The report is available to customers and prospects\n    under NDA upon request through our Trust Center .\n"
source_yaml_url: https://artifacts.apis.io/mendral/compliance/mendral-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Mendral's own page on 2026-11-10.
synthetic: false
tags:
- Company
- DevOps
- CI/CD
- Security
- Artificial Intelligence
- Platform Engineering
- Automation
- Developer Tools
---
