---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: EvenUp security and compliance program
    text: EvenUp’s security and compliance program has been independently assessed through a SOC 2 Type 2 examination and a HIPAA compliance assessment.
    type: SOC 2 Type 2 examination
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: EvenUp security and compliance program
    text: Our security program is independently assessed through a SOC 2 Type 2 examination and HIPAA attestation. Relevant reports are available to customers and prospects upon request.
    type: HIPAA compliance assessment / attestation
  trust_center:
    url: https://trust.evenuplaw.com/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: EvenUp
provenance_date: '2026-11-09'
provider_name: EvenUp
provider_slug: evenup
slug: evenup-compliance
source_date: '2026-11-09'
source_filename: evenup-compliance.yml
source_heading: Compliance
source_page: https://trust.evenuplaw.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: EvenUp\naid: evenup\nurl: https://trust.evenuplaw.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/evenup-trust-center.yml\ntrust_center:\n  url: https://trust.evenuplaw.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 examination\n  scope: EvenUp security and compliance program\n  period: null\n  issuer: null\n  report_access: on_request\n  text: EvenUp’s security and compliance program has been independently assessed through a SOC 2 Type 2 examination\n    and a HIPAA compliance assessment.\n- framework: HIPAA\n  type: HIPAA compliance assessment / attestation\n  scope: EvenUp security\
  \ and compliance program\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Our security program is independently assessed through a SOC 2 Type 2 examination and HIPAA attestation.\n    Relevant reports are available to customers and prospects upon request.\n"
source_yaml_url: https://artifacts.apis.io/evenup/compliance/evenup-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from EvenUp's own page on 2026-11-09.
synthetic: false
tags:
- Legal
- Legal Tech
- Personal Injury
- Plaintiff Law
- Case Management
- Demand Letters
- Medical Records
- AI Drafting
- Workflow Automation
- Settlement
- Litigation
- Software-as-a-Service
---
