---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: A-LIGN
    period: null
    report_access: unstated
    scope: null
    text: Certified through an independent third-party audit with A-LIGN for ISO 27001.
    type: Certification
  - framework: SOC2
    issuer: A-LIGN
    period: null
    report_access: unstated
    scope: null
    text: Certified through an independent third-party audit with A-LIGN for SOC 2.
    type: Type 2 Certification
  - framework: PCI-DSS
    issuer: PCI Security Standards Council
    period: null
    report_access: unstated
    scope: Grafana Labs corporate environment for client payment processing
    text: Maintains PCI Compliance through third-party approved scanning vendors for the Grafana Labs corporate environment for client payment processing.
    type: Compliance maintenance through approved scanning vendors
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Data Processor Agreement (DPA) available
    type: Data Processor Agreement
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Completed CSA Security Trust Assurance and Risk (STAR) program.
    type: Completed STAR program
  trust_center:
    url: https://grafana.com/legal/security-compliance/
frameworks:
- CSA-STAR
- GDPR
- ISO27001
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Grafana Loki
provenance_date: '2026-11-09'
provider_name: Grafana Loki
provider_slug: grafana-loki
slug: grafana-loki-compliance
source_date: '2026-11-09'
source_filename: grafana-loki-compliance.yml
source_heading: Compliance
source_page: https://grafana.com/legal/security-compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Grafana Loki\naid: grafana-loki\nurl: https://grafana.com/legal/security-compliance/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://grafana.com/legal/security-compliance/\nattestations:\n- framework: ISO27001\n  type: Certification\n  scope: null\n  period: null\n  issuer: A-LIGN\n  report_access: unstated\n  text: Certified through an independent third-party audit with A-LIGN for ISO 27001.\n- framework: SOC2\n  type: Type 2 Certification\n  scope: null\n  period: null\n  issuer: A-LIGN\n  report_access: unstated\n  text: Certified through an independent third-party audit with A-LIGN for SOC 2.\n-\
  \ framework: PCI-DSS\n  type: Compliance maintenance through approved scanning vendors\n  scope: Grafana Labs corporate environment for client payment processing\n  period: null\n  issuer: PCI Security Standards Council\n  report_access: unstated\n  text: Maintains PCI Compliance through third-party approved scanning vendors for the Grafana Labs corporate environment\n    for client payment processing.\n- framework: GDPR\n  type: Data Processor Agreement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Data Processor Agreement (DPA) available\n- framework: CSA-STAR\n  type: Completed STAR program\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Completed CSA Security Trust Assurance and Risk (STAR) program.\n"
source_yaml_url: https://artifacts.apis.io/grafana-loki/compliance/grafana-loki-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Grafana Loki's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Logs
- Logging
- Log Aggregation
- Observability
- Monitoring
- Open Source
- LogQL
- OpenTelemetry
- Telemetry
- Kubernetes
- Cloud-Native
---
