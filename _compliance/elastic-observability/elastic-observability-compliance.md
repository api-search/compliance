---
api_specs:
- filename: elastic-observability-server-info-api-openapi.yml
  format: yaml
  label: Elastic Observability Server Info API
  slug: elastic-observability-server-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/elastic-observability/openapi/elastic-observability-server-info-api-openapi.yml
- filename: elastic-observability-agent-config-api-openapi.yml
  format: yaml
  label: Elastic Observability agent config API
  slug: elastic-observability-agent-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/elastic-observability/openapi/elastic-observability-agent-config-api-openapi.yml
- filename: elastic-observability-event-intake-api-openapi.yml
  format: yaml
  label: Elastic Observability event intake API
  slug: elastic-observability-event-intake-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/elastic-observability/openapi/elastic-observability-event-intake-api-openapi.yml
- filename: elastic-observability-opentelemetry-intake-api-openapi.yml
  format: yaml
  label: Elastic Observability opentelemetry intake API
  slug: elastic-observability-opentelemetry-intake-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/elastic-observability/openapi/elastic-observability-opentelemetry-intake-api-openapi.yml
claim_count: 12
description: ''
doc:
  attestations:
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: FedRAMP High
    type: certification
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: FedRAMP Moderate
    type: certification
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: PCI DSS
    type: certification
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: CSA STAR
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: ISO/IEC 27001
    type: certification
  - framework: ISO27017
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: ISO/IEC 27017
    type: certification
  - framework: ISO27018
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: ISO/IEC 27018
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 2
    type: audit report
  - framework: TISAX
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: TISAX
    type: certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: HIPAA
    type: compliance
  - framework: CyberEssentials
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Cyber Essentials Plus
    type: certification
  - framework: IRAP
    issuer: null
    period: null
    report_access: on_request
    scope: Protected B
    text: 'IRAP Assessed: Protected B'
    type: assessment
  trust_center:
    url: https://www.elastic.co/trust
frameworks:
- CSA-STAR
- CyberEssentials
- FedRAMP
- HIPAA
- IRAP
- ISO27001
- ISO27017
- ISO27018
- PCI-DSS
- SOC2
- TISAX
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Elastic Observability
provenance_date: '2026-11-09'
provider_name: Elastic Observability
provider_slug: elastic-observability
slug: elastic-observability-compliance
source_date: '2026-11-09'
source_filename: elastic-observability-compliance.yml
source_heading: Compliance
source_page: https://www.elastic.co/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Elastic Observability\naid: elastic-observability\nurl: https://www.elastic.co/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/elastic-observability-trust-center.yml\ntrust_center:\n  url: https://www.elastic.co/trust\nattestations:\n- framework: FedRAMP\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: FedRAMP High\n- framework: FedRAMP\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: FedRAMP Moderate\n- framework: PCI-DSS\n  type: certification\n  scope: null\n  period: null\n\
  \  issuer: null\n  report_access: on_request\n  text: PCI DSS\n- framework: CSA-STAR\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: CSA STAR\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: ISO/IEC 27001\n- framework: ISO27017\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: ISO/IEC 27017\n- framework: ISO27018\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: ISO/IEC 27018\n- framework: SOC2\n  type: audit report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2\n- framework: TISAX\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: TISAX\n- framework: HIPAA\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ on_request\n  text: HIPAA\n- framework: CyberEssentials\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Cyber Essentials Plus\n- framework: IRAP\n  type: assessment\n  scope: Protected B\n  period: null\n  issuer: null\n  report_access: on_request\n  text: 'IRAP Assessed: Protected B'\n"
source_yaml_url: https://artifacts.apis.io/elastic-observability/compliance/elastic-observability-compliance.yml
stated_fields:
- attestations
summary_line: 12 quoted statements, read from Elastic Observability's own page on 2026-11-09.
synthetic: false
tags:
- AIOps
- Observability
- APM
- Logging
- Metrics
- Tracing
- OpenTelemetry
- Monitoring
- Telemetry
---
