---
claim_count: 15
description: ''
doc:
  attestations:
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: and we are officially FedRAMP High Authorized in the FedRAMP Marketplace.
    type: authorization
  - framework: SOC2
    issuer: independent certified auditor
    period: null
    report_access: unstated
    scope: control environment
    text: Andesite has completed its SOC 2 Type 2 audit of our control environment via an independent assessment by a certified auditor.
    type: audit
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: information security management system
    text: Andesite complies with ISO 27001:2022 information security management system requirements, and continuously performs internal assessments against it.
    type: compliance
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: privacy information management system
    text: Andesite continuously monitors its controls and complies with ISO 27701:2019 privacy information management system requirements.
    type: compliance
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: artificial intelligence management system
    text: In addition to NIST AI RMF, Andesite continuously monitors using ISO 42001:2023 controls for our artificial intelligence management system.
    type: compliance
  - framework: HITRUST
    issuer: third-party audit
    period: null
    report_access: unstated
    scope: HITRUST CSF (e1) and AI Security Assessment
    text: Andesite is HITRUST CSF (e1) and AI Security Assessment certified through a third-party audit.
    type: certification
  - framework: PCI-DSS
    issuer: third-party independent assessor
    period: null
    report_access: unstated
    scope: PCI DSS 4.0
    text: We undergo a third-party independent assessment and provide our Attestation of Compliance in our Trust Center.
    type: assessment
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Business Associate
    text: Andesite complies with HIPAA and continually monitors our security and privacy controls appropriate for a Business Associate.
    type: compliance
  - framework: CSA-STAR
    issuer: third-party assessor
    period: null
    report_access: unstated
    scope: CSA STAR Level 2 and CSA AI-STAR Level 2
    text: Andesite completed its third-party CSA STAR Level 2 assessment and is among the first companies to achieve the new CSA AI-STAR Level 2.
    type: assessment
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: CCPA regulation
    text: we perform continuous internal auditing against the CCPA regulation.
    type: internal audit
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://andesite.ai/
    text: Andesite has achieved FedRAMP Certified Class D (High) status and is available in the FedRAMP Marketplace.
    type: FedRAMP Certified Class D (High)
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://andesite.ai/
    text: Protect Your Organization From FedRAMP High Authorized to SOC 2 Type II
    type: SOC 2 Type II
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://andesite.ai/
    text: CSA AI Trustworthy Pledge
    type: CSA AI Trustworthy Pledge
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://andesite.ai/
    text: CSA Trusted Cloud Provider
    type: CSA Trusted Cloud Provider
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://andesite.ai/
    text: CISA Secure by Design Pledge
    type: CISA Secure by Design Pledge
  trust_center:
    url: https://compliancehigh.andesite.ai/home
frameworks:
- CCPA
- CSA-STAR
- FedRAMP
- HIPAA
- HITRUST
- ISO27001
- ISO27701
- ISO42001
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Andesite
provenance_date: '2026-11-09'
provider_name: Andesite
provider_slug: andesite
slug: andesite-compliance
source_date: '2026-11-09'
source_filename: andesite-compliance.yml
source_heading: Compliance
source_page: https://compliancehigh.andesite.ai/home
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Andesite\naid: andesite\nurl: https://compliancehigh.andesite.ai/home\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/andesite-trust-center.yml\n  sources:\n  - https://andesite.ai/\n  - https://compliancehigh.andesite.ai/home\ntrust_center:\n  url: https://compliancehigh.andesite.ai/home\nattestations:\n- framework: FedRAMP\n  type: authorization\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: and we are officially FedRAMP High Authorized in the FedRAMP Marketplace.\n- framework: SOC2\n  type: audit\n  scope: control environment\n  period: null\n  issuer: independent\
  \ certified auditor\n  report_access: unstated\n  text: Andesite has completed its SOC 2 Type 2 audit of our control environment via an independent assessment by\n    a certified auditor.\n- framework: ISO27001\n  type: compliance\n  scope: information security management system\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Andesite complies with ISO 27001:2022 information security management system requirements, and continuously\n    performs internal assessments against it.\n- framework: ISO27701\n  type: compliance\n  scope: privacy information management system\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Andesite continuously monitors its controls and complies with ISO 27701:2019 privacy information management\n    system requirements.\n- framework: ISO42001\n  type: compliance\n  scope: artificial intelligence management system\n  period: null\n  issuer: null\n  report_access: unstated\n  text: In addition to NIST AI RMF, Andesite continuously\
  \ monitors using ISO 42001:2023 controls for our artificial\n    intelligence management system.\n- framework: HITRUST\n  type: certification\n  scope: HITRUST CSF (e1) and AI Security Assessment\n  period: null\n  issuer: third-party audit\n  report_access: unstated\n  text: Andesite is HITRUST CSF (e1) and AI Security Assessment certified through a third-party audit.\n- framework: PCI-DSS\n  type: assessment\n  scope: PCI DSS 4.0\n  period: null\n  issuer: third-party independent assessor\n  report_access: unstated\n  text: We undergo a third-party independent assessment and provide our Attestation of Compliance in our Trust Center.\n- framework: HIPAA\n  type: compliance\n  scope: Business Associate\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Andesite complies with HIPAA and continually monitors our security and privacy controls appropriate for\n    a Business Associate.\n- framework: CSA-STAR\n  type: assessment\n  scope: CSA STAR Level 2 and CSA AI-STAR Level\
  \ 2\n  period: null\n  issuer: third-party assessor\n  report_access: unstated\n  text: Andesite completed its third-party CSA STAR Level 2 assessment and is among the first companies to achieve\n    the new CSA AI-STAR Level 2.\n- framework: CCPA\n  type: internal audit\n  scope: CCPA regulation\n  period: null\n  issuer: null\n  report_access: unstated\n  text: we perform continuous internal auditing against the CCPA regulation.\n- framework: FedRAMP\n  type: FedRAMP Certified Class D (High)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Andesite has achieved FedRAMP Certified Class D (High) status and is available in the FedRAMP Marketplace.\n  source: https://andesite.ai/\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Protect Your Organization From FedRAMP High Authorized to SOC 2 Type II\n  source: https://andesite.ai/\n- framework: other\n  type: CSA AI Trustworthy Pledge\n\
  \  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CSA AI Trustworthy Pledge\n  source: https://andesite.ai/\n- framework: other\n  type: CSA Trusted Cloud Provider\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CSA Trusted Cloud Provider\n  source: https://andesite.ai/\n- framework: other\n  type: CISA Secure by Design Pledge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CISA Secure by Design Pledge\n  source: https://andesite.ai/\n"
source_yaml_url: https://artifacts.apis.io/andesite/compliance/andesite-compliance.yml
stated_fields:
- attestations
summary_line: 15 quoted statements, read from Andesite's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Defense Government
- Cybersecurity
- Security Operations
- Artificial Intelligence
- Threat Detection
- SOC
- Compliance
---
