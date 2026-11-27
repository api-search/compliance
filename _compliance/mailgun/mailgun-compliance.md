---
api_specs:
- filename: mailgun-domains-api-openapi.yml
  format: yaml
  label: Mailgun Domains API
  slug: mailgun-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailgun/openapi/mailgun-domains-api-openapi.yml
- filename: mailgun-events-api-openapi.yml
  format: yaml
  label: Mailgun Events API
  slug: mailgun-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailgun/openapi/mailgun-events-api-openapi.yml
- filename: mailgun-mailing-lists-api-openapi.yml
  format: yaml
  label: Mailgun Mailing Lists API
  slug: mailgun-mailing-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailgun/openapi/mailgun-mailing-lists-api-openapi.yml
- filename: mailgun-messages-api-openapi.yml
  format: yaml
  label: Mailgun Messages API
  slug: mailgun-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailgun/openapi/mailgun-messages-api-openapi.yml
- filename: mailgun-routes-api-openapi.yml
  format: yaml
  label: Mailgun Routes API
  slug: mailgun-routes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailgun/openapi/mailgun-routes-api-openapi.yml
- filename: mailgun-suppressions-api-openapi.yml
  format: yaml
  label: Mailgun Suppressions API
  slug: mailgun-suppressions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailgun/openapi/mailgun-suppressions-api-openapi.yml
- filename: mailgun-webhooks-api-openapi.yml
  format: yaml
  label: Mailgun Webhooks API
  slug: mailgun-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailgun/openapi/mailgun-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: August 1, 2024 to July 31, 2025
    report_access: unstated
    scope: Mailgun, Mailjet and Email on Acid Services
    text: Mailgun Technologies, Inc has completed its SOC2 Type II for Sinch Mailgun, Mailjet and Email on Acid Services for the August 1, 2024 to July 31, 2025 period.
    type: SOC 2 Type II
  - framework: SOC2
    issuer: null
    period: August 1, 2023 to July 31, 2024
    report_access: unstated
    scope: Mailgun, Mailjet and Email on Acid services
    text: Mailgun Technologies, Inc has completed its SOC2 Type II for Mailgun, Mailjet and Email on Acid Services for the August 1, 2023 to July 31, 2024 period.
    type: SOC 2 Type II
  - framework: ISO27001
    issuer: null
    period: '2024'
    report_access: unstated
    scope: Mailgun Technologies Inc.
    text: 2024 ISO27001 and ISO27701 Certificates now available for Mailgun Technologies Inc.
    type: certificate
  - framework: ISO27701
    issuer: null
    period: '2024'
    report_access: unstated
    scope: Mailgun Technologies Inc.
    text: 2024 ISO27001 and ISO27701 Certificates now available for Mailgun Technologies Inc.
    type: certificate
  - framework: DORA
    issuer: null
    period: null
    report_access: unstated
    scope: Sinch written agreements with customers, third parties and sub-contractors
    text: Sinch has written agreements with customers, third parties and sub-contractors that meet or exceed the requirements set forth by DORA.
    type: contractual alignment
  trust_center:
    url: https://trust.sinch.com:443/?product=mailgun
frameworks:
- DORA
- ISO27001
- ISO27701
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Mailgun
provenance_date: '2026-11-10'
provider_name: Mailgun
provider_slug: mailgun
slug: mailgun-compliance
source_date: '2026-11-10'
source_filename: mailgun-compliance.yml
source_heading: Compliance
source_page: https://trust.sinch.com:443/?product=mailgun
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Mailgun\naid: mailgun\nurl: https://trust.sinch.com:443/?product=mailgun\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/mailgun-trust-center.yml\ntrust_center:\n  url: https://trust.sinch.com:443/?product=mailgun\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: Mailgun, Mailjet and Email on Acid Services\n  period: August 1, 2024 to July 31, 2025\n  issuer: null\n  report_access: unstated\n  text: Mailgun Technologies, Inc has completed its SOC2 Type II for Sinch Mailgun, Mailjet and Email on Acid Services\n    for the August 1, 2024 to July 31, 2025 period.\n- framework: SOC2\n\
  \  type: SOC 2 Type II\n  scope: Mailgun, Mailjet and Email on Acid services\n  period: August 1, 2023 to July 31, 2024\n  issuer: null\n  report_access: unstated\n  text: Mailgun Technologies, Inc has completed its SOC2 Type II for Mailgun, Mailjet and Email on Acid Services\n    for the August 1, 2023 to July 31, 2024 period.\n- framework: ISO27001\n  type: certificate\n  scope: Mailgun Technologies Inc.\n  period: '2024'\n  issuer: null\n  report_access: unstated\n  text: 2024 ISO27001 and ISO27701 Certificates now available for Mailgun Technologies Inc.\n- framework: ISO27701\n  type: certificate\n  scope: Mailgun Technologies Inc.\n  period: '2024'\n  issuer: null\n  report_access: unstated\n  text: 2024 ISO27001 and ISO27701 Certificates now available for Mailgun Technologies Inc.\n- framework: DORA\n  type: contractual alignment\n  scope: Sinch written agreements with customers, third parties and sub-contractors\n  period: null\n  issuer: null\n  report_access: unstated\n  text:\
  \ Sinch has written agreements with customers, third parties and sub-contractors that meet or exceed the requirements\n    set forth by DORA.\n"
source_yaml_url: https://artifacts.apis.io/mailgun/compliance/mailgun-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Mailgun's own page on 2026-11-10.
synthetic: false
tags:
- Email
- Transactional Email
- SMTP
- Email Verification
- Email Delivery
- Messaging
---
