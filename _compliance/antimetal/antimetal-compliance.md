---
api_specs:
- filename: antimetal-artifacts-api-openapi.yml
  format: yaml
  label: Antimetal Artifacts API
  slug: antimetal-artifacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/antimetal/openapi/antimetal-artifacts-api-openapi.yml
- filename: antimetal-issues-api-openapi.yml
  format: yaml
  label: Antimetal Issues API
  slug: antimetal-issues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/antimetal/openapi/antimetal-issues-api-openapi.yml
- filename: antimetal-query-api-openapi.yml
  format: yaml
  label: Antimetal Query API
  slug: antimetal-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/antimetal/openapi/antimetal-query-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: '2025'
    report_access: unstated
    scope: null
    text: Antimetal - SOC 2 Type II - 2025
    type: Type II
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: null
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: null
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: security, availability, and confidentiality
    source: https://docs.antimetal.com/admin/security
    text: Antimetal is SOC 2 Type II certified. Our controls and procedures have been independently audited and validated to meet industry standards for security, availability, and confidentiality.
    type: Type II
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://docs.antimetal.com/admin/security
    text: Antimetal is HIPAA compliant.
    type: null
  trust_center:
    url: https://trust.antimetal.com/
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Antimetal
provenance_date: '2026-11-09'
provider_name: Antimetal
provider_slug: antimetal
slug: antimetal-compliance
source_date: '2026-11-09'
source_filename: antimetal-compliance.yml
source_heading: Compliance
source_page: https://trust.antimetal.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Antimetal\naid: antimetal\nurl: https://trust.antimetal.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/antimetal-trust-center.yml\n  sources:\n  - https://docs.antimetal.com/admin/security\n  - https://trust.antimetal.com/\ntrust_center:\n  url: https://trust.antimetal.com/\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: '2025'\n  issuer: null\n  report_access: unstated\n  text: Antimetal - SOC 2 Type II - 2025\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n- framework: GDPR\n  type: null\n\
  \  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: SOC2\n  type: Type II\n  scope: security, availability, and confidentiality\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Antimetal is SOC 2 Type II certified. Our controls and procedures have been independently audited and validated\n    to meet industry standards for security, availability, and confidentiality.\n  source: https://docs.antimetal.com/admin/security\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Antimetal is HIPAA compliant.\n  source: https://docs.antimetal.com/admin/security\n"
source_yaml_url: https://artifacts.apis.io/antimetal/compliance/antimetal-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Antimetal's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Observability
- Incident Management
- Site Reliability Engineering
- Artificial Intelligence
- Agents
- DevOps
- Cloud Infrastructure
- Kubernetes
- Root Cause Analysis
- MCP
- A2A
---
