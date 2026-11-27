---
api_specs:
- filename: semsee-openapi.yml
  format: yaml
  label: Semsee Submissions API
  slug: semsee-submissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/semsee/openapi/_original/semsee-openapi.yml
- filename: semsee-openapi.yml
  format: yaml
  label: Semsee Quotes API
  slug: semsee-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/semsee/openapi/_original/semsee-openapi.yml
- filename: semsee-openapi.yml
  format: yaml
  label: Semsee Carriers API
  slug: semsee-carriers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/semsee/openapi/_original/semsee-openapi.yml
- filename: semsee-openapi.yml
  format: yaml
  label: Semsee Webhooks API
  slug: semsee-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/semsee/openapi/_original/semsee-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Johanson Group
    period: null
    report_access: nda
    scope: security, availability, and confidentiality
    text: Semsee has successfully completed its SOC 2 Type II attestation, reinforcing our commitment to security, availability, and confidentiality.
    type: SOC 2 Type II attestation
  trust_center:
    url: https://semsee.com/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Semsee
provenance_date: '2026-11-10'
provider_name: Semsee
provider_slug: semsee
slug: semsee-compliance
source_date: '2026-11-10'
source_filename: semsee-compliance.yml
source_heading: Compliance
source_page: https://semsee.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Semsee\naid: semsee\nurl: https://semsee.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/semsee-trust-center.yml\ntrust_center:\n  url: https://semsee.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II attestation\n  scope: security, availability, and confidentiality\n  period: null\n  issuer: Johanson Group\n  report_access: nda\n  text: Semsee has successfully completed its SOC 2 Type II attestation, reinforcing our commitment to security,\n    availability, and confidentiality.\n"
source_yaml_url: https://artifacts.apis.io/semsee/compliance/semsee-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Semsee's own page on 2026-11-10.
synthetic: false
tags:
- Insurance
- Insurtech
- Commercial Insurance
- Quoting
- Submissions
---
