---
api_specs:
- filename: fieldguide-comments-api-openapi.yml
  format: yaml
  label: Fieldguide Comments API
  slug: fieldguide-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-comments-api-openapi.yml
- filename: fieldguide-companies-api-openapi.yml
  format: yaml
  label: Fieldguide Companies API
  slug: fieldguide-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-companies-api-openapi.yml
- filename: fieldguide-controls-api-openapi.yml
  format: yaml
  label: Fieldguide Controls API
  slug: fieldguide-controls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-controls-api-openapi.yml
- filename: fieldguide-engagements-api-openapi.yml
  format: yaml
  label: Fieldguide Engagements API
  slug: fieldguide-engagements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-engagements-api-openapi.yml
- filename: fieldguide-files-api-openapi.yml
  format: yaml
  label: Fieldguide Files API
  slug: fieldguide-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-files-api-openapi.yml
- filename: fieldguide-insights-api-openapi.yml
  format: yaml
  label: Fieldguide Insights API
  slug: fieldguide-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-insights-api-openapi.yml
- filename: fieldguide-jobs-api-openapi.yml
  format: yaml
  label: Fieldguide Jobs API
  slug: fieldguide-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-jobs-api-openapi.yml
- filename: fieldguide-milestones-api-openapi.yml
  format: yaml
  label: Fieldguide Milestones API
  slug: fieldguide-milestones-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-milestones-api-openapi.yml
- filename: fieldguide-requests-api-openapi.yml
  format: yaml
  label: Fieldguide Requests API
  slug: fieldguide-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-requests-api-openapi.yml
- filename: fieldguide-sheet-columns-api-openapi.yml
  format: yaml
  label: Fieldguide Sheet Columns API
  slug: fieldguide-sheet-columns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-sheet-columns-api-openapi.yml
- filename: fieldguide-sheet-rows-api-openapi.yml
  format: yaml
  label: Fieldguide Sheet Rows API
  slug: fieldguide-sheet-rows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-sheet-rows-api-openapi.yml
- filename: fieldguide-sheets-api-openapi.yml
  format: yaml
  label: Fieldguide Sheets API
  slug: fieldguide-sheets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-sheets-api-openapi.yml
- filename: fieldguide-users-api-openapi.yml
  format: yaml
  label: Fieldguide Users API
  slug: fieldguide-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-users-api-openapi.yml
- filename: fieldguide-webhooks-api-openapi.yml
  format: yaml
  label: Fieldguide Webhooks API
  slug: fieldguide-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-webhooks-api-openapi.yml
- filename: fieldguide-scopes-api-openapi.yml
  format: yaml
  label: Fieldguide Scopes API
  slug: fieldguide-scopes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-scopes-api-openapi.yml
- filename: fieldguide-token-api-openapi.yml
  format: yaml
  label: Fieldguide Token API
  slug: fieldguide-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-token-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: AI management systems
    text: The first international standard for AI management systems.
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: security, availability, and confidentiality controls
    text: An independent audit that validates our security, availability, and confidentiality controls over time.
    type: Type 2 audit
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: security and data-handling requirements
    text: A use-control attestation confirming that our processes meet specific security and data-handling requirements, verified through external assessment.
    type: use-control attestation
  trust_center:
    url: https://www.fieldguide.com/trust
frameworks:
- ISO42001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Fieldguide
provenance_date: '2026-11-09'
provider_name: Fieldguide
provider_slug: fieldguide
slug: fieldguide-compliance
source_date: '2026-11-09'
source_filename: fieldguide-compliance.yml
source_heading: Compliance
source_page: https://www.fieldguide.com/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Fieldguide\naid: fieldguide\nurl: https://www.fieldguide.com/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.fieldguide.com/trust\nattestations:\n- framework: ISO42001\n  type: certification\n  scope: AI management systems\n  period: null\n  issuer: null\n  report_access: unstated\n  text: The first international standard for AI management systems.\n- framework: SOC2\n  type: Type 2 audit\n  scope: security, availability, and confidentiality controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: An independent audit that validates our security, availability, and confidentiality\
  \ controls over time.\n- framework: other\n  type: use-control attestation\n  scope: security and data-handling requirements\n  period: null\n  issuer: null\n  report_access: unstated\n  text: A use-control attestation confirming that our processes meet specific security and data-handling requirements,\n    verified through external assessment.\n"
source_yaml_url: https://artifacts.apis.io/fieldguide/compliance/fieldguide-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Fieldguide's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Audit
- Advisory
- Accounting
- Compliance
- Risk Management
- Engagement Management
- Artificial Intelligence
- Agents
- Webhook
---
