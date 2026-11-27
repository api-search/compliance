---
api_specs:
- filename: agentaos-ai-bank-accounts-api-openapi.yml
  format: yaml
  label: AgentaOS Bank Accounts API
  slug: agentaos-ai-bank-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentaos-ai/openapi/agentaos-ai-bank-accounts-api-openapi.yml
- filename: agentaos-ai-businesses-api-openapi.yml
  format: yaml
  label: AgentaOS Businesses API
  slug: agentaos-ai-businesses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentaos-ai/openapi/agentaos-ai-businesses-api-openapi.yml
- filename: agentaos-ai-checkouts-api-openapi.yml
  format: yaml
  label: AgentaOS Checkouts API
  slug: agentaos-ai-checkouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentaos-ai/openapi/agentaos-ai-checkouts-api-openapi.yml
- filename: agentaos-ai-customers-api-openapi.yml
  format: yaml
  label: AgentaOS Customers API
  slug: agentaos-ai-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentaos-ai/openapi/agentaos-ai-customers-api-openapi.yml
- filename: agentaos-ai-discount-codes-api-openapi.yml
  format: yaml
  label: AgentaOS Discount Codes API
  slug: agentaos-ai-discount-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentaos-ai/openapi/agentaos-ai-discount-codes-api-openapi.yml
- filename: agentaos-ai-invoices-api-openapi.yml
  format: yaml
  label: AgentaOS Invoices API
  slug: agentaos-ai-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentaos-ai/openapi/agentaos-ai-invoices-api-openapi.yml
- filename: agentaos-ai-payment-links-api-openapi.yml
  format: yaml
  label: AgentaOS Payment Links API
  slug: agentaos-ai-payment-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentaos-ai/openapi/agentaos-ai-payment-links-api-openapi.yml
- filename: agentaos-ai-subscriptions-api-openapi.yml
  format: yaml
  label: AgentaOS Subscriptions API
  slug: agentaos-ai-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentaos-ai/openapi/agentaos-ai-subscriptions-api-openapi.yml
- filename: agentaos-ai-transactions-api-openapi.yml
  format: yaml
  label: AgentaOS Transactions API
  slug: agentaos-ai-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentaos-ai/openapi/agentaos-ai-transactions-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: Stripe
    period: null
    report_access: unstated
    scope: Card checkout via Stripe PCI DSS hosted fields; merchants do not bring systems into PCI scope for that checkout
    text: Card details are collected by Stripe through Stripe's PCI DSS hosted fields.
    type: Card data handling via Stripe hosted fields
  trust_center:
    url: https://agentaos.ai/security
frameworks:
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: AgentaOS
provenance_date: '2026-11-09'
provider_name: AgentaOS
provider_slug: agentaos-ai
slug: agentaos-ai-compliance
source_date: '2026-11-09'
source_filename: agentaos-ai-compliance.yml
source_heading: Compliance
source_page: https://agentaos.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: AgentaOS\naid: agentaos-ai\nurl: https://agentaos.ai/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://agentaos.ai/security\nattestations:\n- framework: PCI-DSS\n  type: Card data handling via Stripe hosted fields\n  scope: Card checkout via Stripe PCI DSS hosted fields; merchants do not bring systems into PCI scope for that\n    checkout\n  period: null\n  issuer: Stripe\n  report_access: unstated\n  text: Card details are collected by Stripe through Stripe's PCI DSS hosted fields.\n"
source_yaml_url: https://artifacts.apis.io/agentaos-ai/compliance/agentaos-ai-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from AgentaOS's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Billing
- Software-as-a-Service
- Freelancers
- Artificial Intelligence
---
