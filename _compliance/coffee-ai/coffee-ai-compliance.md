---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Armanino
    period: null
    report_access: on_request
    scope: null
    text: SOC 2, Type 2 Fully compliant. Audited annually by Armanino. Report available upon request.
    type: SOC 2 Type 2 audit
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: EU personal data
    text: Coffee processes and protects EU personal data in accordance with the General Data Protection Regulation (GDPR).
    type: GDPR compliance
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: healthcare customer data
    text: We sign BAAs with healthcare and health-tech customers and apply HIPAA safeguards to that data.
    type: HIPAA readiness with BAAs
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Google Workspace integration
    text: Certified to Tier 2 Cloud Application Security Assessment standards for enterprise-grade security.
    type: CASA Tier 2 verification (Google Workspace)
  trust_center:
    url: https://www.coffee.ai/security
frameworks:
- GDPR
- HIPAA
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Coffee
provenance_date: '2026-11-09'
provider_name: Coffee
provider_slug: coffee-ai
slug: coffee-ai-compliance
source_date: '2026-11-09'
source_filename: coffee-ai-compliance.yml
source_heading: Compliance
source_page: https://www.coffee.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Coffee\naid: coffee-ai\nurl: https://www.coffee.ai/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.coffee.ai/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 audit\n  scope: null\n  period: null\n  issuer: Armanino\n  report_access: on_request\n  text: SOC 2, Type 2 Fully compliant. Audited annually by Armanino. Report available upon request.\n- framework: GDPR\n  type: GDPR compliance\n  scope: EU personal data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Coffee processes and protects EU personal data in accordance with the General Data Protection\
  \ Regulation\n    (GDPR).\n- framework: HIPAA\n  type: HIPAA readiness with BAAs\n  scope: healthcare customer data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We sign BAAs with healthcare and health-tech customers and apply HIPAA safeguards to that data.\n- framework: other\n  type: CASA Tier 2 verification (Google Workspace)\n  scope: Google Workspace integration\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Certified to Tier 2 Cloud Application Security Assessment standards for enterprise-grade security.\n"
source_yaml_url: https://artifacts.apis.io/coffee-ai/compliance/coffee-ai-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Coffee's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- CRM
- Sales
- Automation
---
