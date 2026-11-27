---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Pepper PCI-compliant vault for sensitive information
    text: Pepper is fully compliant with the Payment Card Industry Data Security Standard (PCI DSS)
    type: compliance statement
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.usepepper.com/
    text: Compliance SOC 2 Type I 2024
    type: Type I
  trust_center:
    url: https://www.usepepper.com/solutions/security
frameworks:
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Pepper
provenance_date: '2026-11-10'
provider_name: Pepper
provider_slug: pepper
slug: pepper-compliance
source_date: '2026-11-10'
source_filename: pepper-compliance.yml
source_heading: Compliance
source_page: https://www.usepepper.com/solutions/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Pepper\naid: pepper\nurl: https://www.usepepper.com/solutions/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://trust.usepepper.com/\n  - https://www.usepepper.com/solutions/security\ntrust_center:\n  url: https://www.usepepper.com/solutions/security\nattestations:\n- framework: PCI-DSS\n  type: compliance statement\n  scope: Pepper PCI-compliant vault for sensitive information\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Pepper is fully compliant with the Payment Card Industry Data Security Standard (PCI DSS)\n- framework: SOC2\n  type: Type I\n  scope: null\n  period: null\n\
  \  issuer: null\n  report_access: unstated\n  text: Compliance SOC 2 Type I 2024\n  source: https://trust.usepepper.com/\n"
source_yaml_url: https://artifacts.apis.io/pepper/compliance/pepper-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Pepper's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Application
- Food and Beverage
- Distribution
- Wholesale
- Order Management
- Artificial Intelligence
- ERP Integration
---
