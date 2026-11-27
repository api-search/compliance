---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: external auditors
    period: null
    report_access: on_request
    scope: Valence SaaS mesh security platform
    text: Valence completed a SOC 2 Type II attestation which was performed by external auditors and periodically assessed to ensure ongoing compliance.
    type: SOC 2 Type II attestation
  trust_center:
    url: https://www.valencesecurity.com/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Valence Security
provenance_date: '2026-11-10'
provider_name: Valence Security
provider_slug: valence-security
slug: valence-security-compliance
source_date: '2026-11-10'
source_filename: valence-security-compliance.yml
source_heading: Compliance
source_page: https://www.valencesecurity.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Valence Security\naid: valence-security\nurl: https://www.valencesecurity.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/valence-security-trust-center.yml\ntrust_center:\n  url: https://www.valencesecurity.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II attestation\n  scope: Valence SaaS mesh security platform\n  period: null\n  issuer: external auditors\n  report_access: on_request\n  text: Valence completed a SOC 2 Type II attestation which was performed by external auditors and periodically\n    assessed to ensure ongoing compliance.\n"
source_yaml_url: https://artifacts.apis.io/valence-security/compliance/valence-security-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Valence Security's own page on 2026-11-10.
synthetic: false
tags:
- SaaS Security
- SSPM
- AI Security
- Identity Security
- ITDR
- Posture Management
- Risk Remediation
---
