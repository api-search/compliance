---
api_specs:
- filename: tryrook-io-client-uuid-api-openapi.yml
  format: yaml
  label: ROOK Client Uuid API
  slug: tryrook-io-client-uuid-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tryrook-io/openapi/tryrook-io-client-uuid-api-openapi.yml
- filename: tryrook-io-extraction-app-api-openapi.yml
  format: yaml
  label: ROOK Extraction App API
  slug: tryrook-io-extraction-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tryrook-io/openapi/tryrook-io-extraction-app-api-openapi.yml
- filename: tryrook-io-user-id-api-openapi.yml
  format: yaml
  label: ROOK User Id API
  slug: tryrook-io-user-id-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tryrook-io/openapi/tryrook-io-user-id-api-openapi.yml
- filename: tryrook-io-user-profile-api-openapi.yml
  format: yaml
  label: ROOK User Profile API
  slug: tryrook-io-user-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tryrook-io/openapi/tryrook-io-user-profile-api-openapi.yml
- filename: tryrook-io-webhooks-api-openapi.yml
  format: yaml
  label: ROOK Webhooks API
  slug: tryrook-io-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tryrook-io/openapi/tryrook-io-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: ROOK operates under a HIPAA-aligned security program and signs BAAs with covered entities
    text: ROOK operates under a HIPAA-aligned security program and signs BAAs with covered entities.
    type: HIPAA-aligned security program; BAA available
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: processes EU personal data under GDPR as a data processor
    text: ROOK processes EU personal data under GDPR as a data processor.
    type: Data processor under GDPR; DPA available
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: ROOK's API is also designed to support CCPA and CPRA requirements
    text: ROOK's API is also designed to support CCPA and CPRA requirements.
    type: API designed to support requirements
  trust_center:
    url: https://tryrook.io/compliance/
frameworks:
- CCPA
- GDPR
- HIPAA
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: ROOK
provenance_date: '2026-11-10'
provider_name: ROOK
provider_slug: tryrook-io
slug: tryrook-io-compliance
source_date: '2026-11-10'
source_filename: tryrook-io-compliance.yml
source_heading: Compliance
source_page: https://tryrook.io/compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: ROOK\naid: tryrook-io\nurl: https://tryrook.io/compliance/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://tryrook.io/compliance/\nattestations:\n- framework: HIPAA\n  type: HIPAA-aligned security program; BAA available\n  scope: ROOK operates under a HIPAA-aligned security program and signs BAAs with covered entities\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ROOK operates under a HIPAA-aligned security program and signs BAAs with covered entities.\n- framework: GDPR\n  type: Data processor under GDPR; DPA available\n  scope: processes EU personal data under GDPR as a data processor\n\
  \  period: null\n  issuer: null\n  report_access: unstated\n  text: ROOK processes EU personal data under GDPR as a data processor.\n- framework: CCPA\n  type: API designed to support requirements\n  scope: ROOK's API is also designed to support CCPA and CPRA requirements\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ROOK's API is also designed to support CCPA and CPRA requirements.\n"
source_yaml_url: https://artifacts.apis.io/tryrook-io/compliance/tryrook-io-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from ROOK's own page on 2026-11-10.
synthetic: false
tags:
- Health
- Data Integration
- Wearables
- Healthcare
---
