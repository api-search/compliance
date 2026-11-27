---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: OAuth app security controls
    text: Compliant CASA Tier 2 Google Cloud App Security Assessment validating OAuth app security controls.
    type: Google Cloud App Security Assessment (CASA Tier 2)
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: EU data subject rights, DPAs, and sub-processor transparency
    text: Compliant GDPR EU data subject rights, DPAs, and sub-processor transparency.
    type: Compliance status
  - framework: other
    issuer: UK Information Commissioner's Office
    period: null
    report_access: unstated
    scope: Registered as a data controller
    text: Compliant ICO Registered Registered with the UK Information Commissioner's Office as a data controller.
    type: UK ICO registration
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: OAuth app security controls
    source: https://www.supafax.com/security
    text: CASA Tier 2 Google Cloud App Security Assessment validating OAuth app security controls.
    type: CASA Tier 2 security assessment
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: EU data subject rights, DPAs, and sub-processor transparency
    source: https://www.supafax.com/security
    text: GDPR EU data subject rights, DPAs, and sub-processor transparency.
    type: compliance
  trust_center:
    url: https://www.supafax.com/security
frameworks:
- GDPR
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Supafax
provenance_date: '2026-11-10'
provider_name: Supafax
provider_slug: supafax
slug: supafax-compliance
source_date: '2026-11-10'
source_filename: supafax-compliance.yml
source_heading: Compliance
source_page: https://www.supafax.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Supafax\naid: supafax\nurl: https://www.supafax.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/supafax-trust-center.yml\n  sources:\n  - https://www.supafax.com/security\ntrust_center:\n  url: https://www.supafax.com/security\nattestations:\n- framework: other\n  type: Google Cloud App Security Assessment (CASA Tier 2)\n  scope: OAuth app security controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliant CASA Tier 2 Google Cloud App Security Assessment validating OAuth app security controls.\n- framework: GDPR\n  type: Compliance status\n  scope: EU data subject\
  \ rights, DPAs, and sub-processor transparency\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliant GDPR EU data subject rights, DPAs, and sub-processor transparency.\n- framework: other\n  type: UK ICO registration\n  scope: Registered as a data controller\n  period: null\n  issuer: UK Information Commissioner's Office\n  report_access: unstated\n  text: Compliant ICO Registered Registered with the UK Information Commissioner's Office as a data controller.\n- framework: other\n  type: CASA Tier 2 security assessment\n  scope: OAuth app security controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CASA Tier 2 Google Cloud App Security Assessment validating OAuth app security controls.\n  source: https://www.supafax.com/security\n- framework: GDPR\n  type: compliance\n  scope: EU data subject rights, DPAs, and sub-processor transparency\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR EU data subject rights, DPAs,\
  \ and sub-processor transparency.\n  source: https://www.supafax.com/security\n"
source_yaml_url: https://artifacts.apis.io/supafax/compliance/supafax-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Supafax's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Email
- Calendar
- AI Assistant
- AI Agents
- Email Automation
- Productivity
- Y Combinator
---
