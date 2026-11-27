---
api_specs:
- filename: tigergraph-authentication-api-openapi.yml
  format: yaml
  label: TigerGraph Authentication API
  slug: tigergraph-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tigergraph/openapi/tigergraph-authentication-api-openapi.yml
- filename: tigergraph-data-api-openapi.yml
  format: yaml
  label: TigerGraph Data API
  slug: tigergraph-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tigergraph/openapi/tigergraph-data-api-openapi.yml
- filename: tigergraph-query-api-openapi.yml
  format: yaml
  label: TigerGraph Query API
  slug: tigergraph-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tigergraph/openapi/tigergraph-query-api-openapi.yml
- filename: tigergraph-schema-api-openapi.yml
  format: yaml
  label: TigerGraph Schema API
  slug: tigergraph-schema-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tigergraph/openapi/tigergraph-schema-api-openapi.yml
- filename: tigergraph-system-api-openapi.yml
  format: yaml
  label: TigerGraph System API
  slug: tigergraph-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tigergraph/openapi/tigergraph-system-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: NIST-CSF
    issuer: null
    period: null
    report_access: unstated
    scope: core compliance framework
    text: TigerGraph has adopted the National Institute of Standards and Technology Cybersecurity Framework as its core compliance framework.
    type: framework adoption
  - framework: SOC2
    issuer: null
    period: annual basis
    report_access: nda
    scope: corporate operations, on-premise software, and TigerGraph Savanna
    text: TigerGraph is audited on an annual basis for a report on Controls at a Service Organization Relevant to Security, Availability, Processing Integrity, and Confidentiality.
    type: Type 2 report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: information security management
    text: TigerGraph is proud to announce that we have achieved ISO 27001 certification
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: privacy practices
    text: TigerGraph has designed its privacy practices for compliance with The California Consumer Privacy Act (CCPA) and the General Data Protection Regulation (GDPR).
    type: privacy compliance design
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: privacy practices
    text: TigerGraph has designed its privacy practices for compliance with The California Consumer Privacy Act (CCPA) and the General Data Protection Regulation (GDPR).
    type: privacy compliance design
  trust_center:
    url: https://www.tigergraph.com/compliance/
frameworks:
- CCPA
- GDPR
- ISO27001
- NIST-CSF
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: TigerGraph
provenance_date: '2026-11-10'
provider_name: TigerGraph
provider_slug: tigergraph
slug: tigergraph-compliance
source_date: '2026-11-10'
source_filename: tigergraph-compliance.yml
source_heading: Compliance
source_page: https://www.tigergraph.com/compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: TigerGraph\naid: tigergraph\nurl: https://www.tigergraph.com/compliance/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/tigergraph-trust-center.yml\ntrust_center:\n  url: https://www.tigergraph.com/compliance/\nattestations:\n- framework: NIST-CSF\n  type: framework adoption\n  scope: core compliance framework\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TigerGraph has adopted the National Institute of Standards and Technology Cybersecurity Framework as its\n    core compliance framework.\n- framework: SOC2\n  type: Type 2 report\n  scope: corporate operations, on-premise software,\
  \ and TigerGraph Savanna\n  period: annual basis\n  issuer: null\n  report_access: nda\n  text: TigerGraph is audited on an annual basis for a report on Controls at a Service Organization Relevant to\n    Security, Availability, Processing Integrity, and Confidentiality.\n- framework: ISO27001\n  type: certification\n  scope: information security management\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TigerGraph is proud to announce that we have achieved ISO 27001 certification\n- framework: GDPR\n  type: privacy compliance design\n  scope: privacy practices\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TigerGraph has designed its privacy practices for compliance with The California Consumer Privacy Act (CCPA)\n    and the General Data Protection Regulation (GDPR).\n- framework: CCPA\n  type: privacy compliance design\n  scope: privacy practices\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TigerGraph has designed its privacy\
  \ practices for compliance with The California Consumer Privacy Act (CCPA)\n    and the General Data Protection Regulation (GDPR).\n"
source_yaml_url: https://artifacts.apis.io/tigergraph/compliance/tigergraph-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from TigerGraph's own page on 2026-11-10.
synthetic: false
tags:
- Graph Database
- Analytics
- GSQL
- REST++
- Graph Analytics
---
