---
api_specs:
- filename: reputation-asset-library-api-openapi.yml
  format: yaml
  label: Reputation Asset Library API
  slug: reputation-asset-library-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-asset-library-api-openapi.yml
- filename: reputation-authorize-api-openapi.yml
  format: yaml
  label: Reputation Authorize API
  slug: reputation-authorize-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-authorize-api-openapi.yml
- filename: reputation-categories-api-openapi.yml
  format: yaml
  label: Reputation Categories API
  slug: reputation-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-categories-api-openapi.yml
- filename: reputation-credentials-api-openapi.yml
  format: yaml
  label: Reputation Credentials API
  slug: reputation-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-credentials-api-openapi.yml
- filename: reputation-listing-audits-api-openapi.yml
  format: yaml
  label: Reputation Listing Audits API
  slug: reputation-listing-audits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-listing-audits-api-openapi.yml
- filename: reputation-locations-api-openapi.yml
  format: yaml
  label: Reputation Locations API
  slug: reputation-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-locations-api-openapi.yml
- filename: reputation-metrics-api-openapi.yml
  format: yaml
  label: Reputation Metrics API
  slug: reputation-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-metrics-api-openapi.yml
- filename: reputation-reports-api-openapi.yml
  format: yaml
  label: Reputation Reports API
  slug: reputation-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-reports-api-openapi.yml
- filename: reputation-requests-api-openapi.yml
  format: yaml
  label: Reputation Requests API
  slug: reputation-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-requests-api-openapi.yml
- filename: reputation-reviews-api-openapi.yml
  format: yaml
  label: Reputation Reviews API
  slug: reputation-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-reviews-api-openapi.yml
- filename: reputation-rich-content-api-openapi.yml
  format: yaml
  label: Reputation Rich Content API
  slug: reputation-rich-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-rich-content-api-openapi.yml
- filename: reputation-summary-api-openapi.yml
  format: yaml
  label: Reputation Summary API
  slug: reputation-summary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-summary-api-openapi.yml
- filename: reputation-surveys-api-openapi.yml
  format: yaml
  label: Reputation Surveys API
  slug: reputation-surveys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-surveys-api-openapi.yml
- filename: reputation-tenants-api-openapi.yml
  format: yaml
  label: Reputation Tenants API
  slug: reputation-tenants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-tenants-api-openapi.yml
- filename: reputation-tickets-api-openapi.yml
  format: yaml
  label: Reputation Tickets API
  slug: reputation-tickets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-tickets-api-openapi.yml
- filename: reputation-users-api-openapi.yml
  format: yaml
  label: Reputation Users API
  slug: reputation-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reputation/openapi/reputation-users-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: third-party auditor
    period: null
    report_access: nda
    scope: null
    text: Reputation is SOC2 Type II compliant and ISO 27001 certified as attested by a third-party auditor and is HIPAA compliant
    type: SOC 2 Type II report
  - framework: ISO27001
    issuer: third-party auditor
    period: null
    report_access: nda
    scope: null
    text: Reputation will share the latest SOC2 Type II report, ISO 27001 Certificate and our HIPAA Business Associates Agreement upon request and under NDA.
    type: ISO 27001 certificate
  - framework: HIPAA
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: is HIPAA compliant to ensure all customer PII and PHI are properly handled
    type: HIPAA compliance; Business Associates Agreement
  trust_center:
    url: https://reputation.com/legal-information/security-posture
frameworks:
- HIPAA
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Reputation
provenance_date: '2026-11-10'
provider_name: Reputation
provider_slug: reputation
slug: reputation-compliance
source_date: '2026-11-10'
source_filename: reputation-compliance.yml
source_heading: Compliance
source_page: https://reputation.com/legal-information/security-posture
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Reputation\naid: reputation\nurl: https://reputation.com/legal-information/security-posture\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://reputation.com/legal-information/security-posture\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: null\n  issuer: third-party auditor\n  report_access: nda\n  text: Reputation is SOC2 Type II compliant and ISO 27001 certified as attested by a third-party auditor and is\n    HIPAA compliant\n- framework: ISO27001\n  type: ISO 27001 certificate\n  scope: null\n  period: null\n  issuer: third-party auditor\n  report_access:\
  \ nda\n  text: Reputation will share the latest SOC2 Type II report, ISO 27001 Certificate and our HIPAA Business Associates\n    Agreement upon request and under NDA.\n- framework: HIPAA\n  type: HIPAA compliance; Business Associates Agreement\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: is HIPAA compliant to ensure all customer PII and PHI are properly handled\n"
source_yaml_url: https://artifacts.apis.io/reputation/compliance/reputation-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Reputation's own page on 2026-11-10.
synthetic: false
tags:
- Reputation Management
- Online Reviews
- Business Listings
- Surveys
- Social Listening
- Competitive Intelligence
- Customer Experience
- Local SEO
---
