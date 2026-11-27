---
api_specs:
- filename: anaplaninc
  format: yaml
  label: Anaplan Integration API v2.0
  slug: anaplan-integration-api-v20
  spec_type: Postman
  url: https://www.postman.com/anaplaninc
claim_count: 11
description: ''
doc:
  attestations:
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 1 Type 2, SOC 2 Type 2
    type: Type 2
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 1 Type 2, SOC 2 Type 2
    type: Type 2
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO-27001, 27017, 27018, 27701, & 42001
    type: certification
  - framework: ISO27017
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO-27001, 27017, 27018, 27701, & 42001
    type: certification
  - framework: ISO27018
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO-27001, 27017, 27018, 27701, & 42001
    type: certification
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO-27001, 27017, 27018, 27701, & 42001
    type: certification
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO-27001, 27017, 27018, 27701, & 42001
    type: certification
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CSA STAR Level 1
    type: CSA STAR Level 1
  - framework: CyberEssentials
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Cyber Essentials
    type: certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: TX-RAMP
    type: TX-RAMP
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: EU - US DPF
    type: EU-US DPF
  trust_center:
    url: https://trust.anaplan.com/
frameworks:
- CSA-STAR
- CyberEssentials
- ISO27001
- ISO27017
- ISO27018
- ISO27701
- ISO42001
- SOC1
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Anaplan
provenance_date: '2026-11-09'
provider_name: Anaplan
provider_slug: anaplan
slug: anaplan-compliance
source_date: '2026-11-09'
source_filename: anaplan-compliance.yml
source_heading: Compliance
source_page: https://trust.anaplan.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Anaplan\naid: anaplan\nurl: https://trust.anaplan.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/anaplan-trust-center.yml\ntrust_center:\n  url: https://trust.anaplan.com/\nattestations:\n- framework: SOC1\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 1 Type 2, SOC 2 Type 2\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 1 Type 2, SOC 2 Type 2\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: ISO-27001, 27017, 27018, 27701, & 42001\n- framework: ISO27017\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO-27001, 27017, 27018, 27701, & 42001\n- framework: ISO27018\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO-27001, 27017, 27018, 27701, & 42001\n- framework: ISO27701\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO-27001, 27017, 27018, 27701, & 42001\n- framework: ISO42001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO-27001, 27017, 27018, 27701, & 42001\n- framework: CSA-STAR\n  type: CSA STAR Level 1\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CSA STAR Level 1\n- framework: CyberEssentials\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: Cyber Essentials\n- framework: other\n  type: TX-RAMP\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TX-RAMP\n- framework: other\n  type: EU-US DPF\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: EU - US DPF\n"
source_yaml_url: https://artifacts.apis.io/anaplan/compliance/anaplan-compliance.yml
stated_fields:
- attestations
summary_line: 11 quoted statements, read from Anaplan's own page on 2026-11-09.
synthetic: false
tags:
- Connected Planning
- Enterprise Planning
- FP&A
- Supply Chain
- Sales Planning
- Financial Consolidation
- SCIM
- REST
---
