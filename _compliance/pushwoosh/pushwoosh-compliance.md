---
api_specs:
- filename: pushwoosh-messages-api-openapi.yml
  format: yaml
  label: Pushwoosh Messages API
  slug: pushwoosh-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pushwoosh/openapi/pushwoosh-messages-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: European clients; datacenter location within EU (Germany)
    text: For European clients, we guarantee our datacenter location within EU (Germany), as well as compliance with GDPR, Bundesdatenschutzgesetz (Data Protection Acts), and ISO 27 001.
    type: compliance statement
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: European clients; datacenter location within EU (Germany)
    text: For European clients, we guarantee our datacenter location within EU (Germany), as well as compliance with GDPR, Bundesdatenschutzgesetz (Data Protection Acts), and ISO 27 001.
    type: compliance statement
  trust_center:
    url: https://www.pushwoosh.com/
frameworks:
- GDPR
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Pushwoosh
provenance_date: '2026-11-10'
provider_name: Pushwoosh
provider_slug: pushwoosh
slug: pushwoosh-compliance
source_date: '2026-11-10'
source_filename: pushwoosh-compliance.yml
source_heading: Compliance
source_page: https://www.pushwoosh.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Pushwoosh\naid: pushwoosh\nurl: https://www.pushwoosh.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/pushwoosh-trust-center.yml\ntrust_center:\n  url: https://www.pushwoosh.com/\nattestations:\n- framework: ISO27001\n  type: compliance statement\n  scope: European clients; datacenter location within EU (Germany)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: For European clients, we guarantee our datacenter location within EU (Germany), as well as compliance with\n    GDPR, Bundesdatenschutzgesetz (Data Protection Acts), and ISO 27 001.\n- framework: GDPR\n  type: compliance\
  \ statement\n  scope: European clients; datacenter location within EU (Germany)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: For European clients, we guarantee our datacenter location within EU (Germany), as well as compliance with\n    GDPR, Bundesdatenschutzgesetz (Data Protection Acts), and ISO 27 001.\n"
source_yaml_url: https://artifacts.apis.io/pushwoosh/compliance/pushwoosh-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Pushwoosh's own page on 2026-11-10.
synthetic: false
tags:
- Notification
- Push
- Email
- SMS
- Multi-Channel
---
