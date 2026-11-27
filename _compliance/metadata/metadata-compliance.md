---
api_specs:
- filename: metadata-health-api-openapi.yml
  format: yaml
  label: Metadata Health API
  slug: metadata-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metadata/openapi/metadata-health-api-openapi.yml
- filename: metadata-mcp-api-openapi.yml
  format: yaml
  label: Metadata MCP API
  slug: metadata-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metadata/openapi/metadata-mcp-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: security, availability, processing integrity, confidentiality, and privacy controls
    text: Customers can request access to our security policies and certain compliance reports
    type: SOC 2 Type II
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: information security management system
    text: Systematic, ongoing management of information security risks across people, processes, and IT systems.
    type: ISO 27001 certification
  - framework: ISO27701
    issuer: null
    period: null
    report_access: on_request
    scope: privacy management, GDPR compliance and privacy-by-design
    text: GDPR compliance and privacy-by-design implementation across the platform, with systematic privacy management.
    type: ISO 27701 certification
  trust_center:
    url: https://metadata.io/trust-compliance
frameworks:
- ISO27001
- ISO27701
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Metadata
provenance_date: '2026-11-10'
provider_name: Metadata
provider_slug: metadata
slug: metadata-compliance
source_date: '2026-11-10'
source_filename: metadata-compliance.yml
source_heading: Compliance
source_page: https://metadata.io/trust-compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Metadata\naid: metadata\nurl: https://metadata.io/trust-compliance\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://metadata.io/trust-compliance\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: security, availability, processing integrity, confidentiality, and privacy controls\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Customers can request access to our security policies and certain compliance reports\n- framework: ISO27001\n  type: ISO 27001 certification\n  scope: information security management system\n  period: null\n  issuer: null\n  report_access: on_request\n\
  \  text: Systematic, ongoing management of information security risks across people, processes, and IT systems.\n- framework: ISO27701\n  type: ISO 27701 certification\n  scope: privacy management, GDPR compliance and privacy-by-design\n  period: null\n  issuer: null\n  report_access: on_request\n  text: GDPR compliance and privacy-by-design implementation across the platform, with systematic privacy management.\n"
source_yaml_url: https://artifacts.apis.io/metadata/compliance/metadata-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Metadata's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketing
- Marketing Automation
- Demand Generation
- Advertising
- B2B
- Artificial Intelligence
- MCP
- AI Agents
- Paid Media
- Account Based Marketing
---
