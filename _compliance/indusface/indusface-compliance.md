---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: third-party assessors
    period: null
    report_access: on_request
    scope: service provider
    text: Indusface has maintained PCI DSS service provider compliance since 2018 and is now PCI DSS v4.0.1 certified.
    type: certification
  - framework: ISO27001
    issuer: third-party assessors
    period: null
    report_access: on_request
    scope: information security management system
    text: ISO/IEC 27001:2022 Certified since 2019
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Indusface is fully GDPR compliant and publishes a Data Processing Addendum (DPA) as part of its service terms.
    type: compliance
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: security, availability, processing integrity, confidentiality, and privacy controls
    text: Indusface is SOC 2 compliant.
    type: audit report
  - framework: other
    issuer: CERT-In
    period: null
    report_access: unstated
    scope: vulnerability assessment and penetration testing (VAPT) in India
    text: Indusface's empanelment as a CERT-In security auditor empowers it to carry out vulnerability assessment and penetration testing (VAPT) of the IT infrastructures for organizations of various sizes across India.
    type: empanelment
  trust_center:
    url: https://www.indusface.com/security-accreditations/
frameworks:
- GDPR
- ISO27001
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Indusface
provenance_date: '2026-11-09'
provider_name: Indusface
provider_slug: indusface
slug: indusface-compliance
source_date: '2026-11-09'
source_filename: indusface-compliance.yml
source_heading: Compliance
source_page: https://www.indusface.com/security-accreditations/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Indusface\naid: indusface\nurl: https://www.indusface.com/security-accreditations/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.indusface.com/security-accreditations/\nattestations:\n- framework: PCI-DSS\n  type: certification\n  scope: service provider\n  period: null\n  issuer: third-party assessors\n  report_access: on_request\n  text: Indusface has maintained PCI DSS service provider compliance since 2018 and is now PCI DSS v4.0.1 certified.\n- framework: ISO27001\n  type: certification\n  scope: information security management system\n  period: null\n  issuer: third-party assessors\n  report_access:\
  \ on_request\n  text: ISO/IEC 27001:2022 Certified since 2019\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Indusface is fully GDPR compliant and publishes a Data Processing Addendum (DPA) as part of its service\n    terms.\n- framework: SOC2\n  type: audit report\n  scope: security, availability, processing integrity, confidentiality, and privacy controls\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Indusface is SOC 2 compliant.\n- framework: other\n  type: empanelment\n  scope: vulnerability assessment and penetration testing (VAPT) in India\n  period: null\n  issuer: CERT-In\n  report_access: unstated\n  text: Indusface's empanelment as a CERT-In security auditor empowers it to carry out vulnerability assessment\n    and penetration testing (VAPT) of the IT infrastructures for organizations of various sizes across India.\n"
source_yaml_url: https://artifacts.apis.io/indusface/compliance/indusface-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Indusface's own page on 2026-11-09.
synthetic: false
tags:
- Security
- Web Application Firewall
- Cloud
- Artificial Intelligence
- Enterprise
---
