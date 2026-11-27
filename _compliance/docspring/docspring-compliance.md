---
api_specs:
- filename: docspring-authentication-api-openapi.yml
  format: yaml
  label: DocSpring Authentication API
  slug: docspring-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docspring/openapi/docspring-authentication-api-openapi.yml
- filename: docspring-combine-pdfs-api-openapi.yml
  format: yaml
  label: DocSpring Combine PDFs API
  slug: docspring-combine-pdfs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docspring/openapi/docspring-combine-pdfs-api-openapi.yml
- filename: docspring-custom-files-api-openapi.yml
  format: yaml
  label: DocSpring Custom Files API
  slug: docspring-custom-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docspring/openapi/docspring-custom-files-api-openapi.yml
- filename: docspring-data-requests-api-openapi.yml
  format: yaml
  label: DocSpring Data Requests API
  slug: docspring-data-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docspring/openapi/docspring-data-requests-api-openapi.yml
- filename: docspring-folders-api-openapi.yml
  format: yaml
  label: DocSpring Folders API
  slug: docspring-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docspring/openapi/docspring-folders-api-openapi.yml
- filename: docspring-pdf-submissions-api-openapi.yml
  format: yaml
  label: DocSpring PDF Submissions API
  slug: docspring-pdf-submissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docspring/openapi/docspring-pdf-submissions-api-openapi.yml
- filename: docspring-submission-batches-api-openapi.yml
  format: yaml
  label: DocSpring Submission Batches API
  slug: docspring-submission-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docspring/openapi/docspring-submission-batches-api-openapi.yml
- filename: docspring-templates-api-openapi.yml
  format: yaml
  label: DocSpring Templates API
  slug: docspring-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docspring/openapi/docspring-templates-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: CPA firm (named in document filename as CPA Signed)
    period: null
    report_access: nda
    scope: DocSpring, Inc.
    text: DocSpring is SOC 2 Type II audited and HIPAA compliant
    type: Type 2 audit
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: paid plans
    text: HIPAA compliant, with a BAA on every paid plan
    type: compliance with BAA
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliant
    type: compliance badge
  trust_center:
    url: https://trust.docspring.com/
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: DocSpring
provenance_date: '2026-11-09'
provider_name: DocSpring
provider_slug: docspring
slug: docspring-compliance
source_date: '2026-11-09'
source_filename: docspring-compliance.yml
source_heading: Compliance
source_page: https://trust.docspring.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: DocSpring\naid: docspring\nurl: https://trust.docspring.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/docspring-trust-center.yml\ntrust_center:\n  url: https://trust.docspring.com/\nattestations:\n- framework: SOC2\n  type: Type 2 audit\n  scope: DocSpring, Inc.\n  period: null\n  issuer: CPA firm (named in document filename as CPA Signed)\n  report_access: nda\n  text: DocSpring is SOC 2 Type II audited and HIPAA compliant\n- framework: HIPAA\n  type: compliance with BAA\n  scope: paid plans\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA compliant, with a BAA on every\
  \ paid plan\n- framework: GDPR\n  type: compliance badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliant\n"
source_yaml_url: https://artifacts.apis.io/docspring/compliance/docspring-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from DocSpring's own page on 2026-11-09.
synthetic: false
tags:
- PDF
- Document Generation
- PDF Templates
- E-Signature
- Forms
- HTML to PDF
- Document Automation
---
