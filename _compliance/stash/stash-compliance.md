---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: external third party
    period: null
    report_access: unstated
    scope: Stash security
    text: Stash has been audited by an external third party to validate compliance with the Payment Card Industry Data Security Standard (PCI DSS).
    type: external audit
  trust_center:
    url: https://www.stash.com/security
frameworks:
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Stash
provenance_date: '2026-11-10'
provider_name: Stash
provider_slug: stash
slug: stash-compliance
source_date: '2026-11-10'
source_filename: stash-compliance.yml
source_heading: Compliance
source_page: https://www.stash.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Stash\naid: stash\nurl: https://www.stash.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/stash-trust-center.yml\ntrust_center:\n  url: https://www.stash.com/security\nattestations:\n- framework: PCI-DSS\n  type: external audit\n  scope: Stash security\n  period: null\n  issuer: external third party\n  report_access: unstated\n  text: Stash has been audited by an external third party to validate compliance with the Payment Card Industry\n    Data Security Standard (PCI DSS).\n"
source_yaml_url: https://artifacts.apis.io/stash/compliance/stash-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Stash's own page on 2026-11-10.
synthetic: false
tags:
- Fintech
- Investing
- Banking
- Fractional Shares
- Portfolio Management
- Financial Education
- Robo-Advisor
- Stock-Back
- Custodial Accounts
- IRA
---
