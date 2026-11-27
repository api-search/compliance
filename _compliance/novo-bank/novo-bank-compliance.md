---
api_specs:
- filename: novo-bank-openapi.yml
  format: yaml
  label: Novo Accounts
  slug: novo-accounts
  spec_type: OpenAPI
  url: https://artifacts.apis.io/novo-bank/openapi/_original/novo-bank-openapi.yml
- filename: novo-bank-openapi.yml
  format: yaml
  label: Novo Transactions
  slug: novo-transactions
  spec_type: OpenAPI
  url: https://artifacts.apis.io/novo-bank/openapi/_original/novo-bank-openapi.yml
- filename: novo-bank-openapi.yml
  format: yaml
  label: Novo Payments
  slug: novo-payments
  spec_type: OpenAPI
  url: https://artifacts.apis.io/novo-bank/openapi/_original/novo-bank-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Novo's controls
    text: Our SOC 2 Type II controls, continuous testing, and transparent documentation help you evaluate Novo’s security posture.
    type: Type II
  trust_center:
    url: https://trust.novo.co/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Novo
provenance_date: '2026-11-10'
provider_name: Novo
provider_slug: novo-bank
slug: novo-bank-compliance
source_date: '2026-11-10'
source_filename: novo-bank-compliance.yml
source_heading: Compliance
source_page: https://trust.novo.co/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Novo\naid: novo-bank\nurl: https://trust.novo.co/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/novo-bank-trust-center.yml\ntrust_center:\n  url: https://trust.novo.co/\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: Novo's controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our SOC 2 Type II controls, continuous testing, and transparent documentation help you evaluate Novo’s security\n    posture.\n"
source_yaml_url: https://artifacts.apis.io/novo-bank/compliance/novo-bank-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Novo's own page on 2026-11-10.
synthetic: false
tags:
- Banking
- Business Banking
- Fintech
- Small Business
- Freelancers
- Payments
---
