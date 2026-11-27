---
api_specs:
- filename: scribe-documents-api-openapi.yml
  format: yaml
  label: Scribe Documents API
  slug: scribe-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scribe/openapi/scribe-documents-api-openapi.yml
- filename: scribe-search-api-openapi.yml
  format: yaml
  label: Scribe Search API
  slug: scribe-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scribe/openapi/scribe-search-api-openapi.yml
- filename: scribe-teams-api-openapi.yml
  format: yaml
  label: Scribe Teams API
  slug: scribe-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scribe/openapi/scribe-teams-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II US State Privacy Laws HIPAA FERPA GDPR
    type: compliance list entry
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II US State Privacy Laws HIPAA FERPA GDPR
    type: compliance list entry
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II US State Privacy Laws HIPAA FERPA GDPR
    type: compliance list entry
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II US State Privacy Laws HIPAA FERPA GDPR
    type: compliance list entry (FERPA)
  trust_center:
    url: https://scribe.com/security
frameworks:
- GDPR
- HIPAA
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Scribe
provenance_date: '2026-11-10'
provider_name: Scribe
provider_slug: scribe
slug: scribe-compliance
source_date: '2026-11-10'
source_filename: scribe-compliance.yml
source_heading: Compliance
source_page: https://scribe.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Scribe\naid: scribe\nurl: https://scribe.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://scribe.com/security\nattestations:\n- framework: SOC2\n  type: compliance list entry\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II US State Privacy Laws HIPAA FERPA GDPR\n- framework: HIPAA\n  type: compliance list entry\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II US State Privacy Laws HIPAA FERPA GDPR\n- framework: GDPR\n  type: compliance list entry\n  scope: null\n  period: null\n  issuer: null\n\
  \  report_access: unstated\n  text: SOC 2 Type II US State Privacy Laws HIPAA FERPA GDPR\n- framework: other\n  type: compliance list entry (FERPA)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II US State Privacy Laws HIPAA FERPA GDPR\n"
source_yaml_url: https://artifacts.apis.io/scribe/compliance/scribe-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Scribe's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Documentation
- Knowledge Management
- Search
- Workflows
- Process Documentation
- Enterprise
---
