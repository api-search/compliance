---
claim_count: 13
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Your data is hosted on ISO 27001-compliant servers, ensuring global standards for security, availability, and privacy are upheld at every moment.
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CapLinked has been independently assessed to meet SOC 2 standards, implementing industry-leading practices for risk management, access control, system monitoring, and data handling.
    type: independent assessment
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: cross-border data transfers
    text: We comply with the EU-U.S. Privacy Shield framework, ensuring your cross-border data transfers meet the highest standards of privacy and protection as defined by European Commission regulations and U.S. Department of Commerce principles.
    type: framework compliance (EU-U.S. Privacy Shield)
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CapLinked meets all requirements under HIPAA and HITECH standards, making it a reliable choice for organizations in healthcare.
    type: compliance claim
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Our platform is PCI SAQ-D compliant, providing a secure environment for organizations that process credit card and other financial information.
    type: compliance claim (SAQ-D)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: U.S. government clients
    text: For our U.S. government clients, CapLinked meets all Federal Information Security Management Act (FISMA) requirements by implementing NIST SP 800-53 controls
    type: compliance claim (FISMA)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: VDR product
    text: CMMC Compliant VDR
    type: compliance claim (CMMC)
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: hosting servers / platform
    source: https://www.caplinked.com/security/
    text: Your data is hosted on ISO 27001-compliant servers
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: CapLinked platform
    source: https://www.caplinked.com/security/
    text: CapLinked has been independently assessed to meet SOC 2 standards
    type: independent assessment
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: CapLinked platform
    source: https://www.caplinked.com/security/
    text: CapLinked meets all requirements under HIPAA and HITECH standards
    type: compliance
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: platform
    source: https://www.caplinked.com/security/
    text: Our platform is PCI SAQ-D compliant
    type: compliance (SAQ-D)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: U.S. government clients, NIST SP 800-53 controls
    source: https://www.caplinked.com/security/
    text: CapLinked meets all Federal Information Security Management Act (FISMA) requirements by implementing NIST SP 800-53 controls
    type: compliance (FISMA)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: cross-border data transfers
    source: https://www.caplinked.com/security/
    text: We comply with the EU-U.S. Privacy Shield framework
    type: framework compliance (EU-U.S. Privacy Shield)
  trust_center:
    url: https://caplinked.com/security/
frameworks:
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
name: Caplinked
provenance_date: '2026-11-09'
provider_name: Caplinked
provider_slug: caplinked
slug: caplinked-compliance
source_date: '2026-11-09'
source_filename: caplinked-compliance.yml
source_heading: Compliance
source_page: https://caplinked.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Caplinked\naid: caplinked\nurl: https://caplinked.com/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/caplinked-trust-center.yml\n  sources:\n  - https://caplinked.com/security/\n  - https://www.caplinked.com/security/\ntrust_center:\n  url: https://caplinked.com/security/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Your data is hosted on ISO 27001-compliant servers, ensuring global standards for security, availability,\n    and privacy are upheld at every moment.\n- framework: SOC2\n  type:\
  \ independent assessment\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CapLinked has been independently assessed to meet SOC 2 standards, implementing industry-leading practices\n    for risk management, access control, system monitoring, and data handling.\n- framework: other\n  type: framework compliance (EU-U.S. Privacy Shield)\n  scope: cross-border data transfers\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We comply with the EU-U.S. Privacy Shield framework, ensuring your cross-border data transfers meet the\n    highest standards of privacy and protection as defined by European Commission regulations and U.S. Department\n    of Commerce principles.\n- framework: HIPAA\n  type: compliance claim\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CapLinked meets all requirements under HIPAA and HITECH standards, making it a reliable choice for organizations\n    in healthcare.\n- framework:\
  \ PCI-DSS\n  type: compliance claim (SAQ-D)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our platform is PCI SAQ-D compliant, providing a secure environment for organizations that process credit\n    card and other financial information.\n- framework: other\n  type: compliance claim (FISMA)\n  scope: U.S. government clients\n  period: null\n  issuer: null\n  report_access: unstated\n  text: For our U.S. government clients, CapLinked meets all Federal Information Security Management Act (FISMA)\n    requirements by implementing NIST SP 800-53 controls\n- framework: other\n  type: compliance claim (CMMC)\n  scope: VDR product\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CMMC Compliant VDR\n- framework: ISO27001\n  type: certification\n  scope: hosting servers / platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Your data is hosted on ISO 27001-compliant servers\n  source: https://www.caplinked.com/security/\n\
  - framework: SOC2\n  type: independent assessment\n  scope: CapLinked platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CapLinked has been independently assessed to meet SOC 2 standards\n  source: https://www.caplinked.com/security/\n- framework: HIPAA\n  type: compliance\n  scope: CapLinked platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CapLinked meets all requirements under HIPAA and HITECH standards\n  source: https://www.caplinked.com/security/\n- framework: PCI-DSS\n  type: compliance (SAQ-D)\n  scope: platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our platform is PCI SAQ-D compliant\n  source: https://www.caplinked.com/security/\n- framework: other\n  type: compliance (FISMA)\n  scope: U.S. government clients, NIST SP 800-53 controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CapLinked meets all Federal Information Security Management Act (FISMA) requirements by implementing\
  \ NIST\n    SP 800-53 controls\n  source: https://www.caplinked.com/security/\n- framework: other\n  type: framework compliance (EU-U.S. Privacy Shield)\n  scope: cross-border data transfers\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We comply with the EU-U.S. Privacy Shield framework\n  source: https://www.caplinked.com/security/\n"
source_yaml_url: https://artifacts.apis.io/caplinked/compliance/caplinked-compliance.yml
stated_fields:
- attestations
summary_line: 13 quoted statements, read from Caplinked's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Virtual Data Room
- Document Security
- File Sharing
- Due Diligence
- Mergers and Acquisitions
- Digital Rights Management
- Compliance
- Security
---
