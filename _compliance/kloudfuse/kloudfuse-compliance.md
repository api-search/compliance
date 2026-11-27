---
api_specs:
- filename: kloudfuse-cardinality-explorer-api-openapi.yml
  format: yaml
  label: Kloudfuse Cardinality Explorer API
  slug: kloudfuse-cardinality-explorer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kloudfuse/openapi/kloudfuse-cardinality-explorer-api-openapi.yml
- filename: kloudfuse-events-api-openapi.yml
  format: yaml
  label: Kloudfuse Events API
  slug: kloudfuse-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kloudfuse/openapi/kloudfuse-events-api-openapi.yml
- filename: kloudfuse-folders-api-openapi.yml
  format: yaml
  label: Kloudfuse Folders API
  slug: kloudfuse-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kloudfuse/openapi/kloudfuse-folders-api-openapi.yml
- filename: kloudfuse-hydration-api-openapi.yml
  format: yaml
  label: Kloudfuse Hydration API
  slug: kloudfuse-hydration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kloudfuse/openapi/kloudfuse-hydration-api-openapi.yml
- filename: kloudfuse-ingester-api-openapi.yml
  format: yaml
  label: Kloudfuse Ingester API
  slug: kloudfuse-ingester-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kloudfuse/openapi/kloudfuse-ingester-api-openapi.yml
- filename: kloudfuse-metrics-api-openapi.yml
  format: yaml
  label: Kloudfuse Metrics API
  slug: kloudfuse-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kloudfuse/openapi/kloudfuse-metrics-api-openapi.yml
- filename: kloudfuse-policies-api-openapi.yml
  format: yaml
  label: Kloudfuse Policies API
  slug: kloudfuse-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kloudfuse/openapi/kloudfuse-policies-api-openapi.yml
- filename: kloudfuse-teams-api-openapi.yml
  format: yaml
  label: Kloudfuse Teams API
  slug: kloudfuse-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kloudfuse/openapi/kloudfuse-teams-api-openapi.yml
- filename: kloudfuse-traces-api-openapi.yml
  format: yaml
  label: Kloudfuse Traces API
  slug: kloudfuse-traces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kloudfuse/openapi/kloudfuse-traces-api-openapi.yml
- filename: kloudfuse-graph-ql-api-openapi.yml
  format: yaml
  label: Kloudfuse Graph QL API
  slug: kloudfuse-graph-ql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kloudfuse/openapi/kloudfuse-graph-ql-api-openapi.yml
claim_count: 7
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI DSS V4.0.1
    type: null
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: null
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2
    type: null
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: null
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022
    type: null
  - framework: SOC2
    issuer: null
    period: Current
    report_access: nda
    scope: null
    source: https://www.kloudfuse.com/security
    text: SOC 2 Type II Current
    type: Type II
  - framework: ISO27001
    issuer: null
    period: Current
    report_access: unstated
    scope: null
    source: https://www.kloudfuse.com/security
    text: ISO/IEC 27001:2022 Current
    type: ISO/IEC 27001:2022
  trust_center:
    url: https://trust.kloudfuse.com/
frameworks:
- GDPR
- HIPAA
- ISO27001
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Kloudfuse
provenance_date: '2026-11-09'
provider_name: Kloudfuse
provider_slug: kloudfuse
slug: kloudfuse-compliance
source_date: '2026-11-09'
source_filename: kloudfuse-compliance.yml
source_heading: Compliance
source_page: https://trust.kloudfuse.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Kloudfuse\naid: kloudfuse\nurl: https://trust.kloudfuse.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://trust.kloudfuse.com/\n  - https://www.kloudfuse.com/security\ntrust_center:\n  url: https://trust.kloudfuse.com/\nattestations:\n- framework: PCI-DSS\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS V4.0.1\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n- framework: SOC2\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC\
  \ 2\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: ISO27001\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: Current\n  issuer: null\n  report_access: nda\n  text: SOC 2 Type II Current\n  source: https://www.kloudfuse.com/security\n- framework: ISO27001\n  type: ISO/IEC 27001:2022\n  scope: null\n  period: Current\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 27001:2022 Current\n  source: https://www.kloudfuse.com/security\n"
source_yaml_url: https://artifacts.apis.io/kloudfuse/compliance/kloudfuse-compliance.yml
stated_fields:
- attestations
summary_line: 7 quoted statements, read from Kloudfuse's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Observability
- Monitoring
- Logs
- Metrics
- Tracing
- OpenTelemetry
- MCP
---
