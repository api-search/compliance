---
api_specs:
- filename: healthie-webhooks-asyncapi.yml
  format: yaml
  label: Healthie GraphQL API
  slug: healthie-graphql-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/healthie/asyncapi/healthie-webhooks-asyncapi.yml
claim_count: 13
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Healthie platform
    text: Healthie is compliant with US Health Insurance Portability and Accountability Act (HIPAA) regulations.
    type: compliance statement
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Healthie platform
    text: SOC 2 Certified Security standard relevant to the trust services criteria categories covering security, availability, processing integrity, confidentiality and privacy.
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Healthie platform
    text: GDPR-Compliant The General Data Protection Regulation (GDPR) is a regulation that requires businesses to protect the personal data and privacy of EU citizens for transactions.
    type: compliance statement
  - framework: HITRUST
    issuer: null
    period: null
    report_access: unstated
    scope: Healthie platform
    text: Healthie is HITRUST Certified (Type R2) certified, utilizing the HITRUST CSF® framework
    type: certification
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Healthie platform
    text: We process credit card transactions using secure encryption on a Level 1 PCI-compliant network.
    type: compliance statement
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Healthie platform
    text: Healthie’s infrastructure protects data in compliance with the Canadian Personal Information Protection and Electronic Documents Act (PIPEDA).
    type: compliance statement
  - framework: other
    issuer: ONC-ACB
    period: null
    report_access: unstated
    scope: Health IT Module
    text: This Health IT Module is compliant with the ONC Certification Criteria for Health IT and has been certified by an ONC-ACB
    type: certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Healthie platform
    source: https://www.gethealthie.com/hipaa-compliant-software
    text: Healthie is compliant with US Health Insurance Portability and Accountability Act (HIPAA) regulations.
    type: Compliance statement
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Healthie platform
    source: https://www.gethealthie.com/hipaa-compliant-software
    text: SOC 2 Certified Security standard relevant to the trust services criteria categories covering security, availability, processing integrity, confidentiality and privacy.
    type: Certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Healthie platform
    source: https://www.gethealthie.com/hipaa-compliant-software
    text: GDPR-Compliant The General Data Protection Regulation (GDPR) is a regulation that requires businesses to protect the personal data and privacy of EU citizens for transactions.
    type: Compliance statement
  - framework: HITRUST
    issuer: null
    period: null
    report_access: unstated
    scope: Healthie platform
    source: https://www.gethealthie.com/hipaa-compliant-software
    text: Healthie is HITRUST Certified (Type R2) certified, utilizing the HITRUST CSF® framework
    type: Certification (Type R2)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Healthie infrastructure
    source: https://www.gethealthie.com/hipaa-compliant-software
    text: Healthie’s infrastructure protects data in compliance with the Canadian Personal Information Protection and Electronic Documents Act (PIPEDA).
    type: Compliance statement (PIPEDA)
  - framework: other
    issuer: ONC-ACB
    period: null
    report_access: unstated
    scope: Health IT Module
    source: https://www.gethealthie.com/hipaa-compliant-software
    text: This Health IT Module is compliant with the ONC Certification Criteria for Health IT and has been certified by an ONC-ACB
    type: ONC Health IT certification
  trust_center:
    url: https://www.gethealthie.com/hipaa-compliant-software
