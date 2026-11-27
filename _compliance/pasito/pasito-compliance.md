---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: systems and processes handling protected health information
    text: Our systems and processes meet the rigorous requirements of the Health Insurance Portability and Accountability Act (HIPAA).
    type: compliance alignment statement
  - framework: SOC2
    issuer: Prescient Assurance
    period: null
    report_access: on_request
    scope: controls for security
    text: 'SOC 2 Type II: Independently audited by Prescient Assurance, confirming our controls for security. Request our SOC 2 Report'
    type: Type II audit
  trust_center:
    url: https://pasito.ai/security
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Pasito
provenance_date: '2026-11-10'
provider_name: Pasito
provider_slug: pasito
slug: pasito-compliance
source_date: '2026-11-10'
source_filename: pasito-compliance.yml
source_heading: Compliance
source_page: https://pasito.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Pasito\naid: pasito\nurl: https://pasito.ai/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://pasito.ai/security\nattestations:\n- framework: HIPAA\n  type: compliance alignment statement\n  scope: systems and processes handling protected health information\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our systems and processes meet the rigorous requirements of the Health Insurance Portability and Accountability\n    Act (HIPAA).\n- framework: SOC2\n  type: Type II audit\n  scope: controls for security\n  period: null\n  issuer: Prescient Assurance\n  report_access: on_request\n\
  \  text: 'SOC 2 Type II: Independently audited by Prescient Assurance, confirming our controls for security. Request\n    our SOC 2 Report'\n"
source_yaml_url: https://artifacts.apis.io/pasito/compliance/pasito-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Pasito's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Employee Benefits
- Insurance
- Artificial Intelligence
- Insurtech
- Human Resources
- Health
- AI Agents
---
