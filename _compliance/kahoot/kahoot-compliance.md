---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Kahoot! platform
    text: In addition, Kahoot! is ISO 27001 certified, the recognized international standard for information security management systems.
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: schools and educators tools
    text: 'designed to support compliance with: the Family Educational Rights and Privacy Act (FERPA), the Children’s Online Privacy and Protection Act (COPPA), the General Data Protection Regulation (GDPR), SOC 2, ISO27001'
    type: compliance support
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Kahoot! (organisation-level, as stated)
    source: https://trust.kahoot.com/
    text: Kahoot! is ISO 27001 certified, the recognized international standard for information security management systems.
    type: certification
  trust_center:
    url: https://trust.kahoot.com
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Kahoot!
provenance_date: '2026-11-09'
provider_name: Kahoot!
provider_slug: kahoot
slug: kahoot-compliance
source_date: '2026-11-09'
source_filename: kahoot-compliance.yml
source_heading: Compliance
source_page: https://trust.kahoot.com
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Kahoot!\naid: kahoot\nurl: https://trust.kahoot.com\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/kahoot-trust-center.yml\n  sources:\n  - https://trust.kahoot.com\n  - https://trust.kahoot.com/\ntrust_center:\n  url: https://trust.kahoot.com\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Kahoot! platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: In addition, Kahoot! is ISO 27001 certified, the recognized international standard for information security\n    management systems.\n- framework: SOC2\n  type: compliance support\n  scope: schools and educators\
  \ tools\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'designed to support compliance with: the Family Educational Rights and Privacy Act (FERPA), the Children’s\n    Online Privacy and Protection Act (COPPA), the General Data Protection Regulation (GDPR), SOC 2, ISO27001'\n- framework: ISO27001\n  type: certification\n  scope: Kahoot! (organisation-level, as stated)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Kahoot! is ISO 27001 certified, the recognized international standard for information security management\n    systems.\n  source: https://trust.kahoot.com/\n"
source_yaml_url: https://artifacts.apis.io/kahoot/compliance/kahoot-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Kahoot!'s own page on 2026-11-09.
synthetic: false
tags:
- Game-Based Learning
- Education
- Quiz
- Engagement
- Enterprise Learning
- Reporting
- OAuth
- Authentication
---
