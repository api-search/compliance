---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: security, availability, processing integrity, confidentiality, and privacy
    text: Our platform is built on stringent security measures and compliance with top industry standards, including SOC-2 Type 2, GDPR, and HIPAA.
    type: SOC-2 Type 2
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: users in the European Union
    text: At Sworkit Health, we embrace the principles of the General Data Protection Regulation to guarantee robust data protection and privacy for our users in the European Union.
    type: GDPR compliance
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: patient health information
    text: Compliance with the Health Insurance Portability and Accountability Act underscores our dedication to protecting sensitive patient health information.
    type: HIPAA compliance
  trust_center:
    url: https://sworkit.com/security
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Sworkit
provenance_date: '2026-11-10'
provider_name: Sworkit
provider_slug: sworkit
slug: sworkit-compliance
source_date: '2026-11-10'
source_filename: sworkit-compliance.yml
source_heading: Compliance
source_page: https://sworkit.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Sworkit\naid: sworkit\nurl: https://sworkit.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://sworkit.com/security\nattestations:\n- framework: SOC2\n  type: SOC-2 Type 2\n  scope: security, availability, processing integrity, confidentiality, and privacy\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Our platform is built on stringent security measures and compliance with top industry standards, including\n    SOC-2 Type 2, GDPR, and HIPAA.\n- framework: GDPR\n  type: GDPR compliance\n  scope: users in the European Union\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: At Sworkit Health, we embrace the principles of the General Data Protection Regulation to guarantee robust\n    data protection and privacy for our users in the European Union.\n- framework: HIPAA\n  type: HIPAA compliance\n  scope: patient health information\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance with the Health Insurance Portability and Accountability Act underscores our dedication to protecting\n    sensitive patient health information.\n"
source_yaml_url: https://artifacts.apis.io/sworkit/compliance/sworkit-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Sworkit's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fitness
- Health and Wellness
- Employee Wellbeing
- Workouts
- Mindfulness
- Nutrition
- Embeddable Components
- SDK
---
