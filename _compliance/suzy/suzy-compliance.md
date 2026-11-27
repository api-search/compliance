---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: information security management system
    text: Our entire information security program is built on the ISO 27001 framework and we are audited annually.
    type: certification
  - framework: SOC2
    issuer: third party audit firm
    period: annual basis
    report_access: unstated
    scope: security controls against AICPA defined standards
    text: Suzy undergoes a SOC 2 Type 2 examination of our security controls against the AICPA defined standards on an annual basis with a third party audit firm to ensure the security of our platform.
    type: Type 2 examination
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: privacy information management system
    text: Our privacy program is built on the ISO 27701 framework.
    type: certification
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: Artificial Intelligence Management System
    text: we are audited annually against ISO 42001 standards.
    type: certification
  trust_center:
    url: https://www.suzy.com/trust-center
frameworks:
- ISO27001
- ISO27701
- ISO42001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Suzy
provenance_date: '2026-11-10'
provider_name: Suzy
provider_slug: suzy
slug: suzy-compliance
source_date: '2026-11-10'
source_filename: suzy-compliance.yml
source_heading: Compliance
source_page: https://www.suzy.com/trust-center
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Suzy\naid: suzy\nurl: https://www.suzy.com/trust-center\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/suzy-trust-center.yml\ntrust_center:\n  url: https://www.suzy.com/trust-center\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: information security management system\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our entire information security program is built on the ISO 27001 framework and we are audited annually.\n- framework: SOC2\n  type: Type 2 examination\n  scope: security controls against AICPA defined standards\n  period: annual basis\n  issuer:\
  \ third party audit firm\n  report_access: unstated\n  text: Suzy undergoes a SOC 2 Type 2 examination of our security controls against the AICPA defined standards on\n    an annual basis with a third party audit firm to ensure the security of our platform.\n- framework: ISO27701\n  type: certification\n  scope: privacy information management system\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our privacy program is built on the ISO 27701 framework.\n- framework: ISO42001\n  type: certification\n  scope: Artificial Intelligence Management System\n  period: null\n  issuer: null\n  report_access: unstated\n  text: we are audited annually against ISO 42001 standards.\n"
source_yaml_url: https://artifacts.apis.io/suzy/compliance/suzy-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Suzy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Consumer Insights
- Market Research
- Surveys
- Audiences
- Artificial Intelligence
---
