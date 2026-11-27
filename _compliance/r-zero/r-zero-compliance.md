---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: public
    scope: null
    text: R-Zero is independently audited under SOC 2 Type II
    type: SOC 2 Type II audit
  - framework: SOC3
    issuer: null
    period: null
    report_access: public
    scope: null
    text: The SOC 3 report is the public-facing summary of that audit, available to immediately share with your security team.
    type: SOC 3 report
  trust_center:
    url: https://rzero.com/security/
frameworks:
- SOC2
- SOC3
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: R-Zero
provenance_date: '2026-11-10'
provider_name: R-Zero
provider_slug: r-zero
slug: r-zero-compliance
source_date: '2026-11-10'
source_filename: r-zero-compliance.yml
source_heading: Compliance
source_page: https://rzero.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: R-Zero\naid: r-zero\nurl: https://rzero.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://rzero.com/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: null\n  period: null\n  issuer: null\n  report_access: public\n  text: R-Zero is independently audited under SOC 2 Type II\n- framework: SOC3\n  type: SOC 3 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: public\n  text: The SOC 3 report is the public-facing summary of that audit, available to immediately share with your security\n    team.\n"
source_yaml_url: https://artifacts.apis.io/r-zero/compliance/r-zero-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from R-Zero's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Smart Buildings
- Occupancy
- Sensors
- IoT
- Indoor Air Quality
- Energy Efficiency
- HVAC
- Analytics
- Commercial Real Estate
- Workplace
---
