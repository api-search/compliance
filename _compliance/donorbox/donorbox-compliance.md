---
api_specs:
- filename: donorbox-agent-api-openapi.yml
  format: yaml
  label: Donorbox Agent API
  slug: donorbox-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/donorbox/openapi/donorbox-agent-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Donorbox has earned both SOC 2 Type I and SOC 2 Type II certifications
    type: SOC 2 Type I and Type II
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Donorbox is PCI DSS Level 1 compliant, the most stringent level of certification for payment processors.
    type: PCI DSS Level 1
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Our online donation platform complies with the Strong Customer Authentication requirement of PSD2 regulations in Europe.
    type: PSD2 Strong Customer Authentication
  trust_center:
    url: https://donorbox.org/security
frameworks:
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Donorbox
provenance_date: '2026-11-09'
provider_name: Donorbox
provider_slug: donorbox
slug: donorbox-compliance
source_date: '2026-11-09'
source_filename: donorbox-compliance.yml
source_heading: Compliance
source_page: https://donorbox.org/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Donorbox\naid: donorbox\nurl: https://donorbox.org/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/donorbox-trust-center.yml\ntrust_center:\n  url: https://donorbox.org/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type I and Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Donorbox has earned both SOC 2 Type I and SOC 2 Type II certifications\n- framework: PCI-DSS\n  type: PCI DSS Level 1\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Donorbox is PCI DSS Level 1 compliant, the most stringent level of\
  \ certification for payment processors.\n- framework: other\n  type: PSD2 Strong Customer Authentication\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our online donation platform complies with the Strong Customer Authentication requirement of PSD2 regulations\n    in Europe.\n"
source_yaml_url: https://artifacts.apis.io/donorbox/compliance/donorbox-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Donorbox's own page on 2026-11-09.
synthetic: false
tags:
- Non-Profit
- Fundraising
- Donations
- Payments
- Recurring Giving
- Event Ticketing
---
