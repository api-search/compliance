---
api_specs:
- filename: mailmodo-campaigns-api-openapi.yml
  format: yaml
  label: Mailmodo Campaigns API
  slug: mailmodo-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailmodo/openapi/mailmodo-campaigns-api-openapi.yml
- filename: mailmodo-contact-lists-api-openapi.yml
  format: yaml
  label: Mailmodo Contact Lists API
  slug: mailmodo-contact-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailmodo/openapi/mailmodo-contact-lists-api-openapi.yml
- filename: mailmodo-contacts-api-openapi.yml
  format: yaml
  label: Mailmodo Contacts API
  slug: mailmodo-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailmodo/openapi/mailmodo-contacts-api-openapi.yml
- filename: mailmodo-events-api-openapi.yml
  format: yaml
  label: Mailmodo Events API
  slug: mailmodo-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailmodo/openapi/mailmodo-events-api-openapi.yml
- filename: mailmodo-templates-api-openapi.yml
  format: yaml
  label: Mailmodo Templates API
  slug: mailmodo-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailmodo/openapi/mailmodo-templates-api-openapi.yml
- filename: mailmodo-addevent-api-openapi.yml
  format: yaml
  label: Mailmodo Add Event API
  slug: mailmodo-addevent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailmodo/openapi/mailmodo-addevent-api-openapi.yml
- filename: mailmodo-addtolist-api-openapi.yml
  format: yaml
  label: Mailmodo Add To List API
  slug: mailmodo-addtolist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailmodo/openapi/mailmodo-addtolist-api-openapi.yml
- filename: mailmodo-bulktriggercampaign-api-openapi.yml
  format: yaml
  label: Mailmodo Bulktrigger Campaign API
  slug: mailmodo-bulktriggercampaign-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailmodo/openapi/mailmodo-bulktriggercampaign-api-openapi.yml
- filename: mailmodo-getallcontactlists-api-openapi.yml
  format: yaml
  label: Mailmodo Get All Contact Lists API
  slug: mailmodo-getallcontactlists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailmodo/openapi/mailmodo-getallcontactlists-api-openapi.yml
- filename: mailmodo-getalltemplates-api-openapi.yml
  format: yaml
  label: Mailmodo Get All Templates API
  slug: mailmodo-getalltemplates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailmodo/openapi/mailmodo-getalltemplates-api-openapi.yml
- filename: mailmodo-getcontactdetails-api-openapi.yml
  format: yaml
  label: Mailmodo Get Contact Details API
  slug: mailmodo-getcontactdetails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailmodo/openapi/mailmodo-getcontactdetails-api-openapi.yml
- filename: mailmodo-hooks-api-openapi.yml
  format: yaml
  label: Mailmodo Hooks API
  slug: mailmodo-hooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailmodo/openapi/mailmodo-hooks-api-openapi.yml
- filename: mailmodo-removefromlist-api-openapi.yml
  format: yaml
  label: Mailmodo Remove From List API
  slug: mailmodo-removefromlist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailmodo/openapi/mailmodo-removefromlist-api-openapi.yml
- filename: mailmodo-triggercampaign-api-openapi.yml
  format: yaml
  label: Mailmodo Trigger Campaign API
  slug: mailmodo-triggercampaign-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailmodo/openapi/mailmodo-triggercampaign-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: third-party assessors
    period: annual
    report_access: unstated
    scope: null
    text: Mailmodo undergoes annual audits by a third party to ensure SOC 2 Type 2 compliance.
    type: SOC 2 Type 2 audit
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Mailmodo is both SOC 2 Type 2 and GDPR compliant.
    type: GDPR compliance
  trust_center:
    url: https://www.mailmodo.com/security/
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Mailmodo
provenance_date: '2026-11-10'
provider_name: Mailmodo
provider_slug: mailmodo
slug: mailmodo-compliance
source_date: '2026-11-10'
source_filename: mailmodo-compliance.yml
source_heading: Compliance
source_page: https://www.mailmodo.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Mailmodo\naid: mailmodo\nurl: https://www.mailmodo.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/mailmodo-trust-center.yml\ntrust_center:\n  url: https://www.mailmodo.com/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 audit\n  scope: null\n  period: annual\n  issuer: third-party assessors\n  report_access: unstated\n  text: Mailmodo undergoes annual audits by a third party to ensure SOC 2 Type 2 compliance.\n- framework: GDPR\n  type: GDPR compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Mailmodo is both SOC 2 Type 2 and\
  \ GDPR compliant.\n"
source_yaml_url: https://artifacts.apis.io/mailmodo/compliance/mailmodo-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Mailmodo's own page on 2026-11-10.
synthetic: false
tags:
- Email
- Interactive Email
- AMP for Email
- Marketing Automation
- Transactional Email
- Campaigns
- Journeys
- Customer Engagement
---
