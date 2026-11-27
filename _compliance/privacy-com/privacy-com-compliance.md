---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Privacy is PCI-DSS compliant.
    type: compliance claim
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We also comply with the international ISO 27001 standard
    type: compliance claim
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: are SOC1 and SOC2 Type 2 certified.
    type: certification claim
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: are SOC1 and SOC2 Type 2 certified.
    type: certification claim
  trust_center:
    url: https://www.privacy.com/security
frameworks:
- ISO27001
- PCI-DSS
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Privacy.com
provenance_date: '2026-11-10'
provider_name: Privacy.com
provider_slug: privacy-com
slug: privacy-com-compliance
source_date: '2026-11-10'
source_filename: privacy-com-compliance.yml
source_heading: Compliance
source_page: https://www.privacy.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Privacy.com\naid: privacy-com\nurl: https://www.privacy.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/privacy-com-trust-center.yml\ntrust_center:\n  url: https://www.privacy.com/security\nattestations:\n- framework: PCI-DSS\n  type: compliance claim\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Privacy is PCI-DSS compliant.\n- framework: ISO27001\n  type: compliance claim\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We also comply with the international ISO 27001 standard\n- framework: SOC1\n  type: certification\
  \ claim\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: are SOC1 and SOC2 Type 2 certified.\n- framework: SOC2\n  type: certification claim\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: are SOC1 and SOC2 Type 2 certified.\n"
source_yaml_url: https://artifacts.apis.io/privacy-com/compliance/privacy-com-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Privacy.com's own page on 2026-11-10.
synthetic: false
tags:
- Security
- Public APIs
---
