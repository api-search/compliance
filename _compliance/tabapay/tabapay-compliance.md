---
api_specs:
- filename: tabapay-3d-secure-api-openapi.yml
  format: yaml
  label: TabaPay 3D Secure API
  slug: tabapay-3d-secure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tabapay/openapi/tabapay-3d-secure-api-openapi.yml
- filename: tabapay-account-api-openapi.yml
  format: yaml
  label: TabaPay Account API
  slug: tabapay-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tabapay/openapi/tabapay-account-api-openapi.yml
- filename: tabapay-bank-api-openapi.yml
  format: yaml
  label: TabaPay Bank API
  slug: tabapay-bank-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tabapay/openapi/tabapay-bank-api-openapi.yml
- filename: tabapay-card-api-openapi.yml
  format: yaml
  label: TabaPay Card API
  slug: tabapay-card-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tabapay/openapi/tabapay-card-api-openapi.yml
- filename: tabapay-client-api-openapi.yml
  format: yaml
  label: TabaPay Client API
  slug: tabapay-client-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tabapay/openapi/tabapay-client-api-openapi.yml
- filename: tabapay-fxrate-api-openapi.yml
  format: yaml
  label: TabaPay FXRate API
  slug: tabapay-fxrate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tabapay/openapi/tabapay-fxrate-api-openapi.yml
- filename: tabapay-health-api-openapi.yml
  format: yaml
  label: TabaPay Health API
  slug: tabapay-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tabapay/openapi/tabapay-health-api-openapi.yml
- filename: tabapay-key-api-openapi.yml
  format: yaml
  label: TabaPay Key API
  slug: tabapay-key-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tabapay/openapi/tabapay-key-api-openapi.yml
- filename: tabapay-ledger-api-openapi.yml
  format: yaml
  label: TabaPay Ledger API
  slug: tabapay-ledger-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tabapay/openapi/tabapay-ledger-api-openapi.yml
- filename: tabapay-ofac-api-openapi.yml
  format: yaml
  label: TabaPay OFAC API
  slug: tabapay-ofac-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tabapay/openapi/tabapay-ofac-api-openapi.yml
- filename: tabapay-subclient-api-openapi.yml
  format: yaml
  label: TabaPay SubClient API
  slug: tabapay-subclient-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tabapay/openapi/tabapay-subclient-api-openapi.yml
- filename: tabapay-tag-api-openapi.yml
  format: yaml
  label: TabaPay Tag API
  slug: tabapay-tag-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tabapay/openapi/tabapay-tag-api-openapi.yml
- filename: tabapay-transaction-api-openapi.yml
  format: yaml
  label: TabaPay Transaction API
  slug: tabapay-transaction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tabapay/openapi/tabapay-transaction-api-openapi.yml
- filename: tabapay-user-api-openapi.yml
  format: yaml
  label: TabaPay User API
  slug: tabapay-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tabapay/openapi/tabapay-user-api-openapi.yml
- filename: tabapay-verification-api-openapi.yml
  format: yaml
  label: TabaPay Verification API
  slug: tabapay-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tabapay/openapi/tabapay-verification-api-openapi.yml
- filename: tabapay-transaction-request-api-openapi.yml
  format: yaml
  label: TabaPay Transaction Request API
  slug: tabapay-transaction-request-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tabapay/openapi/tabapay-transaction-request-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: TabaPay services
    text: TabaPay is a PCI Level 1 Service Provider.
    type: Level 1 Service Provider
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: TabaPay
    text: TabaPay is SOC 1 Type II Certified.
    type: Type II
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: TabaPay
    text: TabaPay is SOC 2 Type II Certified.
    type: Type II
  trust_center:
    url: https://developers.tabapay.com/reference/pcisoc
frameworks:
- PCI-DSS
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: TabaPay
provenance_date: '2026-11-10'
provider_name: TabaPay
provider_slug: tabapay
slug: tabapay-compliance
source_date: '2026-11-10'
source_filename: tabapay-compliance.yml
source_heading: Compliance
source_page: https://developers.tabapay.com/reference/pcisoc
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: TabaPay\naid: tabapay\nurl: https://developers.tabapay.com/reference/pcisoc\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://developers.tabapay.com/reference/pcisoc\nattestations:\n- framework: PCI-DSS\n  type: Level 1 Service Provider\n  scope: TabaPay services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TabaPay is a PCI Level 1 Service Provider.\n- framework: SOC1\n  type: Type II\n  scope: TabaPay\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TabaPay is SOC 1 Type II Certified.\n- framework: SOC2\n  type: Type II\n  scope: TabaPay\n  period: null\n  issuer:\
  \ null\n  report_access: unstated\n  text: TabaPay is SOC 2 Type II Certified.\n"
source_yaml_url: https://artifacts.apis.io/tabapay/compliance/tabapay-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from TabaPay's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Instant Payments
- Money Movement
- Payouts
- Cards
- Real-Time Payments
- ACH
---
