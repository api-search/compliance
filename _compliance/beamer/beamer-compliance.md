---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: information system security, confidentiality, and privacy policies
    text: Beamer is SOC 2 Type II certified as a guarantee of our information system security, confidentiality, and privacy policies.
    type: SOC 2 Type II certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Beamer is GDPR Compliant and has the Data Processing Agreements in place.
    type: GDPR compliance with Data Processing Agreements
  trust_center:
    url: https://www.getbeamer.com/security
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Beamer
provenance_date: '2026-11-09'
provider_name: Beamer
provider_slug: beamer
slug: beamer-compliance
source_date: '2026-11-09'
source_filename: beamer-compliance.yml
source_heading: Compliance
source_page: https://www.getbeamer.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Beamer\naid: beamer\nurl: https://www.getbeamer.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/beamer-trust-center.yml\ntrust_center:\n  url: https://www.getbeamer.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II certification\n  scope: information system security, confidentiality, and privacy policies\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Beamer is SOC 2 Type II certified as a guarantee of our information system security, confidentiality, and\n    privacy policies.\n- framework: GDPR\n  type: GDPR compliance with Data Processing Agreements\n\
  \  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Beamer is GDPR Compliant and has the Data Processing Agreements in place.\n"
source_yaml_url: https://artifacts.apis.io/beamer/compliance/beamer-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Beamer's own page on 2026-11-09.
synthetic: false
tags:
- Changelog
- Deprecation
- Notification
- Product Updates
- User Engagement
- Webhook
- NPS
- Feedback
---
