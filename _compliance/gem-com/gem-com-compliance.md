---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Gem services
    text: we have developed Gem to operate within the requirements of the General Data Protection Regulation (GDPR)
    type: stated compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Gem platform vulnerability scanning
    text: We are performing regular vulnerability scans at both the network and application level to ensure our compliance with both WASC (Web Application Security Consortium) and OWASP (Open Web Application Security Project) standards.
    type: stated compliance with WASC and OWASP standards
  trust_center:
    url: https://www.gem.com/compliance/security
frameworks:
- GDPR
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Gem
provenance_date: '2026-11-09'
provider_name: Gem
provider_slug: gem-com
slug: gem-com-compliance
source_date: '2026-11-09'
source_filename: gem-com-compliance.yml
source_heading: Compliance
source_page: https://www.gem.com/compliance/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Gem\naid: gem-com\nurl: https://www.gem.com/compliance/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/gem-com-trust-center.yml\ntrust_center:\n  url: https://www.gem.com/compliance/security\nattestations:\n- framework: GDPR\n  type: stated compliance\n  scope: Gem services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: we have developed Gem to operate within the requirements of the General Data Protection Regulation (GDPR)\n- framework: other\n  type: stated compliance with WASC and OWASP standards\n  scope: Gem platform vulnerability scanning\n  period: null\n  issuer:\
  \ null\n  report_access: unstated\n  text: We are performing regular vulnerability scans at both the network and application level to ensure our compliance\n    with both WASC (Web Application Security Consortium) and OWASP (Open Web Application Security Project) standards.\n"
source_yaml_url: https://artifacts.apis.io/gem-com/compliance/gem-com-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Gem's own page on 2026-11-09.
synthetic: false
tags:
- Recruiting CRM
- Applicant Tracking
- Sourcing
- Talent Marketing
- AI Agents
- Human Resources
- Recruiting
---
