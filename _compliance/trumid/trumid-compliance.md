---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: In addition to its own GDPR compliance procedures
    type: self-stated GDPR compliance procedures
  - framework: other
    issuer: Securities and Exchange Commission (SEC)
    period: null
    report_access: unstated
    scope: 'US: Trumid Financial, LLC'
    text: Trumid Financial, LLC is a Securities and Exchange Commission (SEC) registered broker dealer
    type: SEC broker-dealer registration
  trust_center:
    url: https://www.trumid.com/legal-and-regulatory/
frameworks:
- GDPR
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Trumid
provenance_date: '2026-11-10'
provider_name: Trumid
provider_slug: trumid
slug: trumid-compliance
source_date: '2026-11-10'
source_filename: trumid-compliance.yml
source_heading: Compliance
source_page: https://www.trumid.com/legal-and-regulatory/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Trumid\naid: trumid\nurl: https://www.trumid.com/legal-and-regulatory/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.trumid.com/legal-and-regulatory/\nattestations:\n- framework: GDPR\n  type: self-stated GDPR compliance procedures\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: In addition to its own GDPR compliance procedures\n- framework: other\n  type: SEC broker-dealer registration\n  scope: 'US: Trumid Financial, LLC'\n  period: null\n  issuer: Securities and Exchange Commission (SEC)\n  report_access: unstated\n  text: Trumid Financial, LLC is a Securities\
  \ and Exchange Commission (SEC) registered broker dealer\n"
source_yaml_url: https://artifacts.apis.io/trumid/compliance/trumid-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Trumid's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Capital Markets
- Fixed Income
- Bond Trading
- Electronic Trading
- Market Data
- Analytics
- FIX Protocol
- Broker-Dealer
---
