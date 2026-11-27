---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Mouseflow platform
    text: Mouseflow - Type 2 SOC 2 - Confirmation of Engagement
    type: SOC 2 Type II
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Mouseflow
    text: Mouseflow PCI Attestation of Compliance
    type: PCI DSS attestation of compliance
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Google Cloud infrastructure
    text: ISO 27001 Certificate (Google Cloud)
    type: ISO 27001:2022 certificate (Google Cloud)
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR CCPA COMPLIANT
    type: GDPR compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA COMPLIANT
    type: CCPA compliance
  trust_center:
    url: https://trust.mouseflow.com/
frameworks:
- CCPA
- GDPR
- ISO27001
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Mouseflow
provenance_date: '2026-11-10'
provider_name: Mouseflow
provider_slug: mouseflow
slug: mouseflow-compliance
source_date: '2026-11-10'
source_filename: mouseflow-compliance.yml
source_heading: Compliance
source_page: https://trust.mouseflow.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Mouseflow\naid: mouseflow\nurl: https://trust.mouseflow.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/mouseflow-trust-center.yml\ntrust_center:\n  url: https://trust.mouseflow.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: Mouseflow platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Mouseflow - Type 2 SOC 2 - Confirmation of Engagement\n- framework: PCI-DSS\n  type: PCI DSS attestation of compliance\n  scope: Mouseflow\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Mouseflow PCI Attestation of Compliance\n- framework: ISO27001\n\
  \  type: ISO 27001:2022 certificate (Google Cloud)\n  scope: Google Cloud infrastructure\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 Certificate (Google Cloud)\n- framework: GDPR\n  type: GDPR compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR CCPA COMPLIANT\n- framework: CCPA\n  type: CCPA compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA COMPLIANT\n"
source_yaml_url: https://artifacts.apis.io/mouseflow/compliance/mouseflow-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Mouseflow's own page on 2026-11-10.
synthetic: false
tags:
- Company
---
