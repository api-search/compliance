---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Freed platform
    text: Our systems exceed HIPAA and HItech requirements and are SOC 2 Type 2 certified.
    type: compliance claim
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Freed systems
    text: Our systems exceed HIPAA and HItech requirements and are SOC 2 Type 2 certified.
    type: Type 2 certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Freed platform
    text: Yes, Freed is HIPAA-compliant, SOC2 Type 1 & 2 certified, and HITECH-compliant.
    type: Type 1 & 2 certification
  trust_center:
    url: https://www.getfreed.ai/security
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Freed
provenance_date: '2026-11-09'
provider_name: Freed
provider_slug: freed-ai
slug: freed-ai-compliance
source_date: '2026-11-09'
source_filename: freed-ai-compliance.yml
source_heading: Compliance
source_page: https://www.getfreed.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Freed\naid: freed-ai\nurl: https://www.getfreed.ai/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/freed-ai-trust-center.yml\ntrust_center:\n  url: https://www.getfreed.ai/security\nattestations:\n- framework: HIPAA\n  type: compliance claim\n  scope: Freed platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our systems exceed HIPAA and HItech requirements and are SOC 2 Type 2 certified.\n- framework: SOC2\n  type: Type 2 certification\n  scope: Freed systems\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our systems exceed HIPAA and HItech requirements\
  \ and are SOC 2 Type 2 certified.\n- framework: SOC2\n  type: Type 1 & 2 certification\n  scope: Freed platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Yes, Freed is HIPAA-compliant, SOC2 Type 1 & 2 certified, and HITECH-compliant.\n"
source_yaml_url: https://artifacts.apis.io/freed-ai/compliance/freed-ai-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Freed's own page on 2026-11-09.
synthetic: false
tags:
- AI Scribe
- Medical Scribe
- Clinical Documentation
- Ambient Clinical Intelligence
- Healthcare AI
- SOAP Notes
- EHR Integration
- ICD-10 Coding
- CPT Coding
- HIPAA
- SOC 2
- Chrome Extension
- Clinician Productivity
- Consumer SaaS
---
