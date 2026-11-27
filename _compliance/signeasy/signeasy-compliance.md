---
api_specs:
- filename: signeasy-embedded-api-openapi.yml
  format: yaml
  label: Signeasy Embedded API
  slug: signeasy-embedded-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signeasy/openapi/signeasy-embedded-api-openapi.yml
- filename: signeasy-envelopes-api-openapi.yml
  format: yaml
  label: Signeasy Envelopes API
  slug: signeasy-envelopes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signeasy/openapi/signeasy-envelopes-api-openapi.yml
- filename: signeasy-originals-api-openapi.yml
  format: yaml
  label: Signeasy Originals API
  slug: signeasy-originals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signeasy/openapi/signeasy-originals-api-openapi.yml
- filename: signeasy-templates-api-openapi.yml
  format: yaml
  label: Signeasy Templates API
  slug: signeasy-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signeasy/openapi/signeasy-templates-api-openapi.yml
- filename: signeasy-users-api-openapi.yml
  format: yaml
  label: Signeasy Users API
  slug: signeasy-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signeasy/openapi/signeasy-users-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: platform
    text: Our platform is certified with SOC 2 standards, and we undergo regular security audits
    type: certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: healthcare data
    text: Signeasy complies with HIPAA regulations to ensure your healthcare data is handled responsibly and securely
    type: compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliance ESIGN, UETA, eIDAS, SOC 2, GDPR, HIPAA, 21 CFR
    type: compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: electronic signatures (EU and US)
    text: Signeasy adheres to eIDAS and ESIGN Act regulations, providing legally binding and secure electronic signatures in the EU and the US
    type: regulatory compliance
  trust_center:
    url: https://signeasy.com/security
frameworks:
- GDPR
- HIPAA
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Signeasy
provenance_date: '2026-11-10'
provider_name: Signeasy
provider_slug: signeasy
slug: signeasy-compliance
source_date: '2026-11-10'
source_filename: signeasy-compliance.yml
source_heading: Compliance
source_page: https://signeasy.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Signeasy\naid: signeasy\nurl: https://signeasy.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/signeasy-trust-center.yml\ntrust_center:\n  url: https://signeasy.com/security\nattestations:\n- framework: SOC2\n  type: certification\n  scope: platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our platform is certified with SOC 2 standards, and we undergo regular security audits\n- framework: HIPAA\n  type: compliance\n  scope: healthcare data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Signeasy complies with HIPAA regulations to ensure your\
  \ healthcare data is handled responsibly and securely\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance ESIGN, UETA, eIDAS, SOC 2, GDPR, HIPAA, 21 CFR\n- framework: other\n  type: regulatory compliance\n  scope: electronic signatures (EU and US)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Signeasy adheres to eIDAS and ESIGN Act regulations, providing legally binding and secure electronic signatures\n    in the EU and the US\n"
source_yaml_url: https://artifacts.apis.io/signeasy/compliance/signeasy-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Signeasy's own page on 2026-11-10.
synthetic: false
tags:
- E-Signature
- Documents
- Contract Management
- Embedded Signing
- Templates
- Webhook
---
