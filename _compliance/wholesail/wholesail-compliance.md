---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Platform
    text: Platform SOC 2 Certified We undergo independent audits to verify adherence to industry-leading security protocols.
    type: independent audit
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Wholesail card data handling
    text: Wholesail meets Payment Card Industry Data Security Standard (PCI-DSS) requirements to protect card data.
    type: compliance
  trust_center:
    url: https://www.wholesail.ai/security/
frameworks:
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Wholesail
provenance_date: '2026-11-10'
provider_name: Wholesail
provider_slug: wholesail
slug: wholesail-compliance
source_date: '2026-11-10'
source_filename: wholesail-compliance.yml
source_heading: Compliance
source_page: https://www.wholesail.ai/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Wholesail\naid: wholesail\nurl: https://www.wholesail.ai/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.wholesail.ai/security/\nattestations:\n- framework: SOC2\n  type: independent audit\n  scope: Platform\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Platform SOC 2 Certified We undergo independent audits to verify adherence to industry-leading security\n    protocols.\n- framework: PCI-DSS\n  type: compliance\n  scope: Wholesail card data handling\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Wholesail meets Payment Card Industry Data Security\
  \ Standard (PCI-DSS) requirements to protect card data.\n"
source_yaml_url: https://artifacts.apis.io/wholesail/compliance/wholesail-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Wholesail's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Accounts Receivable
- B2B
- ACH
- Wholesale
- Collection
---
