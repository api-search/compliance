---
claim_count: 10
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: since 2017
    report_access: unstated
    scope: Lookout products
    text: The Lookout products have been certified as ISO/IEC 27001, 27017, and27018 compliant since 2017.
    type: ISO/IEC 27001 certification
  - framework: ISO27017
    issuer: null
    period: since 2017
    report_access: unstated
    scope: Lookout products
    text: The Lookout products have been certified as ISO/IEC 27001, 27017, and27018 compliant since 2017.
    type: ISO/IEC 27017 certification
  - framework: ISO27018
    issuer: null
    period: null
    report_access: unstated
    scope: Lookout products
    text: The Lookout products are certified as ISO/IEC 27018 compliant.
    type: ISO/IEC 27018 certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Business continuity program
    text: Lookout complies with ISO/IEC 22301.2019 standards.
    type: ISO/IEC 22301 compliance
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: Lookout cloud services
    text: Lookout maintains a FedRAMP Moderate accreditation that is renewed on an annual cadence.
    type: FedRAMP Moderate accreditation
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: Lookout Platform
    text: 'Lookout has submitted for the self-assessed CSA STAR Level 1: Attestation for the Lookout Platform.'
    type: CSA STAR Level 1 self-assessment (submitted)
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Lookout Platform
    text: Lookout currently maintains SOC2 Type2 for the Lookout Platform.
    type: SOC 2 Type 2
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: Mobile EDR only (per asterisk)
    source: https://security.lookout.com/
    text: FedRAMP * | SOC2 | GDPR Compliant * Mobile EDR only
    type: compliance statement
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: unstated
    source: https://security.lookout.com/
    text: FedRAMP * | SOC2 | GDPR Compliant * Mobile EDR only
    type: compliance statement
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Mobile EDR only (per asterisk)
    source: https://security.lookout.com/
    text: FedRAMP * | SOC2 | GDPR Compliant * Mobile EDR only
    type: compliance statement
  trust_center:
    url: https://www.lookout.com/legal/compliance-corner
frameworks:
- CSA-STAR
- FedRAMP
- GDPR
- ISO27001
- ISO27017
- ISO27018
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Lookout
provenance_date: '2026-11-09'
provider_name: Lookout
provider_slug: lookout
slug: lookout-compliance
source_date: '2026-11-09'
source_filename: lookout-compliance.yml
source_heading: Compliance
source_page: https://www.lookout.com/legal/compliance-corner
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Lookout\naid: lookout\nurl: https://www.lookout.com/legal/compliance-corner\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/lookout-trust-center.yml\n  sources:\n  - https://security.lookout.com/\n  - https://www.lookout.com/legal/compliance-corner\ntrust_center:\n  url: https://www.lookout.com/legal/compliance-corner\nattestations:\n- framework: ISO27001\n  type: ISO/IEC 27001 certification\n  scope: Lookout products\n  period: since 2017\n  issuer: null\n  report_access: unstated\n  text: The Lookout products have been certified as ISO/IEC 27001, 27017, and27018 compliant since 2017.\n- framework:\
  \ ISO27017\n  type: ISO/IEC 27017 certification\n  scope: Lookout products\n  period: since 2017\n  issuer: null\n  report_access: unstated\n  text: The Lookout products have been certified as ISO/IEC 27001, 27017, and27018 compliant since 2017.\n- framework: ISO27018\n  type: ISO/IEC 27018 certification\n  scope: Lookout products\n  period: null\n  issuer: null\n  report_access: unstated\n  text: The Lookout products are certified as ISO/IEC 27018 compliant.\n- framework: other\n  type: ISO/IEC 22301 compliance\n  scope: Business continuity program\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Lookout complies with ISO/IEC 22301.2019 standards.\n- framework: FedRAMP\n  type: FedRAMP Moderate accreditation\n  scope: Lookout cloud services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Lookout maintains a FedRAMP Moderate accreditation that is renewed on an annual cadence.\n- framework: CSA-STAR\n  type: CSA STAR Level 1 self-assessment (submitted)\n\
  \  scope: Lookout Platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'Lookout has submitted for the self-assessed CSA STAR Level 1: Attestation for the Lookout Platform.'\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: Lookout Platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Lookout currently maintains SOC2 Type2 for the Lookout Platform.\n- framework: FedRAMP\n  type: compliance statement\n  scope: Mobile EDR only (per asterisk)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: FedRAMP * | SOC2 | GDPR Compliant * Mobile EDR only\n  source: https://security.lookout.com/\n- framework: SOC2\n  type: compliance statement\n  scope: unstated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: FedRAMP * | SOC2 | GDPR Compliant * Mobile EDR only\n  source: https://security.lookout.com/\n- framework: GDPR\n  type: compliance statement\n  scope: Mobile EDR only (per asterisk)\n  period: null\n  issuer: null\n\
  \  report_access: unstated\n  text: FedRAMP * | SOC2 | GDPR Compliant * Mobile EDR only\n  source: https://security.lookout.com/\n"
source_yaml_url: https://artifacts.apis.io/lookout/compliance/lookout-compliance.yml
stated_fields:
- attestations
summary_line: 10 quoted statements, read from Lookout's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Mobile Security
- Endpoint Security
- Threat Intelligence
- Mobile Threat Defense
- Data Protection
- SIEM
---
