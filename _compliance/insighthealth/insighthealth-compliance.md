---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: systems and processes meeting security, availability, privacy and confidentiality standards
    text: We're SOC 2 Type 2 Certified, which assures our systems and processes meet rigorous security, availability, privacy and confidentiality standards.
    type: Type 2 attestation
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: data storage and processing protocols for data captured and shared through the platform
    text: We maintain HIPAA-compliant data storage and processing protocols for all data captured and shared through our platform
    type: compliance statement
  trust_center:
    url: https://www.insighthealth.ai/trust-safety
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Insight Health
provenance_date: '2026-11-09'
provider_name: Insight Health
provider_slug: insighthealth
slug: insighthealth-compliance
source_date: '2026-11-09'
source_filename: insighthealth-compliance.yml
source_heading: Compliance
source_page: https://www.insighthealth.ai/trust-safety
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Insight Health\naid: insighthealth\nurl: https://www.insighthealth.ai/trust-safety\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.insighthealth.ai/trust-safety\nattestations:\n- framework: SOC2\n  type: Type 2 attestation\n  scope: systems and processes meeting security, availability, privacy and confidentiality standards\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We're SOC 2 Type 2 Certified, which assures our systems and processes meet rigorous security, availability,\n    privacy and confidentiality standards.\n- framework: HIPAA\n  type: compliance statement\n  scope:\
  \ data storage and processing protocols for data captured and shared through the platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We maintain HIPAA-compliant data storage and processing protocols for all data captured and shared through\n    our platform\n"
source_yaml_url: https://artifacts.apis.io/insighthealth/compliance/insighthealth-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Insight Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Artificial Intelligence
- Clinical Documentation
- Voice Agents
- Electronic Health Records
- HIPAA
- FHIR
- Medical
- Patient Engagement
---
