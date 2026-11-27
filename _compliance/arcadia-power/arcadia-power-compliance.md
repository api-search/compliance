---
api_specs:
- filename: arcadia-power-accounts-api-openapi.yml
  format: yaml
  label: Arcadia Accounts API
  slug: arcadia-power-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcadia-power/openapi/arcadia-power-accounts-api-openapi.yml
- filename: arcadia-power-credentials-api-openapi.yml
  format: yaml
  label: Arcadia Credentials API
  slug: arcadia-power-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcadia-power/openapi/arcadia-power-credentials-api-openapi.yml
- filename: arcadia-power-files-api-openapi.yml
  format: yaml
  label: Arcadia Files API
  slug: arcadia-power-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcadia-power/openapi/arcadia-power-files-api-openapi.yml
- filename: arcadia-power-intervals-api-openapi.yml
  format: yaml
  label: Arcadia Intervals API
  slug: arcadia-power-intervals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcadia-power/openapi/arcadia-power-intervals-api-openapi.yml
- filename: arcadia-power-meters-api-openapi.yml
  format: yaml
  label: Arcadia Meters API
  slug: arcadia-power-meters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcadia-power/openapi/arcadia-power-meters-api-openapi.yml
- filename: arcadia-power-providers-api-openapi.yml
  format: yaml
  label: Arcadia Providers API
  slug: arcadia-power-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcadia-power/openapi/arcadia-power-providers-api-openapi.yml
- filename: arcadia-power-sites-api-openapi.yml
  format: yaml
  label: Arcadia Sites API
  slug: arcadia-power-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcadia-power/openapi/arcadia-power-sites-api-openapi.yml
- filename: arcadia-power-statements-api-openapi.yml
  format: yaml
  label: Arcadia Statements API
  slug: arcadia-power-statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcadia-power/openapi/arcadia-power-statements-api-openapi.yml
- filename: arcadia-power-webhooks-api-openapi.yml
  format: yaml
  label: Arcadia Webhooks API
  slug: arcadia-power-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcadia-power/openapi/arcadia-power-webhooks-api-openapi.yml
- filename: arcadia-power-api-keys-api-openapi.yml
  format: yaml
  label: Arcadia API Keys API
  slug: arcadia-power-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcadia-power/openapi/arcadia-power-api-keys-api-openapi.yml
- filename: arcadia-power-authentication-api-openapi.yml
  format: yaml
  label: Arcadia Authentication API
  slug: arcadia-power-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcadia-power/openapi/arcadia-power-authentication-api-openapi.yml
- filename: arcadia-power-business-units-api-openapi.yml
  format: yaml
  label: Arcadia Business Units API
  slug: arcadia-power-business-units-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcadia-power/openapi/arcadia-power-business-units-api-openapi.yml
- filename: arcadia-power-custom-data-api-openapi.yml
  format: yaml
  label: Arcadia Custom Data API
  slug: arcadia-power-custom-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcadia-power/openapi/arcadia-power-custom-data-api-openapi.yml
- filename: arcadia-power-deletion-api-openapi.yml
  format: yaml
  label: Arcadia Deletion API
  slug: arcadia-power-deletion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcadia-power/openapi/arcadia-power-deletion-api-openapi.yml
- filename: arcadia-power-discovered-statements-api-openapi.yml
  format: yaml
  label: Arcadia Discovered Statements API
  slug: arcadia-power-discovered-statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcadia-power/openapi/arcadia-power-discovered-statements-api-openapi.yml
- filename: arcadia-power-downloads-api-openapi.yml
  format: yaml
  label: Arcadia Downloads API
  slug: arcadia-power-downloads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcadia-power/openapi/arcadia-power-downloads-api-openapi.yml
- filename: arcadia-power-expected-accounts-api-openapi.yml
  format: yaml
  label: Arcadia Expected Accounts API
  slug: arcadia-power-expected-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcadia-power/openapi/arcadia-power-expected-accounts-api-openapi.yml
- filename: arcadia-power-sandbox-statements-api-openapi.yml
  format: yaml
  label: Arcadia Sandbox Statements API
  slug: arcadia-power-sandbox-statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcadia-power/openapi/arcadia-power-sandbox-statements-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Stripe payment platform (not Arcadia itself)
    text: Stripe and Plaid have their own stringent security policies and have been audited to achieve PCI Level 1 Service Provider and SOC 2 Type II compliance, respectively.
    type: third-party processor attestation
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Plaid (not Arcadia itself)
    text: Stripe and Plaid have their own stringent security policies and have been audited to achieve PCI Level 1 Service Provider and SOC 2 Type II compliance, respectively.
    type: third-party processor attestation
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Amazon Web Services physical infrastructure (not Arcadia itself)
    text: ISO 27001
    type: infrastructure provider attestation
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: Amazon Web Services physical infrastructure (not Arcadia itself)
    text: SOC 1
    type: infrastructure provider attestation
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Amazon Web Services physical infrastructure (not Arcadia itself)
    text: SOC 2/SSAE 16/ISAE 3402
    type: infrastructure provider attestation
  trust_center:
    url: https://www.arcadia.com/security
frameworks:
- ISO27001
- PCI-DSS
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Arcadia
provenance_date: '2026-11-09'
provider_name: Arcadia
provider_slug: arcadia-power
slug: arcadia-power-compliance
source_date: '2026-11-09'
source_filename: arcadia-power-compliance.yml
source_heading: Compliance
source_page: https://www.arcadia.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Arcadia\naid: arcadia-power\nurl: https://www.arcadia.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/arcadia-power-trust-center.yml\ntrust_center:\n  url: https://www.arcadia.com/security\nattestations:\n- framework: PCI-DSS\n  type: third-party processor attestation\n  scope: Stripe payment platform (not Arcadia itself)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Stripe and Plaid have their own stringent security policies and have been audited to achieve PCI Level 1\n    Service Provider and SOC 2 Type II compliance, respectively.\n- framework: SOC2\n  type: third-party\
  \ processor attestation\n  scope: Plaid (not Arcadia itself)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Stripe and Plaid have their own stringent security policies and have been audited to achieve PCI Level 1\n    Service Provider and SOC 2 Type II compliance, respectively.\n- framework: ISO27001\n  type: infrastructure provider attestation\n  scope: Amazon Web Services physical infrastructure (not Arcadia itself)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001\n- framework: SOC1\n  type: infrastructure provider attestation\n  scope: Amazon Web Services physical infrastructure (not Arcadia itself)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 1\n- framework: SOC2\n  type: infrastructure provider attestation\n  scope: Amazon Web Services physical infrastructure (not Arcadia itself)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2/SSAE 16/ISAE 3402\n"
source_yaml_url: https://artifacts.apis.io/arcadia-power/compliance/arcadia-power-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Arcadia's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- Clean Energy
- Utility Data
- Climate
- Sustainability
- Carbon Accounting
- Solar
- Storage
- EV Charging
- Decarbonization
- Energy Intelligence
- Utilities
---
