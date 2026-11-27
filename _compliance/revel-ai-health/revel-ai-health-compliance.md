---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: Security, Availability, and Confidentiality Trust Service Criteria
    text: SOC 2 Type II compliant. Our SOC 2 Type II audit (Security, Availability, and Confidentiality Trust Service Criteria) demonstrates that our controls are not only designed effectively, but operate consistently over time.
    type: Type II audit
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: administrative, physical, and technical safeguards for ePHI
    text: HIPAA compliant. RevelAi Health maintains administrative, physical, and technical safeguards in alignment with the HIPAA Security Rule for protecting electronic PHI (ePHI).
    type: compliance with HIPAA Security Rule
  trust_center:
    url: https://www.revelaihealth.com/security
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Revel Ai Health
provenance_date: '2026-11-10'
provider_name: Revel Ai Health
provider_slug: revel-ai-health
slug: revel-ai-health-compliance
source_date: '2026-11-10'
source_filename: revel-ai-health-compliance.yml
source_heading: Compliance
source_page: https://www.revelaihealth.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Revel Ai Health\naid: revel-ai-health\nurl: https://www.revelaihealth.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/revel-ai-health-trust-center.yml\ntrust_center:\n  url: https://www.revelaihealth.com/security\nattestations:\n- framework: SOC2\n  type: Type II audit\n  scope: Security, Availability, and Confidentiality Trust Service Criteria\n  period: null\n  issuer: null\n  report_access: nda\n  text: SOC 2 Type II compliant. Our SOC 2 Type II audit (Security, Availability, and Confidentiality Trust Service\n    Criteria) demonstrates that our controls are not only designed effectively,\
  \ but operate consistently over time.\n- framework: HIPAA\n  type: compliance with HIPAA Security Rule\n  scope: administrative, physical, and technical safeguards for ePHI\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA compliant. RevelAi Health maintains administrative, physical, and technical safeguards in alignment\n    with the HIPAA Security Rule for protecting electronic PHI (ePHI).\n"
source_yaml_url: https://artifacts.apis.io/revel-ai-health/compliance/revel-ai-health-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Revel Ai Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Artificial Intelligence
- Conversational AI
- Value-Based Care
- Orthopedics
- Digital Health
---
