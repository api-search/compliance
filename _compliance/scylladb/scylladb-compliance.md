---
api_specs:
- filename: scylladb-account-api-openapi.yml
  format: yaml
  label: ScyllaDB Account API
  slug: scylladb-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scylladb/openapi/scylladb-account-api-openapi.yml
- filename: scylladb-account-cluster-network-api-openapi.yml
  format: yaml
  label: ScyllaDB Account Cluster Network API
  slug: scylladb-account-cluster-network-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scylladb/openapi/scylladb-account-cluster-network-api-openapi.yml
- filename: scylladb-account-network-cluster-connection-api-openapi.yml
  format: yaml
  label: ScyllaDB Account network cluster connection API
  slug: scylladb-account-network-cluster-connection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scylladb/openapi/scylladb-account-network-cluster-connection-api-openapi.yml
- filename: scylladb-cluster-api-openapi.yml
  format: yaml
  label: ScyllaDB Cluster API
  slug: scylladb-cluster-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scylladb/openapi/scylladb-cluster-api-openapi.yml
- filename: scylladb-cluster-request-api-openapi.yml
  format: yaml
  label: ScyllaDB Cluster Request API
  slug: scylladb-cluster-request-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scylladb/openapi/scylladb-cluster-request-api-openapi.yml
- filename: scylladb-deployment-api-openapi.yml
  format: yaml
  label: ScyllaDB Deployment API
  slug: scylladb-deployment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scylladb/openapi/scylladb-deployment-api-openapi.yml
- filename: scylladb-pricing-api-openapi.yml
  format: yaml
  label: ScyllaDB Pricing API
  slug: scylladb-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scylladb/openapi/scylladb-pricing-api-openapi.yml
- filename: scylladb-vector-search-api-openapi.yml
  format: yaml
  label: ScyllaDB Vector Search API
  slug: scylladb-vector-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scylladb/openapi/scylladb-vector-search-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: not stated
    text: 'ScyllaDB has been certified to be compliant with the following standards: SOC 2 PCI-DSS ISO 27001 ISO 27017 ISO 27018'
    type: certification
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: not stated
    text: 'ScyllaDB has been certified to be compliant with the following standards: SOC 2 PCI-DSS ISO 27001 ISO 27017 ISO 27018'
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: not stated
    text: 'ScyllaDB has been certified to be compliant with the following standards: SOC 2 PCI-DSS ISO 27001 ISO 27017 ISO 27018'
    type: certification
  - framework: ISO27017
    issuer: null
    period: null
    report_access: unstated
    scope: not stated
    text: 'ScyllaDB has been certified to be compliant with the following standards: SOC 2 PCI-DSS ISO 27001 ISO 27017 ISO 27018'
    type: certification
  - framework: ISO27018
    issuer: null
    period: null
    report_access: unstated
    scope: not stated
    text: 'ScyllaDB has been certified to be compliant with the following standards: SOC 2 PCI-DSS ISO 27001 ISO 27017 ISO 27018'
    type: certification
  trust_center:
    url: https://www.scylladb.com/trust-center/
frameworks:
- ISO27001
- ISO27017
- ISO27018
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: ScyllaDB
provenance_date: '2026-11-10'
provider_name: ScyllaDB
provider_slug: scylladb
slug: scylladb-compliance
source_date: '2026-11-10'
source_filename: scylladb-compliance.yml
source_heading: Compliance
source_page: https://www.scylladb.com/trust-center/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: ScyllaDB\naid: scylladb\nurl: https://www.scylladb.com/trust-center/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/scylladb-trust-center.yml\ntrust_center:\n  url: https://www.scylladb.com/trust-center/\nattestations:\n- framework: SOC2\n  type: certification\n  scope: not stated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'ScyllaDB has been certified to be compliant with the following standards: SOC 2 PCI-DSS ISO 27001 ISO 27017\n    ISO 27018'\n- framework: PCI-DSS\n  type: certification\n  scope: not stated\n  period: null\n  issuer: null\n  report_access: unstated\n  text:\
  \ 'ScyllaDB has been certified to be compliant with the following standards: SOC 2 PCI-DSS ISO 27001 ISO 27017\n    ISO 27018'\n- framework: ISO27001\n  type: certification\n  scope: not stated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'ScyllaDB has been certified to be compliant with the following standards: SOC 2 PCI-DSS ISO 27001 ISO 27017\n    ISO 27018'\n- framework: ISO27017\n  type: certification\n  scope: not stated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'ScyllaDB has been certified to be compliant with the following standards: SOC 2 PCI-DSS ISO 27001 ISO 27017\n    ISO 27018'\n- framework: ISO27018\n  type: certification\n  scope: not stated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'ScyllaDB has been certified to be compliant with the following standards: SOC 2 PCI-DSS ISO 27001 ISO 27017\n    ISO 27018'\n"
source_yaml_url: https://artifacts.apis.io/scylladb/compliance/scylladb-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from ScyllaDB's own page on 2026-11-10.
synthetic: false
tags:
- Database
- NoSQL
- Cassandra Compatible
- DynamoDB Compatible
- Distributed Database
- Real-Time
- Vector Search
- Cloud Database
---
