---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: AICPA-accredited firm
    period: null
    report_access: unstated
    scope: security, availability, processing integrity, confidentiality, and privacy
    text: We maintain a Service Organization Control Type 2 (SOC 2) Type 2 certification.
    type: SOC 2 Type 2 certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Health Insurance Portability and Accountability Act of 1996 (HIPAA)
    text: This SOC 2 Type 2 also measures our compliance with the Health Insurance Portability and Accountability Act of 1996 (HIPAA).
    type: compliance measured within SOC 2 Type 2
  - framework: other
    issuer: Joint Commission
    period: null
    report_access: unstated
    scope: telehealth
    text: HealthTap is the first virtual primary care physician practice to achieve Joint Commission accreditation for telehealth.
    type: Joint Commission accreditation for telehealth
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: General Data Protection Regulation 2016/679 (GDPR) helps shape standards and policies
    text: General Data Protection Regulation 2016/679 (GDPR)
    type: standards influence
  trust_center:
    url: https://www.healthtap.com/security/
frameworks:
- GDPR
- HIPAA
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: HealthTap
provenance_date: '2026-11-09'
provider_name: HealthTap
provider_slug: healthtap
slug: healthtap-compliance
source_date: '2026-11-09'
source_filename: healthtap-compliance.yml
source_heading: Compliance
source_page: https://www.healthtap.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: HealthTap\naid: healthtap\nurl: https://www.healthtap.com/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.healthtap.com/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 certification\n  scope: security, availability, processing integrity, confidentiality, and privacy\n  period: null\n  issuer: AICPA-accredited firm\n  report_access: unstated\n  text: We maintain a Service Organization Control Type 2 (SOC 2) Type 2 certification.\n- framework: HIPAA\n  type: compliance measured within SOC 2 Type 2\n  scope: Health Insurance Portability and Accountability Act of 1996 (HIPAA)\n\
  \  period: null\n  issuer: null\n  report_access: unstated\n  text: This SOC 2 Type 2 also measures our compliance with the Health Insurance Portability and Accountability\n    Act of 1996 (HIPAA).\n- framework: other\n  type: Joint Commission accreditation for telehealth\n  scope: telehealth\n  period: null\n  issuer: Joint Commission\n  report_access: unstated\n  text: HealthTap is the first virtual primary care physician practice to achieve Joint Commission accreditation\n    for telehealth.\n- framework: GDPR\n  type: standards influence\n  scope: General Data Protection Regulation 2016/679 (GDPR) helps shape standards and policies\n  period: null\n  issuer: null\n  report_access: unstated\n  text: General Data Protection Regulation 2016/679 (GDPR)\n"
source_yaml_url: https://artifacts.apis.io/healthtap/compliance/healthtap-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from HealthTap's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health Tech
- Telehealth
- Virtual Care
- Healthcare
- Primary Care
- Digital Health
---
