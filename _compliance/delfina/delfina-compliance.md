---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Delfina
    text: Delfina is fully compliant with the Health Insurance Portability and Accountability Act (HIPAA).
    type: compliance statement
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Security, Confidentiality, and Availability
    text: Delfina maintains a SOC 2 Type II certification for Security, Confidentiality, and Availability.
    type: Type II certification
  trust_center:
    url: https://www.delfina.com/security
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Delfina
provenance_date: '2026-11-09'
provider_name: Delfina
provider_slug: delfina
slug: delfina-compliance
source_date: '2026-11-09'
source_filename: delfina-compliance.yml
source_heading: Compliance
source_page: https://www.delfina.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Delfina\naid: delfina\nurl: https://www.delfina.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.delfina.com/security\nattestations:\n- framework: HIPAA\n  type: compliance statement\n  scope: Delfina\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Delfina is fully compliant with the Health Insurance Portability and Accountability Act (HIPAA).\n- framework: SOC2\n  type: Type II certification\n  scope: Security, Confidentiality, and Availability\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Delfina maintains a SOC 2 Type II certification for Security,\
  \ Confidentiality, and Availability.\n"
source_yaml_url: https://artifacts.apis.io/delfina/compliance/delfina-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Delfina's own page on 2026-11-09.
synthetic: false
tags:
- Maternal Health
- Pregnancy Care
- Digital Health
- Remote Patient Monitoring
- Telehealth
- Health Plans
- Employer Benefits
- HIPAA
- SOC 2
---
