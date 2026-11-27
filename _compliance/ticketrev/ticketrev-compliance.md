---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: platform security, confidentiality, integrity, availability
    text: Our security measures align with SOC2 Type II standards
    type: Type II
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: cardholder data
    text: we rigorously adhere to the Payment Card Industry Data Security Standard (PCI DSS) to secure cardholder data
    type: null
  trust_center:
    url: https://www.ticketrev.com/security-and-compliance-commitments
frameworks:
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: TicketRev
provenance_date: '2026-11-10'
provider_name: TicketRev
provider_slug: ticketrev
slug: ticketrev-compliance
source_date: '2026-11-10'
source_filename: ticketrev-compliance.yml
source_heading: Compliance
source_page: https://www.ticketrev.com/security-and-compliance-commitments
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: TicketRev\naid: ticketrev\nurl: https://www.ticketrev.com/security-and-compliance-commitments\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.ticketrev.com/security-and-compliance-commitments\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: platform security, confidentiality, integrity, availability\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our security measures align with SOC2 Type II standards\n- framework: PCI-DSS\n  type: null\n  scope: cardholder data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: we rigorously adhere to the Payment\
  \ Card Industry Data Security Standard (PCI DSS) to secure cardholder\n    data\n"
source_yaml_url: https://artifacts.apis.io/ticketrev/compliance/ticketrev-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from TicketRev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Ticketing
- Sports
- Entertainment
- Marketplace
- Event
- Payments
---
