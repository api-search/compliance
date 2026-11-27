---
claim_count: 10
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 1 and Type 2
    type: Type 1 and Type 2
  - framework: SOC3
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 3
    type: report
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI DSS
    type: compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA COMPLIANT
    type: compliance
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: compliance
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: High
    text: FedRAMP High
    type: authorization
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: NIS 2
    type: compliance
  - framework: IRAP
    issuer: null
    period: null
    report_access: unstated
    scope: PROTECTED level
    text: IRAP Readiness Assessed – PROTECTED Level
    type: readiness assessment
  trust_center:
    url: https://trust.tungstenautomation.com/
frameworks:
- CCPA
- FedRAMP
- GDPR
- HIPAA
- IRAP
- ISO27001
- PCI-DSS
- SOC2
- SOC3
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: ReadSoft
provenance_date: '2026-11-10'
provider_name: ReadSoft
provider_slug: readsoft
slug: readsoft-compliance
source_date: '2026-11-10'
source_filename: readsoft-compliance.yml
source_heading: Compliance
source_page: https://trust.tungstenautomation.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: ReadSoft\naid: readsoft\nurl: https://trust.tungstenautomation.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/readsoft-trust-center.yml\ntrust_center:\n  url: https://trust.tungstenautomation.com/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022\n- framework: SOC2\n  type: Type 1 and Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 1 and Type 2\n- framework: SOC3\n  type: report\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: SOC 3\n- framework: PCI-DSS\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: CCPA\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA COMPLIANT\n- framework: HIPAA\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n- framework: FedRAMP\n  type: authorization\n  scope: High\n  period: null\n  issuer: null\n  report_access: unstated\n  text: FedRAMP High\n- framework: other\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: NIS 2\n- framework: IRAP\n  type: readiness assessment\n  scope: PROTECTED level\n  period: null\n  issuer: null\n  report_access: unstated\n  text: IRAP Readiness Assessed – PROTECTED\
  \ Level\n"
source_yaml_url: https://artifacts.apis.io/readsoft/compliance/readsoft-compliance.yml
stated_fields:
- attestations
summary_line: 10 quoted statements, read from ReadSoft's own page on 2026-11-10.
synthetic: false
tags:
- Accounts Payable
- Business Process Automation
- Document Processing
- Enterprise Software
- Invoice Processing
- OCR
- Capture
---
