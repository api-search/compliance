---
api_specs:
- filename: 2sAYQZJYMC
  format: yaml
  label: GreyMatter API
  slug: greymatter-api
  spec_type: Postman
  url: https://apidocs.myreliaquest.com/api/collections/39440280/2sAYQZJYMC?segregateAuth=true&versionTag=latest
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: annual
    report_access: unstated
    scope: security controls, availability, and data-handling practices
    text: Yes, ReliaQuest maintains SOC 2 Type II attestation, which is verified through independent annual audits of the company's security controls, availability, and data-handling practices.
    type: Type II attestation
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Yes, ReliaQuest maintains HIPAA and PCI-DSS compliance.
    type: compliance
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Yes, ReliaQuest maintains HIPAA and PCI-DSS compliance.
    type: compliance
  trust_center:
    url: https://reliaquest.com/resources/greymatter-faq/data-privacy-and-compliance-faq/
frameworks:
- HIPAA
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: ReliaQuest
provenance_date: '2026-11-10'
provider_name: ReliaQuest
provider_slug: reliaquest
slug: reliaquest-compliance
source_date: '2026-11-10'
source_filename: reliaquest-compliance.yml
source_heading: Compliance
source_page: https://reliaquest.com/resources/greymatter-faq/data-privacy-and-compliance-faq/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: ReliaQuest\naid: reliaquest\nurl: https://reliaquest.com/resources/greymatter-faq/data-privacy-and-compliance-faq/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/reliaquest-trust-center.yml\ntrust_center:\n  url: https://reliaquest.com/resources/greymatter-faq/data-privacy-and-compliance-faq/\nattestations:\n- framework: SOC2\n  type: Type II attestation\n  scope: security controls, availability, and data-handling practices\n  period: annual\n  issuer: null\n  report_access: unstated\n  text: Yes, ReliaQuest maintains SOC 2 Type II attestation, which is verified through independent annual audits\n\
  \    of the company's security controls, availability, and data-handling practices.\n- framework: HIPAA\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Yes, ReliaQuest maintains HIPAA and PCI-DSS compliance.\n- framework: PCI-DSS\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Yes, ReliaQuest maintains HIPAA and PCI-DSS compliance.\n"
source_yaml_url: https://artifacts.apis.io/reliaquest/compliance/reliaquest-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from ReliaQuest's own page on 2026-11-10.
synthetic: false
tags:
- Cybersecurity
- Security Operations
- Threat Detection
- Incident Response
- Threat Intelligence
- Digital Risk Protection
- AI Agents
- GraphQL
---
