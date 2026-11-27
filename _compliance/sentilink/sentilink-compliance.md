---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 2 compliant
    type: Type 2
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI compliant
    type: compliance
  trust_center:
    url: https://www.sentilink.com/security
frameworks:
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: SentiLink
provenance_date: '2026-11-10'
provider_name: SentiLink
provider_slug: sentilink
slug: sentilink-compliance
source_date: '2026-11-10'
source_filename: sentilink-compliance.yml
source_heading: Compliance
source_page: https://www.sentilink.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: SentiLink\naid: sentilink\nurl: https://www.sentilink.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/sentilink-trust-center.yml\ntrust_center:\n  url: https://www.sentilink.com/security\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 compliant\n- framework: PCI-DSS\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI compliant\n"
source_yaml_url: https://artifacts.apis.io/sentilink/compliance/sentilink-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from SentiLink's own page on 2026-11-10.
synthetic: false
tags:
- Fraud Prevention
- Identity Verification
- Synthetic Identity
- Account Takeover
- First-Party Fraud
- Financial Services
- Risk Scoring
- Fintech
- KYC
- AML
---
