---
api_specs:
- filename: mailosaur-analysis-api-openapi.yml
  format: yaml
  label: Mailosaur Analysis API
  slug: mailosaur-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailosaur/openapi/mailosaur-analysis-api-openapi.yml
- filename: mailosaur-devices-api-openapi.yml
  format: yaml
  label: Mailosaur Devices API
  slug: mailosaur-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailosaur/openapi/mailosaur-devices-api-openapi.yml
- filename: mailosaur-files-api-openapi.yml
  format: yaml
  label: Mailosaur Files API
  slug: mailosaur-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailosaur/openapi/mailosaur-files-api-openapi.yml
- filename: mailosaur-messages-api-openapi.yml
  format: yaml
  label: Mailosaur Messages API
  slug: mailosaur-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailosaur/openapi/mailosaur-messages-api-openapi.yml
- filename: mailosaur-previews-api-openapi.yml
  format: yaml
  label: Mailosaur Previews API
  slug: mailosaur-previews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailosaur/openapi/mailosaur-previews-api-openapi.yml
- filename: mailosaur-servers-api-openapi.yml
  format: yaml
  label: Mailosaur Servers API
  slug: mailosaur-servers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailosaur/openapi/mailosaur-servers-api-openapi.yml
- filename: mailosaur-usage-api-openapi.yml
  format: yaml
  label: Mailosaur Usage API
  slug: mailosaur-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailosaur/openapi/mailosaur-usage-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II
    type: Type II
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022
    type: Certificate
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: null
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA COMPLIANT
    type: null
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI DSS - SAQ A
    type: SAQ A
  trust_center:
    url: https://trust.mailosaur.com/
frameworks:
- CCPA
- GDPR
- ISO27001
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Mailosaur
provenance_date: '2026-11-10'
provider_name: Mailosaur
provider_slug: mailosaur
slug: mailosaur-compliance
source_date: '2026-11-10'
source_filename: mailosaur-compliance.yml
source_heading: Compliance
source_page: https://trust.mailosaur.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Mailosaur\naid: mailosaur\nurl: https://trust.mailosaur.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.mailosaur.com/\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n- framework: ISO27001\n  type: Certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: CCPA\n  type: null\n  scope: null\n  period: null\n\
  \  issuer: null\n  report_access: unstated\n  text: CCPA COMPLIANT\n- framework: PCI-DSS\n  type: SAQ A\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS - SAQ A\n"
source_yaml_url: https://artifacts.apis.io/mailosaur/compliance/mailosaur-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Mailosaur's own page on 2026-11-10.
synthetic: false
tags:
- Email Testing
- SMS Testing
- Developer Tools
- QA Automation
- CI/CD
- SMTP
- TOTP
- Deliverability
---
