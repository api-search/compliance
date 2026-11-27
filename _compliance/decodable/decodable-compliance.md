---
api_specs:
- filename: decodable-connections-api-openapi.yml
  format: yaml
  label: Decodable Connections API
  slug: decodable-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decodable/openapi/decodable-connections-api-openapi.yml
- filename: decodable-pipelines-api-openapi.yml
  format: yaml
  label: Decodable Pipelines API
  slug: decodable-pipelines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decodable/openapi/decodable-pipelines-api-openapi.yml
- filename: decodable-resources-api-openapi.yml
  format: yaml
  label: Decodable Resources API
  slug: decodable-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decodable/openapi/decodable-resources-api-openapi.yml
- filename: decodable-secrets-api-openapi.yml
  format: yaml
  label: Decodable Secrets API
  slug: decodable-secrets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decodable/openapi/decodable-secrets-api-openapi.yml
- filename: decodable-streams-api-openapi.yml
  format: yaml
  label: Decodable Streams API
  slug: decodable-streams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decodable/openapi/decodable-streams-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Information Security Program
    text: Copies of Decodable's SOC 2 Type II report, HIPAA report, and Data Processing Addendum (GDPR) can be requested from security@decodable.co.
    type: SOC 2 Type II report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: Information Security Program
    text: Our Information Security Program is audited and complies with SOC2 Type II, HIPAA, and GDPR in accordance with AT-C 315.
    type: HIPAA report
  - framework: GDPR
    issuer: null
    period: null
    report_access: on_request
    scope: Information Security Program
    text: Copies of Decodable's SOC 2 Type II report, HIPAA report, and Data Processing Addendum (GDPR) can be requested from security@decodable.co.
    type: Data Processing Addendum (GDPR)
  trust_center:
    url: https://www.decodable.co/security
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Decodable
provenance_date: '2026-11-09'
provider_name: Decodable
provider_slug: decodable
slug: decodable-compliance
source_date: '2026-11-09'
source_filename: decodable-compliance.yml
source_heading: Compliance
source_page: https://www.decodable.co/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Decodable\naid: decodable\nurl: https://www.decodable.co/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/decodable-trust-center.yml\ntrust_center:\n  url: https://www.decodable.co/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: Information Security Program\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Copies of Decodable's SOC 2 Type II report, HIPAA report, and Data Processing Addendum (GDPR) can be requested\n    from security@decodable.co.\n- framework: HIPAA\n  type: HIPAA report\n  scope: Information Security Program\n  period:\
  \ null\n  issuer: null\n  report_access: on_request\n  text: Our Information Security Program is audited and complies with SOC2 Type II, HIPAA, and GDPR in accordance\n    with AT-C 315.\n- framework: GDPR\n  type: Data Processing Addendum (GDPR)\n  scope: Information Security Program\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Copies of Decodable's SOC 2 Type II report, HIPAA report, and Data Processing Addendum (GDPR) can be requested\n    from security@decodable.co.\n"
source_yaml_url: https://artifacts.apis.io/decodable/compliance/decodable-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Decodable's own page on 2026-11-09.
synthetic: false
tags:
- Stream Processing
- Apache Flink
- Debezium
- Real-Time Data
- Data Pipeline
- Change Data Capture
---
