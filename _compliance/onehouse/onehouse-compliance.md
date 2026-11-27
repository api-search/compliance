---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Onehouse is SOC 2 Type 1 and 2 certified, so you have the guarantee that the platform has been certified against the industry’s highest standards.
    type: Type 1 and Type 2
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Onehouse is also certified as Payment Card Industry Data Security Standards (PCI DSS) compliant.
    type: null
  trust_center:
    url: https://www.onehouse.ai/product/security
frameworks:
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Onehouse
provenance_date: '2026-11-10'
provider_name: Onehouse
provider_slug: onehouse
slug: onehouse-compliance
source_date: '2026-11-10'
source_filename: onehouse-compliance.yml
source_heading: Compliance
source_page: https://www.onehouse.ai/product/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Onehouse\naid: onehouse\nurl: https://www.onehouse.ai/product/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.onehouse.ai/product/security\nattestations:\n- framework: SOC2\n  type: Type 1 and Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Onehouse is SOC 2 Type 1 and 2 certified, so you have the guarantee that the platform has been certified\n    against the industry’s highest standards.\n- framework: PCI-DSS\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Onehouse is also certified as Payment\
  \ Card Industry Data Security Standards (PCI DSS) compliant.\n"
source_yaml_url: https://artifacts.apis.io/onehouse/compliance/onehouse-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Onehouse's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Developer Tools
- Data Lakehouse
- Data Engineering
- ETL
- Apache Hudi
- Analytics
- Data Infrastructure
---
