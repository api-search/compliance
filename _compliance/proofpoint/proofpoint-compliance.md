---
claim_count: 10
description: ''
doc:
  attestations:
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: AIMS supporting in-scope solutions identified in the certificate
    text: Proofpoint achieved ISO 42001 certification for its AIMS that supports the in-scope solutions identified in the certificate.
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: information security management system supporting in-scope solutions identified in the certificate
    text: Proofpoint achieved ISO 27001 certification for its information security management system that supports the in-scope solutions identified in the certificate.
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: products
    text: Request Proofpoint’s SOC 2 Reports .
    type: audit
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: cloud-based products and services
    text: Proofpoint’s FedRAMP authorization may be found at the FedRAMP Marketplace .
    type: authorization
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: information systems supporting the services identified in the certificate
    text: Proofpoint has received a certificate of conformity with Spain's National Security Framework for the information systems supporting the services identified in the certificate.
    type: certificate of conformity
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: EU-U.S., UK Extension and Swiss-U.S. Data Privacy Frameworks
    text: Proofpoint complies with the EU-U.S., UK Extension to the EU-U.S., and Swiss-U.S. Data Privacy Frameworks.
    type: compliance
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Proofpoint Archive
    text: Proofpoint Archive is PCI compliant.
    type: compliance
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: security and privacy controls
    text: Proofpoint is listed on the Security, Trust, Assurance, and Risk (STAR) Registry documenting its security and privacy controls.
    type: registry listing
  - framework: DORA
    issuer: null
    period: null
    report_access: public
    scope: Critical or Important Functions Under DORA
    source: https://www.proofpoint.com/us/legal/trust
    text: March 02, 2026 Critical or Important Functions Under DORA
    type: regulatory document
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: Federal Government solution
    source: https://www.proofpoint.com/us/legal/trust
    text: Enable your agency with FedRAMP certified security
    type: certification mention
  trust_center:
    url: https://www.proofpoint.com/us/legal/trust/product-certifications
frameworks:
- CSA-STAR
- DORA
- FedRAMP
- ISO27001
- ISO42001
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Proofpoint
provenance_date: '2026-11-10'
provider_name: Proofpoint
provider_slug: proofpoint
slug: proofpoint-compliance
source_date: '2026-11-10'
source_filename: proofpoint-compliance.yml
source_heading: Compliance
source_page: https://www.proofpoint.com/us/legal/trust/product-certifications
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Proofpoint\naid: proofpoint\nurl: https://www.proofpoint.com/us/legal/trust/product-certifications\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.proofpoint.com/us/legal/trust\n  - https://www.proofpoint.com/us/legal/trust/product-certifications\ntrust_center:\n  url: https://www.proofpoint.com/us/legal/trust/product-certifications\nattestations:\n- framework: ISO42001\n  type: certification\n  scope: AIMS supporting in-scope solutions identified in the certificate\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Proofpoint achieved ISO 42001 certification for its AIMS that supports\
  \ the in-scope solutions identified\n    in the certificate.\n- framework: ISO27001\n  type: certification\n  scope: information security management system supporting in-scope solutions identified in the certificate\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Proofpoint achieved ISO 27001 certification for its information security management system that supports\n    the in-scope solutions identified in the certificate.\n- framework: SOC2\n  type: audit\n  scope: products\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Request Proofpoint’s SOC 2 Reports .\n- framework: FedRAMP\n  type: authorization\n  scope: cloud-based products and services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Proofpoint’s FedRAMP authorization may be found at the FedRAMP Marketplace .\n- framework: other\n  type: certificate of conformity\n  scope: information systems supporting the services identified in the certificate\n  period: null\n \
  \ issuer: null\n  report_access: unstated\n  text: Proofpoint has received a certificate of conformity with Spain's National Security Framework for the information\n    systems supporting the services identified in the certificate.\n- framework: other\n  type: compliance\n  scope: EU-U.S., UK Extension and Swiss-U.S. Data Privacy Frameworks\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Proofpoint complies with the EU-U.S., UK Extension to the EU-U.S., and Swiss-U.S. Data Privacy Frameworks.\n- framework: PCI-DSS\n  type: compliance\n  scope: Proofpoint Archive\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Proofpoint Archive is PCI compliant.\n- framework: CSA-STAR\n  type: registry listing\n  scope: security and privacy controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Proofpoint is listed on the Security, Trust, Assurance, and Risk (STAR) Registry documenting its security\n    and privacy controls.\n- framework: DORA\n\
  \  type: regulatory document\n  scope: Critical or Important Functions Under DORA\n  period: null\n  issuer: null\n  report_access: public\n  text: March 02, 2026 Critical or Important Functions Under DORA\n  source: https://www.proofpoint.com/us/legal/trust\n- framework: FedRAMP\n  type: certification mention\n  scope: Federal Government solution\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Enable your agency with FedRAMP certified security\n  source: https://www.proofpoint.com/us/legal/trust\n"
source_yaml_url: https://artifacts.apis.io/proofpoint/compliance/proofpoint-compliance.yml
stated_fields:
- attestations
summary_line: 10 quoted statements, read from Proofpoint's own page on 2026-11-10.
synthetic: false
tags:
- Security
- Cybersecurity
- Email Security
- Threat Intelligence
- Data Loss Prevention
- Security Awareness Training
- Insider Threat
- SIEM
- Compliance
- Email
---
