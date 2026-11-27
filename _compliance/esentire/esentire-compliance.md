---
claim_count: 15
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: December 1, 2024 to November 30, 2025
    report_access: unstated
    scope: Managed Detection and Response Services System
    text: Report on eSentire Inc.’s Description of its Managed Detection and Response Services System on the Suitability of the Design and Operating Effectiveness of its Controls Relevant to the Security, Trust Services Criteria for the period December 1, 2024 to November 30, 2025.
    type: SOC 2 Type 2 report
  - framework: SOC2
    issuer: null
    period: December 1, 2024 to November 30, 2025
    report_access: unstated
    scope: Digital Forensics Incident Response Services System
    text: For the period December 1, 2024 to November 30, 2025.
    type: SOC 2 Type 2 report
  - framework: SOC2
    issuer: null
    period: February 2026
    report_access: unstated
    scope: null
    text: SOC2 Bridge Letter - February 2026
    type: Bridge letter
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: 'Certificate #IS735163'
    type: Certificate of Registration (ISO 27001:2022)
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: eSentire XDR Services
    text: We are pleased to share our latest PCI DSS 4.01 Attestation of Compliance for eSentire XDR Services.
    type: Attestation of Compliance (PCI DSS 4.0.1)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Internal/external Penetration Test
    text: Updated attestation on the completion of an independent internal/external Penetration Test.
    type: Penetration test attestation
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: CJIS policy areas
    text: Description as to how eSentire complies with the CJIS policy areas.
    type: Statement of compliance (CJIS)
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: Trust page badge
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: Trust page badge
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA
    type: Trust page badge
  - framework: DORA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: DORA
    type: Trust page badge
  - framework: SOC2
    issuer: null
    period: December 1, 2024 to November 30, 2025
    report_access: unstated
    scope: Managed Detection & Response capabilities and DF/IR Services
    source: https://trust.esentire.com/
    text: We are please to announce the availability of our most recent SOC2 Type 2 audit reports for our Managed Detection & Response capabilities and our DF/IR Services for the period December 1, 2024 to November 30, 2025.
    type: SOC 2 Type 2 audit report
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: eSentire XDR Services
    source: https://trust.esentire.com/
    text: We are pleased to share our latest PCI DSS 4.01 Attestation of Compliance for eSentire XDR Services.
    type: Attestation of Compliance (PCI DSS 4.01)
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.esentire.com/
    text: ISO 27001:2022 Certificate of Registration
    type: Certificate of Registration (ISO 27001:2022)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.esentire.com/
    text: eSentire Statement on Criminal Justice Information Systems (CJIS) Compliance
    type: CJIS compliance statement
  trust_center:
    url: https://trust.esentire.com/api/trustpage/public/v1/
frameworks:
- CCPA
- DORA
- GDPR
- HIPAA
- ISO27001
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: eSentire
provenance_date: '2026-11-09'
provider_name: eSentire
provider_slug: esentire
slug: esentire-compliance
source_date: '2026-11-09'
source_filename: esentire-compliance.yml
source_heading: Compliance
source_page: https://trust.esentire.com/api/trustpage/public/v1/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: eSentire\naid: esentire\nurl: https://trust.esentire.com/api/trustpage/public/v1/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/esentire-trust-center.yml\n  sources:\n  - https://trust.esentire.com/\n  - https://trust.esentire.com/api/trustpage/public/v1/\ntrust_center:\n  url: https://trust.esentire.com/api/trustpage/public/v1/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: Managed Detection and Response Services System\n  period: December 1, 2024 to November 30, 2025\n  issuer: null\n  report_access: unstated\n  text: Report on eSentire Inc.’s Description of its Managed\
  \ Detection and Response Services System on the Suitability\n    of the Design and Operating Effectiveness of its Controls Relevant to the Security, Trust Services Criteria\n    for the period December 1, 2024 to November 30, 2025.\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: Digital Forensics Incident Response Services System\n  period: December 1, 2024 to November 30, 2025\n  issuer: null\n  report_access: unstated\n  text: For the period December 1, 2024 to November 30, 2025.\n- framework: SOC2\n  type: Bridge letter\n  scope: null\n  period: February 2026\n  issuer: null\n  report_access: unstated\n  text: SOC2 Bridge Letter - February 2026\n- framework: ISO27001\n  type: Certificate of Registration (ISO 27001:2022)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'Certificate #IS735163'\n- framework: PCI-DSS\n  type: Attestation of Compliance (PCI DSS 4.0.1)\n  scope: eSentire XDR Services\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: We are pleased to share our latest PCI DSS 4.01 Attestation of Compliance for eSentire XDR Services.\n- framework: other\n  type: Penetration test attestation\n  scope: Internal/external Penetration Test\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Updated attestation on the completion of an independent internal/external Penetration Test.\n- framework: other\n  type: Statement of compliance (CJIS)\n  scope: CJIS policy areas\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Description as to how eSentire complies with the CJIS policy areas.\n- framework: GDPR\n  type: Trust page badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: HIPAA\n  type: Trust page badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n- framework: CCPA\n  type: Trust page badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text:\
  \ CCPA\n- framework: DORA\n  type: Trust page badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: DORA\n- framework: SOC2\n  type: SOC 2 Type 2 audit report\n  scope: Managed Detection & Response capabilities and DF/IR Services\n  period: December 1, 2024 to November 30, 2025\n  issuer: null\n  report_access: unstated\n  text: We are please to announce the availability of our most recent SOC2 Type 2 audit reports for our Managed\n    Detection & Response capabilities and our DF/IR Services for the period December 1, 2024 to November 30, 2025.\n  source: https://trust.esentire.com/\n- framework: PCI-DSS\n  type: Attestation of Compliance (PCI DSS 4.01)\n  scope: eSentire XDR Services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are pleased to share our latest PCI DSS 4.01 Attestation of Compliance for eSentire XDR Services.\n  source: https://trust.esentire.com/\n- framework: ISO27001\n  type: Certificate of Registration (ISO\
  \ 27001:2022)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022 Certificate of Registration\n  source: https://trust.esentire.com/\n- framework: other\n  type: CJIS compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: eSentire Statement on Criminal Justice Information Systems (CJIS) Compliance\n  source: https://trust.esentire.com/\n"
source_yaml_url: https://artifacts.apis.io/esentire/compliance/esentire-compliance.yml
stated_fields:
- attestations
summary_line: 15 quoted statements, read from eSentire's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Cybersecurity
- Managed Detection and Response
- Threat Intelligence
- Incident Response
- MCP
- Agents
- Authentication
- Software-as-a-Service
---
