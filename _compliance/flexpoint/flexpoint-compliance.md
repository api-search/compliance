---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Card payment processing
    text: Card payments in FlexPoint are processed through a certified Level 1 PCI Compliant Service Provider, the highest certification level under the Payment Card Industry Data Security Standard (PCI DSS).
    type: Level 1 certified Service Provider
  trust_center:
    url: https://www.getflexpoint.com/company/security
frameworks:
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: FlexPoint
provenance_date: '2026-11-09'
provider_name: FlexPoint
provider_slug: flexpoint
slug: flexpoint-compliance
source_date: '2026-11-09'
source_filename: flexpoint-compliance.yml
source_heading: Compliance
source_page: https://www.getflexpoint.com/company/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: FlexPoint\naid: flexpoint\nurl: https://www.getflexpoint.com/company/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.getflexpoint.com/company/security\nattestations:\n- framework: PCI-DSS\n  type: Level 1 certified Service Provider\n  scope: Card payment processing\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Card payments in FlexPoint are processed through a certified Level 1 PCI Compliant Service Provider, the\n    highest certification level under the Payment Card Industry Data Security Standard (PCI DSS).\n"
source_yaml_url: https://artifacts.apis.io/flexpoint/compliance/flexpoint-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from FlexPoint's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Billing
- Accounts Receivable
- MSP
- Invoicing
- ACH
- Reconciliation
- AI Agents
---
