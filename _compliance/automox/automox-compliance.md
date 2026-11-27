---
claim_count: 6
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: 080124-073125
    report_access: on_request
    scope: null
    text: 26083 FINAL Automox 080124-073125 SOC 2 Type 2 (2).pdf
    type: SOC 2 Type 2 report
  - framework: SOC3
    issuer: null
    period: 080124-073125
    report_access: public
    scope: null
    text: 26083 FINAL Automox 080124-073125 SOC 3.pdf
    type: SOC 3 report
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CSA STAR Level 1
    type: CSA STAR Level 1
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: null
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: PCI-DSS-v4-0-1-AOC-for-SAQ-D-Service-Provider-r1-signed.pdf
    type: PCI DSS v4.0.1 Attestation of Compliance for SAQ D Service Provider
  - framework: other
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: TX-RAMP Level 2 Certificate Automox.pdf
    type: TX-RAMP Level 2 Certificate
  trust_center:
    url: https://security.automox.com/
frameworks:
- CSA-STAR
- GDPR
- PCI-DSS
- SOC2
- SOC3
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Automox
provenance_date: '2026-11-09'
provider_name: Automox
provider_slug: automox
slug: automox-compliance
source_date: '2026-11-09'
source_filename: automox-compliance.yml
source_heading: Compliance
source_page: https://security.automox.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Automox\naid: automox\nurl: https://security.automox.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/automox-trust-center.yml\ntrust_center:\n  url: https://security.automox.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: null\n  period: 080124-073125\n  issuer: null\n  report_access: on_request\n  text: 26083 FINAL Automox 080124-073125 SOC 2 Type 2 (2).pdf\n- framework: SOC3\n  type: SOC 3 report\n  scope: null\n  period: 080124-073125\n  issuer: null\n  report_access: public\n  text: 26083 FINAL Automox 080124-073125 SOC 3.pdf\n- framework: CSA-STAR\n  type: CSA\
  \ STAR Level 1\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CSA STAR Level 1\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: PCI-DSS\n  type: PCI DSS v4.0.1 Attestation of Compliance for SAQ D Service Provider\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: PCI-DSS-v4-0-1-AOC-for-SAQ-D-Service-Provider-r1-signed.pdf\n- framework: other\n  type: TX-RAMP Level 2 Certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: TX-RAMP Level 2 Certificate Automox.pdf\n"
source_yaml_url: https://artifacts.apis.io/automox/compliance/automox-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Automox's own page on 2026-11-09.
synthetic: false
tags:
- Endpoint Management
- Patch Management
- IT Operations
- Device Management
- Configuration Management
- Security
---
