---
api_specs:
- filename: idme-applications-openapi-generated.yml
  format: yaml
  label: ID.me applications API
  slug: applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idme/openapi/_ae-authored/idme-applications-openapi-generated.yml
- filename: idme-core-openapi-generated.yml
  format: yaml
  label: ID.me core API
  slug: core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idme/openapi/_ae-authored/idme-core-openapi-generated.yml
- filename: idme-document-passback-openapi-generated.yml
  format: yaml
  label: ID.me document passback API
  slug: document-passback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idme/openapi/_ae-authored/idme-document-passback-openapi-generated.yml
- filename: idme-services-openapi-generated.yml
  format: yaml
  label: ID.me services API
  slug: services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idme/openapi/_ae-authored/idme-services-openapi-generated.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: IDMe IAL2 online self-service verification flow
    text: Aligning with NIST 800-63-3 standards, IDMe validates and verifies one piece of strong evidence
    type: Alignment with NIST SP 800-63-3 identity proofing standards
  trust_center:
    url: https://docs.id.me/guides/learn-more/digital-wallet/nist-ial-2
frameworks:
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: ID.me
provenance_date: '2026-11-09'
provider_name: ID.me
provider_slug: idme
slug: idme-compliance
source_date: '2026-11-09'
source_filename: idme-compliance.yml
source_heading: Compliance
source_page: https://docs.id.me/guides/learn-more/digital-wallet/nist-ial-2
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: ID.me\naid: idme\nurl: https://docs.id.me/guides/learn-more/digital-wallet/nist-ial-2\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://docs.id.me/guides/learn-more/digital-wallet/nist-ial-2\nattestations:\n- framework: other\n  type: Alignment with NIST SP 800-63-3 identity proofing standards\n  scope: IDMe IAL2 online self-service verification flow\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Aligning with NIST 800-63-3 standards, IDMe validates and verifies one piece of strong evidence\n"
source_yaml_url: https://artifacts.apis.io/idme/compliance/idme-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from ID.me's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Identity
- Identity Verification
- Authentication
- OpenID Connect
- OAuth
- SAML
- SSO
- Digital Identity
- KYC
- Fraud Prevention
- Government
- Identity Federation
---
