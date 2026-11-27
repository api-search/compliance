---
api_specs:
- filename: elasticsearch-cat-api-openapi.yml
  format: yaml
  label: Elasticsearch Cat API
  slug: elasticsearch-cat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/elasticsearch/openapi/elasticsearch-cat-api-openapi.yml
- filename: elasticsearch-cluster-api-openapi.yml
  format: yaml
  label: Elasticsearch Cluster API
  slug: elasticsearch-cluster-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/elasticsearch/openapi/elasticsearch-cluster-api-openapi.yml
- filename: elasticsearch-document-api-openapi.yml
  format: yaml
  label: Elasticsearch Document API
  slug: elasticsearch-document-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/elasticsearch/openapi/elasticsearch-document-api-openapi.yml
- filename: elasticsearch-index-api-openapi.yml
  format: yaml
  label: Elasticsearch Index API
  slug: elasticsearch-index-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/elasticsearch/openapi/elasticsearch-index-api-openapi.yml
- filename: elasticsearch-search-api-openapi.yml
  format: yaml
  label: Elasticsearch Search API
  slug: elasticsearch-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/elasticsearch/openapi/elasticsearch-search-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: on_request
    scope: FedRAMP High
    text: 'FedRAMP High FedRAMP Moderate PCI DSS CSA STAR ISO/IEC 27001 ISO/IEC 27017 ISO/IEC 27018 SOC 2 SOC 3 TISAX HIPAA Cyber Essentials Plus IRAP Assessed: Protected B CyberGRX'
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: ISO/IEC 27001
    text: Our services are independently audited and certified to meet industry-leading compliance and privacy standards. View all certifications and request audit reports
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: SOC 2
    text: View all certifications and request audit reports
    type: audit report
  trust_center:
    url: https://www.elastic.co/trust
frameworks:
- FedRAMP
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Elasticsearch
provenance_date: '2026-11-09'
provider_name: Elasticsearch
provider_slug: elasticsearch
slug: elasticsearch-compliance
source_date: '2026-11-09'
source_filename: elasticsearch-compliance.yml
source_heading: Compliance
source_page: https://www.elastic.co/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Elasticsearch\naid: elasticsearch\nurl: https://www.elastic.co/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/elasticsearch-trust-center.yml\ntrust_center:\n  url: https://www.elastic.co/trust\nattestations:\n- framework: FedRAMP\n  type: certification\n  scope: FedRAMP High\n  period: null\n  issuer: null\n  report_access: on_request\n  text: 'FedRAMP High FedRAMP Moderate PCI DSS CSA STAR ISO/IEC 27001 ISO/IEC 27017 ISO/IEC 27018 SOC 2 SOC 3 TISAX\n    HIPAA Cyber Essentials Plus IRAP Assessed: Protected B CyberGRX'\n- framework: ISO27001\n  type: certification\n  scope: ISO/IEC 27001\n  period:\
  \ null\n  issuer: null\n  report_access: on_request\n  text: Our services are independently audited and certified to meet industry-leading compliance and privacy standards.\n    View all certifications and request audit reports\n- framework: SOC2\n  type: audit report\n  scope: SOC 2\n  period: null\n  issuer: null\n  report_access: on_request\n  text: View all certifications and request audit reports\n"
source_yaml_url: https://artifacts.apis.io/elasticsearch/compliance/elasticsearch-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Elasticsearch's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Database
- Full-Text Search
- NoSQL
- Search
---
