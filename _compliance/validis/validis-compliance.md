---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Validis Security Compliance program
    text: We are ISO 27001 and SOC2 Type 2 compliant.
    type: SOC2 Type 2
  - framework: ISO27001
    issuer: null
    period: annually
    report_access: unstated
    scope: Validis Security Compliance program
    text: We are audited annually for both.
    type: null
  trust_center:
    url: https://www.validis.com/privacy-security/
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Validis
provenance_date: '2026-11-10'
provider_name: Validis
provider_slug: validis
slug: validis-compliance
source_date: '2026-11-10'
source_filename: validis-compliance.yml
source_heading: Compliance
source_page: https://www.validis.com/privacy-security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Validis\naid: validis\nurl: https://www.validis.com/privacy-security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.validis.com/privacy-security/\nattestations:\n- framework: SOC2\n  type: SOC2 Type 2\n  scope: Validis Security Compliance program\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are ISO 27001 and SOC2 Type 2 compliant.\n- framework: ISO27001\n  type: null\n  scope: Validis Security Compliance program\n  period: annually\n  issuer: null\n  report_access: unstated\n  text: We are audited annually for both.\n"
source_yaml_url: https://artifacts.apis.io/validis/compliance/validis-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Validis's own page on 2026-11-10.
synthetic: false
tags:
- Audit
- Commercial Lending
- Specialist Lending
- M&A Due Diligence
- Financial Data Infrastructure
---
