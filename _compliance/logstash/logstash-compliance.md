---
claim_count: 12
description: ''
doc:
  attestations:
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: High
    text: FedRAMP High
    type: certification
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: Moderate
    text: FedRAMP Moderate
    type: certification
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI DSS
    type: certification
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CSA STAR
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO/IEC 27001
    type: certification
  - framework: ISO27017
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO/IEC 27017
    type: certification
  - framework: ISO27018
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO/IEC 27018
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2
    type: report
  - framework: SOC3
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 3
    type: report
  - framework: TISAX
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: TISAX
    type: certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: certification
  - framework: CyberEssentials
    issuer: null
    period: null
    report_access: unstated
    scope: Plus
    text: Cyber Essentials Plus
    type: certification
  trust_center:
    url: https://www.elastic.co/trust
frameworks:
- CSA-STAR
- CyberEssentials
- FedRAMP
- HIPAA
- ISO27001
- ISO27017
- ISO27018
- PCI-DSS
- SOC2
- SOC3
- TISAX
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Logstash
provenance_date: '2026-11-09'
provider_name: Logstash
provider_slug: logstash
slug: logstash-compliance
source_date: '2026-11-09'
source_filename: logstash-compliance.yml
source_heading: Compliance
source_page: https://www.elastic.co/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Logstash\naid: logstash\nurl: https://www.elastic.co/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/logstash-trust-center.yml\ntrust_center:\n  url: https://www.elastic.co/trust\nattestations:\n- framework: FedRAMP\n  type: certification\n  scope: High\n  period: null\n  issuer: null\n  report_access: unstated\n  text: FedRAMP High\n- framework: FedRAMP\n  type: certification\n  scope: Moderate\n  period: null\n  issuer: null\n  report_access: unstated\n  text: FedRAMP Moderate\n- framework: PCI-DSS\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: PCI DSS\n- framework: CSA-STAR\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CSA STAR\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 27001\n- framework: ISO27017\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 27017\n- framework: ISO27018\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 27018\n- framework: SOC2\n  type: report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2\n- framework: SOC3\n  type: report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 3\n- framework: TISAX\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TISAX\n- framework: HIPAA\n  type: certification\n\
  \  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n- framework: CyberEssentials\n  type: certification\n  scope: Plus\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Cyber Essentials Plus\n"
source_yaml_url: https://artifacts.apis.io/logstash/compliance/logstash-compliance.yml
stated_fields:
- attestations
summary_line: 12 quoted statements, read from Logstash's own page on 2026-11-09.
synthetic: false
tags:
- Data Processing
- ETL
- Log Management
- Pipelines
---