frameworks:
- GDPR
- HIPAA
- HITRUST
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Healthie
provenance_date: '2026-11-09'
provider_name: Healthie
provider_slug: healthie
slug: healthie-compliance
source_date: '2026-11-09'
source_filename: healthie-compliance.yml
source_heading: Compliance
source_page: https://www.gethealthie.com/hipaa-compliant-software
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Healthie\naid: healthie\nurl: https://www.gethealthie.com/hipaa-compliant-software\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/healthie-trust-center.yml\n  sources:\n  - https://www.gethealthie.com/hipaa-compliant-software\ntrust_center:\n  url: https://www.gethealthie.com/hipaa-compliant-software\nattestations:\n- framework: HIPAA\n  type: compliance statement\n  scope: Healthie platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Healthie is compliant with US Health Insurance Portability and Accountability Act (HIPAA) regulations.\n- framework: SOC2\n  type: certification\n\
  \  scope: Healthie platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Certified Security standard relevant to the trust services criteria categories covering security,\n    availability, processing integrity, confidentiality and privacy.\n- framework: GDPR\n  type: compliance statement\n  scope: Healthie platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR-Compliant The General Data Protection Regulation (GDPR) is a regulation that requires businesses to\n    protect the personal data and privacy of EU citizens for transactions.\n- framework: HITRUST\n  type: certification\n  scope: Healthie platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Healthie is HITRUST Certified (Type R2) certified, utilizing the HITRUST CSF® framework\n- framework: PCI-DSS\n  type: compliance statement\n  scope: Healthie platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We process credit card transactions\
  \ using secure encryption on a Level 1 PCI-compliant network.\n- framework: PCI-DSS\n  type: compliance statement\n  scope: Healthie platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Healthie’s infrastructure protects data in compliance with the Canadian Personal Information Protection\n    and Electronic Documents Act (PIPEDA).\n- framework: other\n  type: certification\n  scope: Health IT Module\n  period: null\n  issuer: ONC-ACB\n  report_access: unstated\n  text: This Health IT Module is compliant with the ONC Certification Criteria for Health IT and has been certified\n    by an ONC-ACB\n- framework: HIPAA\n  type: Compliance statement\n  scope: Healthie platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Healthie is compliant with US Health Insurance Portability and Accountability Act (HIPAA) regulations.\n  source: https://www.gethealthie.com/hipaa-compliant-software\n- framework: SOC2\n  type: Certification\n  scope: Healthie\
  \ platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Certified Security standard relevant to the trust services criteria categories covering security,\n    availability, processing integrity, confidentiality and privacy.\n  source: https://www.gethealthie.com/hipaa-compliant-software\n- framework: GDPR\n  type: Compliance statement\n  scope: Healthie platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR-Compliant The General Data Protection Regulation (GDPR) is a regulation that requires businesses to\n    protect the personal data and privacy of EU citizens for transactions.\n  source: https://www.gethealthie.com/hipaa-compliant-software\n- framework: HITRUST\n  type: Certification (Type R2)\n  scope: Healthie platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Healthie is HITRUST Certified (Type R2) certified, utilizing the HITRUST CSF® framework\n  source: https://www.gethealthie.com/hipaa-compliant-software\n\
  - framework: other\n  type: Compliance statement (PIPEDA)\n  scope: Healthie infrastructure\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Healthie’s infrastructure protects data in compliance with the Canadian Personal Information Protection\n    and Electronic Documents Act (PIPEDA).\n  source: https://www.gethealthie.com/hipaa-compliant-software\n- framework: other\n  type: ONC Health IT certification\n  scope: Health IT Module\n  period: null\n  issuer: ONC-ACB\n  report_access: unstated\n  text: This Health IT Module is compliant with the ONC Certification Criteria for Health IT and has been certified\n    by an ONC-ACB\n  source: https://www.gethealthie.com/hipaa-compliant-software\n"
source_yaml_url: https://artifacts.apis.io/healthie/compliance/healthie-compliance.yml
stated_fields:
- attestations
summary_line: 13 quoted statements, read from Healthie's own page on 2026-11-09.
synthetic: false
tags:
- API-First
- Appointments
- Billing
- Care Plans
- Charting
- Claims
- Clinical
- Digital Health
- Electronic Health Records
- Forms
- GraphQL
- Health Tech
- Healthcare
- Insurance
- Intake
- Online Programs
- Patient Engagement
- Patient Portal
- Practice Management
- Programs
- Scheduling
- Telehealth
- Wellness
- Webhook
- Real-Time
- FHIR
---
