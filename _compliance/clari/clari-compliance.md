---
api_specs:
- filename: clari-activity-api-api-openapi.yml
  format: yaml
  label: Clari Activity API
  slug: clari-activity-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clari/openapi/clari-activity-api-api-openapi.yml
- filename: clari-administrative-api-api-openapi.yml
  format: yaml
  label: Clari Administrative API
  slug: clari-administrative-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clari/openapi/clari-administrative-api-api-openapi.yml
- filename: clari-audit-api-api-openapi.yml
  format: yaml
  label: Clari Audit API
  slug: clari-audit-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clari/openapi/clari-audit-api-api-openapi.yml
- filename: clari-bulk-export-framework-api-openapi.yml
  format: yaml
  label: Clari Bulk Export Framework API
  slug: clari-bulk-export-framework-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clari/openapi/clari-bulk-export-framework-api-openapi.yml
- filename: clari-bulk-ingest-job-status-api-api-openapi.yml
  format: yaml
  label: Clari Bulk Ingest Job Status API
  slug: clari-bulk-ingest-job-status-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clari/openapi/clari-bulk-ingest-job-status-api-api-openapi.yml
- filename: clari-forecast-api-api-openapi.yml
  format: yaml
  label: Clari Forecast API
  slug: clari-forecast-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clari/openapi/clari-forecast-api-api-openapi.yml
- filename: clari-ingestion-api-api-openapi.yml
  format: yaml
  label: Clari Ingestion API
  slug: clari-ingestion-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clari/openapi/clari-ingestion-api-api-openapi.yml
- filename: clari-opportunity-api-api-openapi.yml
  format: yaml
  label: Clari Opportunity API
  slug: clari-opportunity-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clari/openapi/clari-opportunity-api-api-openapi.yml
- filename: clari-account-api-openapi.yml
  format: yaml
  label: Clari Account API
  slug: clari-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clari/openapi/clari-account-api-openapi.yml
- filename: clari-call-api-openapi.yml
  format: yaml
  label: Clari Call API
  slug: clari-call-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clari/openapi/clari-call-api-openapi.yml
- filename: clari-contact-api-openapi.yml
  format: yaml
  label: Clari Contact API
  slug: clari-contact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clari/openapi/clari-contact-api-openapi.yml
- filename: clari-deal-api-openapi.yml
  format: yaml
  label: Clari Deal API
  slug: clari-deal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clari/openapi/clari-deal-api-openapi.yml
- filename: clari-scorecard-api-openapi.yml
  format: yaml
  label: Clari Scorecard API
  slug: clari-scorecard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clari/openapi/clari-scorecard-api-openapi.yml
- filename: clari-topics-api-openapi.yml
  format: yaml
  label: Clari Topics API
  slug: clari-topics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clari/openapi/clari-topics-api-openapi.yml
- filename: clari-user-api-openapi.yml
  format: yaml
  label: Clari User API
  slug: clari-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clari/openapi/clari-user-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: third-party audit firm
    period: null
    report_access: public
    scope: Salesloft and Drift platform services
    text: The SOC 2 reports are published in the Salesloft Trust Portal .
    type: SOC 2 Type 2 examination
  - framework: ISO27001
    issuer: null
    period: null
    report_access: public
    scope: Information security management system (ISMS)
    text: Salesloft’s ISO certification is published in the Salesloft Trust Portal .
    type: certification
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: Privacy
    text: Salesloft is certified compliant with the ISO 27701 standard.
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Privacy compliance
    text: including the General Data Protection Regulation (GDPR)
    type: compliance commitment
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: Privacy compliance
    text: the California Consumer Privacy Act and Privacy Rights Act (CCPA/CPRA)
    type: compliance commitment
  trust_center:
    url: https://www.salesloft.com/security-compliance
frameworks:
- CCPA
- GDPR
- ISO27001
- ISO27701
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Clari
provenance_date: '2026-11-09'
provider_name: Clari
provider_slug: clari
slug: clari-compliance
source_date: '2026-11-09'
source_filename: clari-compliance.yml
source_heading: Compliance
source_page: https://www.salesloft.com/security-compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Clari\naid: clari\nurl: https://www.salesloft.com/security-compliance\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/clari-trust-center.yml\ntrust_center:\n  url: https://www.salesloft.com/security-compliance\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 examination\n  scope: Salesloft and Drift platform services\n  period: null\n  issuer: third-party audit firm\n  report_access: public\n  text: The SOC 2 reports are published in the Salesloft Trust Portal .\n- framework: ISO27001\n  type: certification\n  scope: Information security management system (ISMS)\n  period: null\n  issuer: null\n\
  \  report_access: public\n  text: Salesloft’s ISO certification is published in the Salesloft Trust Portal .\n- framework: ISO27701\n  type: certification\n  scope: Privacy\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Salesloft is certified compliant with the ISO 27701 standard.\n- framework: GDPR\n  type: compliance commitment\n  scope: Privacy compliance\n  period: null\n  issuer: null\n  report_access: unstated\n  text: including the General Data Protection Regulation (GDPR)\n- framework: CCPA\n  type: compliance commitment\n  scope: Privacy compliance\n  period: null\n  issuer: null\n  report_access: unstated\n  text: the California Consumer Privacy Act and Privacy Rights Act (CCPA/CPRA)\n"
source_yaml_url: https://artifacts.apis.io/clari/compliance/clari-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Clari's own page on 2026-11-09.
synthetic: false
tags:
- Revenue Operations
- Forecasting
- Pipeline Management
- Sales Intelligence
- Activity Intelligence
- Deal Insights
- CRM
- Conversation Intelligence
- B2B
- Enterprise
- MCP
- Agents
- Sales Engagement
- Bulk Export
- Data Ingestion
---
