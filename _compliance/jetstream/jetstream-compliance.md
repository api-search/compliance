---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: on_request
    scope: SAIG Platform
    text: JetStream is FedRAMP HIGH / Class D Certified
    type: certification (HIGH / Class D)
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: on_request
    scope: federal workloads
    text: is available to federal agencies and authorized partners through the FedRAMP Marketplace and on direct request
    type: authorization package (SSP, SAP, SAR, POA&M, ConMon)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: state, local, tribal, and territorial governments
    text: JetStream’s FedRAMP HIGH posture extends to GovRAMP through established reciprocity
    type: reciprocity (GovRAMP, formerly StateRAMP)
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We have achieved SOC 2 Type I and are actively pursuing SOC 2 Type II
    type: SOC 2 Type I achieved; Type II in progress
  trust_center:
    url: https://jetstream.security/trust-center/
frameworks:
- FedRAMP
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Jetstream
provenance_date: '2026-11-09'
provider_name: Jetstream
provider_slug: jetstream
slug: jetstream-compliance
source_date: '2026-11-09'
source_filename: jetstream-compliance.yml
source_heading: Compliance
source_page: https://jetstream.security/trust-center/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Jetstream\naid: jetstream\nurl: https://jetstream.security/trust-center/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/jetstream-trust-center.yml\ntrust_center:\n  url: https://jetstream.security/trust-center/\nattestations:\n- framework: FedRAMP\n  type: certification (HIGH / Class D)\n  scope: SAIG Platform\n  period: null\n  issuer: null\n  report_access: on_request\n  text: JetStream is FedRAMP HIGH / Class D Certified\n- framework: FedRAMP\n  type: authorization package (SSP, SAP, SAR, POA&M, ConMon)\n  scope: federal workloads\n  period: null\n  issuer: null\n  report_access: on_request\n \
  \ text: is available to federal agencies and authorized partners through the FedRAMP Marketplace and on direct request\n- framework: other\n  type: reciprocity (GovRAMP, formerly StateRAMP)\n  scope: state, local, tribal, and territorial governments\n  period: null\n  issuer: null\n  report_access: unstated\n  text: JetStream’s FedRAMP HIGH posture extends to GovRAMP through established reciprocity\n- framework: SOC2\n  type: SOC 2 Type I achieved; Type II in progress\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We have achieved SOC 2 Type I and are actively pursuing SOC 2 Type II\n"
source_yaml_url: https://artifacts.apis.io/jetstream/compliance/jetstream-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Jetstream's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- AI Governance
- AI Security
- AI Agents
- Runtime Governance
- Compliance
- FinOps
---
