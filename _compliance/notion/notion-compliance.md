---
api_specs:
- filename: notion-blocks-api-openapi.yml
  format: yaml
  label: Notion Blocks API
  slug: notion-blocks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/notion/openapi/notion-blocks-api-openapi.yml
- filename: notion-comments-api-openapi.yml
  format: yaml
  label: Notion Comments API
  slug: notion-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/notion/openapi/notion-comments-api-openapi.yml
- filename: notion-databases-api-openapi.yml
  format: yaml
  label: Notion Databases API
  slug: notion-databases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/notion/openapi/notion-databases-api-openapi.yml
- filename: notion-pages-api-openapi.yml
  format: yaml
  label: Notion Pages API
  slug: notion-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/notion/openapi/notion-pages-api-openapi.yml
- filename: notion-search-api-openapi.yml
  format: yaml
  label: Notion Search API
  slug: notion-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/notion/openapi/notion-search-api-openapi.yml
- filename: notion-users-api-openapi.yml
  format: yaml
  label: Notion Users API
  slug: notion-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/notion/openapi/notion-users-api-openapi.yml
claim_count: 8
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Notion platform
    text: Notion undergoes multiple, annual, industry standard audits including SOC 2, ISO 27001, ISMAP, BSI C5, and more!
    type: audit report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: Notion platform
    text: Notion undergoes multiple, annual, industry standard audits including SOC 2, ISO 27001, ISMAP, BSI C5, and more!
    type: audit
  - framework: C5
    issuer: null
    period: null
    report_access: on_request
    scope: Notion platform
    text: Notion undergoes multiple, annual, industry standard audits including SOC 2, ISO 27001, ISMAP, BSI C5, and more!
    type: audit
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: privacy controls
    text: independently attested to against ISO 27701 and ISO 27018
    type: attestation
  - framework: ISO27018
    issuer: null
    period: null
    report_access: unstated
    scope: privacy controls
    text: independently attested to against ISO 27701 and ISO 27018
    type: attestation
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data
    text: Notion is aligned with the General Data Protection Regulation (GDPR)
    type: alignment
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: California privacy laws
    text: Notion complies with California privacy laws, including CCPA and CPRA
    type: compliance
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Enterprise HIPAA security features
    text: Businesses subject to HIPAA can leverage Notion's Enterprise-grade HIPAA security features, with a Business Associate Agreement (BAA) available to Enterprise customers.
    type: configuration
  trust_center:
    url: https://www.notion.com/security
frameworks:
- C5
- CCPA
- GDPR
- HIPAA
- ISO27001
- ISO27018
- ISO27701
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Notion
provenance_date: '2026-11-10'
provider_name: Notion
provider_slug: notion
slug: notion-compliance
source_date: '2026-11-10'
source_filename: notion-compliance.yml
source_heading: Compliance
source_page: https://www.notion.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Notion\naid: notion\nurl: https://www.notion.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/notion-trust-center.yml\ntrust_center:\n  url: https://www.notion.com/security\nattestations:\n- framework: SOC2\n  type: audit report\n  scope: Notion platform\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Notion undergoes multiple, annual, industry standard audits including SOC 2, ISO 27001, ISMAP, BSI C5, and\n    more!\n- framework: ISO27001\n  type: audit\n  scope: Notion platform\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Notion undergoes\
  \ multiple, annual, industry standard audits including SOC 2, ISO 27001, ISMAP, BSI C5, and\n    more!\n- framework: C5\n  type: audit\n  scope: Notion platform\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Notion undergoes multiple, annual, industry standard audits including SOC 2, ISO 27001, ISMAP, BSI C5, and\n    more!\n- framework: ISO27701\n  type: attestation\n  scope: privacy controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: independently attested to against ISO 27701 and ISO 27018\n- framework: ISO27018\n  type: attestation\n  scope: privacy controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: independently attested to against ISO 27701 and ISO 27018\n- framework: GDPR\n  type: alignment\n  scope: personal data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Notion is aligned with the General Data Protection Regulation (GDPR)\n- framework: CCPA\n  type: compliance\n  scope: California\
  \ privacy laws\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Notion complies with California privacy laws, including CCPA and CPRA\n- framework: HIPAA\n  type: configuration\n  scope: Enterprise HIPAA security features\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Businesses subject to HIPAA can leverage Notion's Enterprise-grade HIPAA security features, with a Business\n    Associate Agreement (BAA) available to Enterprise customers.\n"
source_yaml_url: https://artifacts.apis.io/notion/compliance/notion-compliance.yml
stated_fields:
- attestations
summary_line: 8 quoted statements, read from Notion's own page on 2026-11-10.
synthetic: false
tags:
- Collaboration
- Database
- Ideas
- Notes
- Productivity
- Project
- T1
- Task
- Wiki
- Workspace
- Knowledge Management
---
