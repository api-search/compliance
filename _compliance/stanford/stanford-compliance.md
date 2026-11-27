---
api_specs:
- filename: stanford-about-api-openapi.yml
  format: yaml
  label: Stanford University About API
  slug: stanford-about-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stanford/openapi/stanford-about-api-openapi.yml
- filename: stanford-authentication-api-openapi.yml
  format: yaml
  label: Stanford University Authentication API
  slug: stanford-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stanford/openapi/stanford-authentication-api-openapi.yml
- filename: stanford-catalog-api-openapi.yml
  format: yaml
  label: Stanford University Catalog API
  slug: stanford-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stanford/openapi/stanford-catalog-api-openapi.yml
- filename: stanford-events-api-openapi.yml
  format: yaml
  label: Stanford University Events API
  slug: stanford-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stanford/openapi/stanford-events-api-openapi.yml
- filename: stanford-files-api-openapi.yml
  format: yaml
  label: Stanford University Files API
  slug: stanford-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stanford/openapi/stanford-files-api-openapi.yml
- filename: stanford-identifiers-api-openapi.yml
  format: yaml
  label: Stanford University Identifiers API
  slug: stanford-identifiers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stanford/openapi/stanford-identifiers-api-openapi.yml
- filename: stanford-integrations-api-openapi.yml
  format: yaml
  label: Stanford University Integrations API
  slug: stanford-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stanford/openapi/stanford-integrations-api-openapi.yml
- filename: stanford-jobs-api-openapi.yml
  format: yaml
  label: Stanford University Jobs API
  slug: stanford-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stanford/openapi/stanford-jobs-api-openapi.yml
- filename: stanford-legacy-api-openapi.yml
  format: yaml
  label: Stanford University Legacy API
  slug: stanford-legacy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stanford/openapi/stanford-legacy-api-openapi.yml
- filename: stanford-metadata-api-openapi.yml
  format: yaml
  label: Stanford University Metadata API
  slug: stanford-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stanford/openapi/stanford-metadata-api-openapi.yml
- filename: stanford-objects-api-openapi.yml
  format: yaml
  label: Stanford University Objects API
  slug: stanford-objects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stanford/openapi/stanford-objects-api-openapi.yml
- filename: stanford-release-tags-api-openapi.yml
  format: yaml
  label: Stanford University Release Tags API
  slug: stanford-release-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stanford/openapi/stanford-release-tags-api-openapi.yml
- filename: stanford-tags-api-openapi.yml
  format: yaml
  label: Stanford University Tags API
  slug: stanford-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stanford/openapi/stanford-tags-api-openapi.yml
- filename: stanford-versions-api-openapi.yml
  format: yaml
  label: Stanford University Versions API
  slug: stanford-versions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stanford/openapi/stanford-versions-api-openapi.yml
- filename: stanford-workflows-api-openapi.yml
  format: yaml
  label: Stanford University Workflows API
  slug: stanford-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stanford/openapi/stanford-workflows-api-openapi.yml
- filename: stanford-workspaces-api-openapi.yml
  format: yaml
  label: Stanford University Workspaces API
  slug: stanford-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stanford/openapi/stanford-workspaces-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: university computing resources and data
    text: 'Regulatory: CA 1798.82 | CCPA | CMIA | FERPA | GDPR | HIPAA | PCI'
    type: regulatory reference listed
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: university computing resources and data
    text: 'Regulatory: CA 1798.82 | CCPA | CMIA | FERPA | GDPR | HIPAA | PCI'
    type: regulatory reference listed
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: university computing resources and data
    text: 'Regulatory: CA 1798.82 | CCPA | CMIA | FERPA | GDPR | HIPAA | PCI'
    type: regulatory reference listed
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: university computing resources and data
    text: 'Regulatory: CA 1798.82 | CCPA | CMIA | FERPA | GDPR | HIPAA | PCI'
    type: regulatory reference listed
  trust_center:
    url: https://uit.stanford.edu/security
frameworks:
- CCPA
- GDPR
- HIPAA
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Stanford University
provenance_date: '2026-11-10'
provider_name: Stanford University
provider_slug: stanford
slug: stanford-compliance
source_date: '2026-11-10'
source_filename: stanford-compliance.yml
source_heading: Compliance
source_page: https://uit.stanford.edu/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Stanford University\naid: stanford\nurl: https://uit.stanford.edu/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/stanford-trust-center.yml\ntrust_center:\n  url: https://uit.stanford.edu/security\nattestations:\n- framework: HIPAA\n  type: regulatory reference listed\n  scope: university computing resources and data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'Regulatory: CA 1798.82 | CCPA | CMIA | FERPA | GDPR | HIPAA | PCI'\n- framework: PCI-DSS\n  type: regulatory reference listed\n  scope: university computing resources and data\n  period: null\n  issuer: null\n\
  \  report_access: unstated\n  text: 'Regulatory: CA 1798.82 | CCPA | CMIA | FERPA | GDPR | HIPAA | PCI'\n- framework: GDPR\n  type: regulatory reference listed\n  scope: university computing resources and data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'Regulatory: CA 1798.82 | CCPA | CMIA | FERPA | GDPR | HIPAA | PCI'\n- framework: CCPA\n  type: regulatory reference listed\n  scope: university computing resources and data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'Regulatory: CA 1798.82 | CCPA | CMIA | FERPA | GDPR | HIPAA | PCI'\n"
source_yaml_url: https://artifacts.apis.io/stanford/compliance/stanford-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Stanford University's own page on 2026-11-10.
synthetic: false
tags:
- University
- Higher Education
- Education
- Research
- United States
- California
- Private Research University
- Association of American Universities
- Research Repository
- Course Catalog
- Identity Federation
- Library
- Digital Repository
- Artificial Intelligence
- IIIF
---
