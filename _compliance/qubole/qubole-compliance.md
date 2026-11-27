---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC2® SOC for Service Organizations (SSAE-18) Type II Report
    type: SOC for Service Organizations (SSAE-18) Type II Report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: QDS Health Cloud
    text: HIPAA Compliance Qubole Service Offering QDS Health Cloud
    type: HIPAA Compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliance General Data Protection Regulation
    type: GDPR Compliance
  trust_center:
    url: https://www.qubole.com/products/trust
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Qubole
provenance_date: '2026-11-10'
provider_name: Qubole
provider_slug: qubole
slug: qubole-compliance
source_date: '2026-11-10'
source_filename: qubole-compliance.yml
source_heading: Compliance
source_page: https://www.qubole.com/products/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Qubole\naid: qubole\nurl: https://www.qubole.com/products/trust\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.qubole.com/products/trust\nattestations:\n- framework: SOC2\n  type: SOC for Service Organizations (SSAE-18) Type II Report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC2® SOC for Service Organizations (SSAE-18) Type II Report\n- framework: HIPAA\n  type: HIPAA Compliance\n  scope: QDS Health Cloud\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Compliance Qubole Service Offering QDS Health Cloud\n- framework: GDPR\n  type:\
  \ GDPR Compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliance General Data Protection Regulation\n"
source_yaml_url: https://artifacts.apis.io/qubole/compliance/qubole-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Qubole's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- Data Lake
- Big Data
- Analytics
- Spark
- Presto
- Hive
- Airflow
- Machine Learning
- Cloud
- Data Engineering
---
