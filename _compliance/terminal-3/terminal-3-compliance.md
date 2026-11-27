---
api_specs:
- filename: terminal-3-did-v1-api-openapi.yml
  format: yaml
  label: Terminal 3 DID V1 API
  slug: terminal-3-did-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/terminal-3/openapi/terminal-3-did-v1-api-openapi.yml
- filename: terminal-3-openid-connect-v1-api-openapi.yml
  format: yaml
  label: Terminal 3 OpenID Connect V1 API
  slug: terminal-3-openid-connect-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/terminal-3/openapi/terminal-3-openid-connect-v1-api-openapi.yml
- filename: terminal-3-openid-connect-v2-api-openapi.yml
  format: yaml
  label: Terminal 3 OpenID Connect V2 API
  slug: terminal-3-openid-connect-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/terminal-3/openapi/terminal-3-openid-connect-v2-api-openapi.yml
- filename: terminal-3-sub-client-v1-api-openapi.yml
  format: yaml
  label: Terminal 3 Sub Client V1 API
  slug: terminal-3-sub-client-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/terminal-3/openapi/terminal-3-sub-client-v1-api-openapi.yml
- filename: terminal-3-transactional-email-template-v1-api-openapi.yml
  format: yaml
  label: Terminal 3 Transactional Email Template V1 API
  slug: terminal-3-transactional-email-template-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/terminal-3/openapi/terminal-3-transactional-email-template-v1-api-openapi.yml
- filename: terminal-3-user-v1-api-openapi.yml
  format: yaml
  label: Terminal 3 User V1 API
  slug: terminal-3-user-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/terminal-3/openapi/terminal-3-user-v1-api-openapi.yml
- filename: terminal-3-vc-v1-api-openapi.yml
  format: yaml
  label: Terminal 3 VC V1 API
  slug: terminal-3-vc-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/terminal-3/openapi/terminal-3-vc-v1-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: other
    issuer: Independent security firm
    period: null
    report_access: nda
    scope: Full-scope review of security controls, access management, network boundaries, and infrastructure hardening
    text: Full-scope review of security controls, access management, network boundaries, and infrastructure hardening.
    type: Independent security audit
  - framework: other
    issuer: Independent cryptographers
    period: null
    report_access: nda
    scope: Cryptographic implementation, threshold key management, TEE attestation logic, and post-quantum algorithms
    text: Deep review of cryptographic implementation, threshold key management, TEE attestation logic, and post-quantum algorithms.
    type: Cryptography audit
  - framework: other
    issuer: PwC
    period: Annual
    report_access: unstated
    scope: API surface, authentication flows, and network boundary controls
    text: Annual external penetration test of API surface, authentication flows, and network boundary controls by PwC.
    type: Penetration test
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Data residency at the infrastructure layer
    text: GDPR, PDPA, and APPI residency requirements are satisfied at the infrastructure layer, without any policy configuration required.
    type: Data residency requirements satisfied
  trust_center:
    url: https://terminal3.io/security
frameworks:
- GDPR
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Terminal 3
provenance_date: '2026-11-10'
provider_name: Terminal 3
provider_slug: terminal-3
slug: terminal-3-compliance
source_date: '2026-11-10'
source_filename: terminal-3-compliance.yml
source_heading: Compliance
source_page: https://terminal3.io/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Terminal 3\naid: terminal-3\nurl: https://terminal3.io/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://terminal3.io/security\nattestations:\n- framework: other\n  type: Independent security audit\n  scope: Full-scope review of security controls, access management, network boundaries, and infrastructure hardening\n  period: null\n  issuer: Independent security firm\n  report_access: nda\n  text: Full-scope review of security controls, access management, network boundaries, and infrastructure hardening.\n- framework: other\n  type: Cryptography audit\n  scope: Cryptographic implementation, threshold\
  \ key management, TEE attestation logic, and post-quantum algorithms\n  period: null\n  issuer: Independent cryptographers\n  report_access: nda\n  text: Deep review of cryptographic implementation, threshold key management, TEE attestation logic, and post-quantum\n    algorithms.\n- framework: other\n  type: Penetration test\n  scope: API surface, authentication flows, and network boundary controls\n  period: Annual\n  issuer: PwC\n  report_access: unstated\n  text: Annual external penetration test of API surface, authentication flows, and network boundary controls by\n    PwC.\n- framework: GDPR\n  type: Data residency requirements satisfied\n  scope: Data residency at the infrastructure layer\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR, PDPA, and APPI residency requirements are satisfied at the infrastructure layer, without any policy\n    configuration required.\n"
source_yaml_url: https://artifacts.apis.io/terminal-3/compliance/terminal-3-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Terminal 3's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Identity
- Decentralized Identity
- Verifiable Credentials
- OpenID Connect
- KYC
- AML
- Confidential Computing
- AI Agents
- Privacy
- Web3
- DID
---
