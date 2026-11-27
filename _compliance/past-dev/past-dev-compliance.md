---
api_specs:
- filename: past-dev-audiences-api-openapi.yml
  format: yaml
  label: past-dev Audiences API
  slug: past-dev-audiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/past-dev/openapi/past-dev-audiences-api-openapi.yml
- filename: past-dev-debugging-api-openapi.yml
  format: yaml
  label: past-dev Debugging API
  slug: past-dev-debugging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/past-dev/openapi/past-dev-debugging-api-openapi.yml
- filename: past-dev-identities-api-openapi.yml
  format: yaml
  label: past-dev Identities API
  slug: past-dev-identities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/past-dev/openapi/past-dev-identities-api-openapi.yml
- filename: past-dev-ingestion-api-openapi.yml
  format: yaml
  label: past-dev Ingestion API
  slug: past-dev-ingestion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/past-dev/openapi/past-dev-ingestion-api-openapi.yml
- filename: past-dev-management-api-openapi.yml
  format: yaml
  label: past-dev Management API
  slug: past-dev-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/past-dev/openapi/past-dev-management-api-openapi.yml
- filename: past-dev-recall-api-openapi.yml
  format: yaml
  label: past-dev Recall API
  slug: past-dev-recall-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/past-dev/openapi/past-dev-recall-api-openapi.yml
- filename: past-dev-webhooks-api-openapi.yml
  format: yaml
  label: past-dev Webhooks API
  slug: past-dev-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/past-dev/openapi/past-dev-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent auditor
    period: null
    report_access: nda
    scope: controls audited every year
    text: The report is available under NDA in the compliance pack.
    type: SOC 2 Type II audit
  - framework: ISO27001
    issuer: independent certification body
    period: null
    report_access: on_request
    scope: information security management system incl. access control, cryptography, secure development, supplier management, logging, and incident response
    text: Independent certification of the information security management system.
    type: ISO/IEC 27001 certification
  - framework: ISO27701
    issuer: null
    period: null
    report_access: on_request
    scope: privacy information management controls for processing, minimising, and retaining personal data
    text: Privacy information management controls for processing, minimising, and retaining personal data, including data subject requests.
    type: ISO/IEC 27701 certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: on_request
    scope: data minimisation, retention, and data subject rights
    text: A data processing agreement is available on request.
    type: GDPR compliance
  trust_center:
    url: https://past.dev/security
frameworks:
- GDPR
- ISO27001
- ISO27701
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: past-dev
provenance_date: '2026-11-10'
provider_name: past-dev
provider_slug: past-dev
slug: past-dev-compliance
source_date: '2026-11-10'
source_filename: past-dev-compliance.yml
source_heading: Compliance
source_page: https://past.dev/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: past-dev\naid: past-dev\nurl: https://past.dev/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://past.dev/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: controls audited every year\n  period: null\n  issuer: independent auditor\n  report_access: nda\n  text: The report is available under NDA in the compliance pack.\n- framework: ISO27001\n  type: ISO/IEC 27001 certification\n  scope: information security management system incl. access control, cryptography, secure development, supplier\n    management, logging, and incident response\n  period: null\n  issuer:\
  \ independent certification body\n  report_access: on_request\n  text: Independent certification of the information security management system.\n- framework: ISO27701\n  type: ISO/IEC 27701 certification\n  scope: privacy information management controls for processing, minimising, and retaining personal data\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Privacy information management controls for processing, minimising, and retaining personal data, including\n    data subject requests.\n- framework: GDPR\n  type: GDPR compliance\n  scope: data minimisation, retention, and data subject rights\n  period: null\n  issuer: null\n  report_access: on_request\n  text: A data processing agreement is available on request.\n"
source_yaml_url: https://artifacts.apis.io/past-dev/compliance/past-dev-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from past-dev's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Memory
- Platform
- Developers
---
