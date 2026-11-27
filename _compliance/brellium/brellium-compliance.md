---
api_specs:
- filename: brellium-audits-api-openapi.yml
  format: yaml
  label: Brellium Audits API
  slug: brellium-audits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brellium/openapi/brellium-audits-api-openapi.yml
- filename: brellium-auth-api-openapi.yml
  format: yaml
  label: Brellium Auth API
  slug: brellium-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brellium/openapi/brellium-auth-api-openapi.yml
- filename: brellium-coding-api-openapi.yml
  format: yaml
  label: Brellium Coding API
  slug: brellium-coding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brellium/openapi/brellium-coding-api-openapi.yml
- filename: brellium-documents-api-openapi.yml
  format: yaml
  label: Brellium Documents API
  slug: brellium-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brellium/openapi/brellium-documents-api-openapi.yml
- filename: brellium-documents-multiple-api-openapi.yml
  format: yaml
  label: Brellium Documents Multiple API
  slug: brellium-documents-multiple-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brellium/openapi/brellium-documents-multiple-api-openapi.yml
- filename: brellium-link-providers-api-openapi.yml
  format: yaml
  label: Brellium Link Providers API
  slug: brellium-link-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brellium/openapi/brellium-link-providers-api-openapi.yml
- filename: brellium-question-sets-api-openapi.yml
  format: yaml
  label: Brellium Question Sets API
  slug: brellium-question-sets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brellium/openapi/brellium-question-sets-api-openapi.yml
- filename: brellium-update-audits-flags-api-openapi.yml
  format: yaml
  label: Brellium Update Audits Flags API
  slug: brellium-update-audits-flags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brellium/openapi/brellium-update-audits-flags-api-openapi.yml
- filename: brellium-users-api-openapi.yml
  format: yaml
  label: Brellium Users API
  slug: brellium-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brellium/openapi/brellium-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Independent third-party auditor
    period: null
    report_access: on_request
    scope: security controls for data handling and protection
    text: Brellium is HIPAA compliant and has completed SOC 2 Type I and Type II with Secureframe and the Johanson Group. Reports are available upon request.
    type: Type II attestation
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Brellium
    text: Brellium is HIPAA and SOC 2 compliant.
    type: compliance
  trust_center:
    url: https://www.brellium.com/security
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Brellium
provenance_date: '2026-11-09'
provider_name: Brellium
provider_slug: brellium
slug: brellium-compliance
source_date: '2026-11-09'
source_filename: brellium-compliance.yml
source_heading: Compliance
source_page: https://www.brellium.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Brellium\naid: brellium\nurl: https://www.brellium.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.brellium.com/security\nattestations:\n- framework: SOC2\n  type: Type II attestation\n  scope: security controls for data handling and protection\n  period: null\n  issuer: Independent third-party auditor\n  report_access: on_request\n  text: Brellium is HIPAA compliant and has completed SOC 2 Type I and Type II with Secureframe and the Johanson\n    Group. Reports are available upon request.\n- framework: HIPAA\n  type: compliance\n  scope: Brellium\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: Brellium is HIPAA and SOC 2 compliant.\n"
source_yaml_url: https://artifacts.apis.io/brellium/compliance/brellium-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Brellium's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Clinical Compliance
- Clinical Documentation
- Medical Coding
- Audit
- Behavioral Health
- Digital Health
---
