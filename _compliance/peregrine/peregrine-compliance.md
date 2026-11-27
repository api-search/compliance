---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: external auditor
    period: three-month period
    report_access: unstated
    scope: security, availability, and confidentiality
    text: An external auditor validated the design and operating effectiveness of controls over security, availability, and confidentiality for a three-month period.
    type: Type II certification
  - framework: SOC2
    issuer: licensed CPA firm
    period: null
    report_access: unstated
    scope: security, availability, and confidentiality
    text: A licensed CPA firm verified that controls for security, availability, and confidentiality were designed and operated effectively throughout the audit period.
    type: Type II report
  trust_center:
    url: https://trustcenter.peregrine.io/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Peregrine
provenance_date: '2026-11-10'
provider_name: Peregrine
provider_slug: peregrine
slug: peregrine-compliance
source_date: '2026-11-10'
source_filename: peregrine-compliance.yml
source_heading: Compliance
source_page: https://trustcenter.peregrine.io/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Peregrine\naid: peregrine\nurl: https://trustcenter.peregrine.io/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trustcenter.peregrine.io/\nattestations:\n- framework: SOC2\n  type: Type II certification\n  scope: security, availability, and confidentiality\n  period: three-month period\n  issuer: external auditor\n  report_access: unstated\n  text: An external auditor validated the design and operating effectiveness of controls over security, availability,\n    and confidentiality for a three-month period.\n- framework: SOC2\n  type: Type II report\n  scope: security, availability, and confidentiality\n\
  \  period: null\n  issuer: licensed CPA firm\n  report_access: unstated\n  text: A licensed CPA firm verified that controls for security, availability, and confidentiality were designed\n    and operated effectively throughout the audit period.\n"
source_yaml_url: https://artifacts.apis.io/peregrine/compliance/peregrine-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Peregrine's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Infrastructure
- Public Safety
- Law Enforcement
- Government
- Data Integration
- Artificial Intelligence
- Situational Awareness
- Emergency Response
---
