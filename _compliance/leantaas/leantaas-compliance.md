---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC2 Type 2 Attestation
    type: SOC2 Type 2 Attestation
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 HIPAA TX-RAMP CCPA COMPLIANT CCPA HITRUST
    type: HIPAA compliance
  - framework: HITRUST
    issuer: null
    period: '2026'
    report_access: unstated
    scope: null
    text: HITRUST r2 Certification Letter 2026
    type: HITRUST r2 Certification Letter
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA COMPLIANT
    type: CCPA compliant
  trust_center:
    url: https://trust.leantaas.com/
frameworks:
- CCPA
- HIPAA
- HITRUST
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: LeanTaaS
provenance_date: '2026-11-09'
provider_name: LeanTaaS
provider_slug: leantaas
slug: leantaas-compliance
source_date: '2026-11-09'
source_filename: leantaas-compliance.yml
source_heading: Compliance
source_page: https://trust.leantaas.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: LeanTaaS\naid: leantaas\nurl: https://trust.leantaas.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.leantaas.com/\nattestations:\n- framework: SOC2\n  type: SOC2 Type 2 Attestation\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC2 Type 2 Attestation\n- framework: HIPAA\n  type: HIPAA compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 HIPAA TX-RAMP CCPA COMPLIANT CCPA HITRUST\n- framework: HITRUST\n  type: HITRUST r2 Certification Letter\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access:\
  \ unstated\n  text: HITRUST r2 Certification Letter 2026\n- framework: CCPA\n  type: CCPA compliant\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA COMPLIANT\n"
source_yaml_url: https://artifacts.apis.io/leantaas/compliance/leantaas-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from LeanTaaS's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Health Systems
- Hospital Operations
- Capacity Management
- Artificial Intelligence
- Machine Learning
- Predictive Analytics
- Scheduling
- Software-as-a-Service
---
