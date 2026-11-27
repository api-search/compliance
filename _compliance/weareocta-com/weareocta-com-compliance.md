---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: security, availability, and confidentiality controls
    text: 'SOC 2 Type II: independently audited controls for security, availability, and confidentiality'
    type: SOC 2 Type II
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: information security management system
    text: 'ISO 27001: certified information security management system'
    type: certified information security management system
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: EU personal data
    text: 'GDPR: compliant data processing for EU personal data'
    type: compliant data processing
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: UAE market personal data
    text: 'UAE PDPL (Personal Data Protection Law): compliant data handling for the UAE market'
    type: compliant data handling (UAE PDPL)
  trust_center:
    url: https://weareocta.com/security
frameworks:
- GDPR
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Octa
provenance_date: '2026-11-10'
provider_name: Octa
provider_slug: weareocta-com
slug: weareocta-com-compliance
source_date: '2026-11-10'
source_filename: weareocta-com-compliance.yml
source_heading: Compliance
source_page: https://weareocta.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Octa\naid: weareocta-com\nurl: https://weareocta.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://weareocta.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: security, availability, and confidentiality controls\n  period: null\n  issuer: null\n  report_access: on_request\n  text: 'SOC 2 Type II: independently audited controls for security, availability, and confidentiality'\n- framework: ISO27001\n  type: certified information security management system\n  scope: information security management system\n  period: null\n  issuer: null\n  report_access: on_request\n\
  \  text: 'ISO 27001: certified information security management system'\n- framework: GDPR\n  type: compliant data processing\n  scope: EU personal data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'GDPR: compliant data processing for EU personal data'\n- framework: other\n  type: compliant data handling (UAE PDPL)\n  scope: UAE market personal data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'UAE PDPL (Personal Data Protection Law): compliant data handling for the UAE market'\n"
source_yaml_url: https://artifacts.apis.io/weareocta-com/compliance/weareocta-com-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Octa's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Accounting
- Software-as-a-Service
- Workforce
---
