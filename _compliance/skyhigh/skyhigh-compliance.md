---
api_specs:
- filename: skyhigh-tenant-api-openapi.yml
  format: yaml
  label: Skyhigh Security Tenant API
  slug: skyhigh-tenant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skyhigh/openapi/skyhigh-tenant-api-openapi.yml
claim_count: 9
description: ''
doc:
  attestations:
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: Skyhigh CASB, Skyhigh SWG for Cloud, DLP and Advanced DLP
    text: Skyhigh Cloud Access Security Broker (CASB), Skyhigh Secure Web Gateway (SWG) for Cloud, DLP and Advanced DLP have all been granted FedRAMP High Authorization
    type: authorization
  - framework: other
    issuer: DISA
    period: null
    report_access: unstated
    scope: DoD Impact Level 2 (IL2)
    text: Skyhigh Security has been granted a DoD Impact Level 2 (IL2) Provisional Authorization from DISA
    type: provisional authorization
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data protection
    text: Skyhigh Security implements appropriate technical and organizational measures to protect personal data in full conformity with GDPR requirements.
    type: compliance statement
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: complete SSE Cloud Platform
    text: Achieving SOC 2 Type II for the complete SSE Cloud Platform is a comprehensive process
    type: SOC 2 Type II
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: information security management system
    text: Skyhigh Security was the first Cloud Access Security Broker to attain ISO 27001 Certification
    type: certification
  - framework: IRAP
    issuer: null
    period: '2023'
    report_access: unstated
    scope: SSE at PROTECTED classification level
    text: Skyhigh SSE completed an IRAP assessment at the PROTECTED security classification level in 2023.
    type: assessment
  - framework: C5
    issuer: null
    period: '2026'
    report_access: unstated
    scope: Skyhigh SSE Portfolio
    text: Achieving milestones like IRAP 2026 and BSI C5 simultaneously demonstrates that Skyhigh Security is the partner governments and enterprises can rely on
    type: certification
  - framework: CSA-STAR
    issuer: Cloud Security Alliance
    period: null
    report_access: unstated
    scope: cloud security
    text: Skyhigh Security's CSA STAR Certification reinforces its leadership in cloud security
    type: STAR Level 1 certification
  - framework: CSA-STAR
    issuer: certified STAR auditor
    period: null
    report_access: unstated
    scope: Cloud Controls Matrix, 17 domains
    text: A certified STAR auditor has confirmed that Skyhigh Security's security controls across the 17 domains of the Cloud Controls Matrix are not only designed appropriately but operating effectively in practice
    type: STAR Level 2 third-party audit
  trust_center:
    url: https://www.skyhighsecurity.com/about/certification.html
frameworks:
- C5
- CSA-STAR
- FedRAMP
- GDPR
- IRAP
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Skyhigh Security
provenance_date: '2026-11-10'
provider_name: Skyhigh Security
provider_slug: skyhigh
slug: skyhigh-compliance
source_date: '2026-11-10'
source_filename: skyhigh-compliance.yml
source_heading: Compliance
source_page: https://www.skyhighsecurity.com/about/certification.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Skyhigh Security\naid: skyhigh\nurl: https://www.skyhighsecurity.com/about/certification.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.skyhighsecurity.com/about/certification.html\nattestations:\n- framework: FedRAMP\n  type: authorization\n  scope: Skyhigh CASB, Skyhigh SWG for Cloud, DLP and Advanced DLP\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Skyhigh Cloud Access Security Broker (CASB), Skyhigh Secure Web Gateway (SWG) for Cloud, DLP and Advanced\n    DLP have all been granted FedRAMP High Authorization\n- framework: other\n  type: provisional authorization\n\
  \  scope: DoD Impact Level 2 (IL2)\n  period: null\n  issuer: DISA\n  report_access: unstated\n  text: Skyhigh Security has been granted a DoD Impact Level 2 (IL2) Provisional Authorization from DISA\n- framework: GDPR\n  type: compliance statement\n  scope: personal data protection\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Skyhigh Security implements appropriate technical and organizational measures to protect personal data in\n    full conformity with GDPR requirements.\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: complete SSE Cloud Platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Achieving SOC 2 Type II for the complete SSE Cloud Platform is a comprehensive process\n- framework: ISO27001\n  type: certification\n  scope: information security management system\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Skyhigh Security was the first Cloud Access Security Broker to attain ISO 27001 Certification\n- framework:\
  \ IRAP\n  type: assessment\n  scope: SSE at PROTECTED classification level\n  period: '2023'\n  issuer: null\n  report_access: unstated\n  text: Skyhigh SSE completed an IRAP assessment at the PROTECTED security classification level in 2023.\n- framework: C5\n  type: certification\n  scope: Skyhigh SSE Portfolio\n  period: '2026'\n  issuer: null\n  report_access: unstated\n  text: Achieving milestones like IRAP 2026 and BSI C5 simultaneously demonstrates that Skyhigh Security is the\n    partner governments and enterprises can rely on\n- framework: CSA-STAR\n  type: STAR Level 1 certification\n  scope: cloud security\n  period: null\n  issuer: Cloud Security Alliance\n  report_access: unstated\n  text: Skyhigh Security's CSA STAR Certification reinforces its leadership in cloud security\n- framework: CSA-STAR\n  type: STAR Level 2 third-party audit\n  scope: Cloud Controls Matrix, 17 domains\n  period: null\n  issuer: certified STAR auditor\n  report_access: unstated\n  text: A certified\
  \ STAR auditor has confirmed that Skyhigh Security's security controls across the 17 domains of\n    the Cloud Controls Matrix are not only designed appropriately but operating effectively in practice\n"
source_yaml_url: https://artifacts.apis.io/skyhigh/compliance/skyhigh-compliance.yml
stated_fields:
- attestations
summary_line: 9 quoted statements, read from Skyhigh Security's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cybersecurity
- Security Service Edge
- CASB
- Secure Web Gateway
- Data Loss Prevention
- Cloud Security
- Zero Trust
- SASE
---
