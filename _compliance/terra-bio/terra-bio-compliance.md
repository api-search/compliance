---
api_specs:
- filename: terra-bio-public-api-openapi.yml
  format: yaml
  label: Terra Public API
  slug: terra-bio-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/terra-bio/openapi/terra-bio-public-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: NIST-800-53
    issuer: null
    period: null
    report_access: unstated
    scope: Terra platform
    text: we implement controls from the NIST 800-53 Moderate baseline and select additional enhancing controls where needed
    type: control baseline implemented
  trust_center:
    url: https://terra.bio/customer-security-requirements/
frameworks:
- NIST-800-53
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Terra
provenance_date: '2026-11-10'
provider_name: Terra
provider_slug: terra-bio
slug: terra-bio-compliance
source_date: '2026-11-10'
source_filename: terra-bio-compliance.yml
source_heading: Compliance
source_page: https://terra.bio/customer-security-requirements/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Terra\naid: terra-bio\nurl: https://terra.bio/customer-security-requirements/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://terra.bio/customer-security-requirements/\nattestations:\n- framework: NIST-800-53\n  type: control baseline implemented\n  scope: Terra platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: we implement controls from the NIST 800-53 Moderate baseline and select additional enhancing controls where\n    needed\n"
source_yaml_url: https://artifacts.apis.io/terra-bio/compliance/terra-bio-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Terra's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Biomedical
- Data Analysis
- Collaboration
- Cloud Platform
---
