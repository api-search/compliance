---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Self undergoes annual audits that produce a SOC 1 Type 2 report, SOC 2 Type 2 report, and PCI DSS Report on Compliance.
    type: Type 2 report
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Self undergoes annual audits that produce a SOC 1 Type 2 report, SOC 2 Type 2 report, and PCI DSS Report on Compliance.
    type: Type 2 report
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Self undergoes annual audits that produce a SOC 1 Type 2 report, SOC 2 Type 2 report, and PCI DSS Report on Compliance.
    type: Report on Compliance
  trust_center:
    url: https://www.self.inc/trust
frameworks:
- PCI-DSS
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Self
provenance_date: '2026-11-10'
provider_name: Self
provider_slug: self
slug: self-compliance
source_date: '2026-11-10'
source_filename: self-compliance.yml
source_heading: Compliance
source_page: https://www.self.inc/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Self\naid: self\nurl: https://www.self.inc/trust\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.self.inc/trust\nattestations:\n- framework: SOC1\n  type: Type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Self undergoes annual audits that produce a SOC 1 Type 2 report, SOC 2 Type 2 report, and PCI DSS Report\n    on Compliance.\n- framework: SOC2\n  type: Type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Self undergoes annual audits that produce a SOC 1 Type 2 report, SOC 2 Type 2 report, and PCI DSS Report\n\
  \    on Compliance.\n- framework: PCI-DSS\n  type: Report on Compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Self undergoes annual audits that produce a SOC 1 Type 2 report, SOC 2 Type 2 report, and PCI DSS Report\n    on Compliance.\n"
source_yaml_url: https://artifacts.apis.io/self/compliance/self-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Self's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Credit Building
- Consumer Finance
- Banking
- Financial Services
- Credit Cards
- Lending
---
