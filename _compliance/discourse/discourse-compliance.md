---
api_specs:
- filename: discourse-admin-api-openapi.yml
  format: yaml
  label: Discourse Admin API
  slug: discourse-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discourse/openapi/discourse-admin-api-openapi.yml
- filename: discourse-backups-api-openapi.yml
  format: yaml
  label: Discourse Backups API
  slug: discourse-backups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discourse/openapi/discourse-backups-api-openapi.yml
- filename: discourse-badges-api-openapi.yml
  format: yaml
  label: Discourse Badges API
  slug: discourse-badges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discourse/openapi/discourse-badges-api-openapi.yml
- filename: discourse-categories-api-openapi.yml
  format: yaml
  label: Discourse Categories API
  slug: discourse-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discourse/openapi/discourse-categories-api-openapi.yml
- filename: discourse-discourse-calendar-events-api-openapi.yml
  format: yaml
  label: Discourse Calendar - Events API
  slug: discourse-discourse-calendar-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discourse/openapi/discourse-discourse-calendar-events-api-openapi.yml
- filename: discourse-groups-api-openapi.yml
  format: yaml
  label: Discourse Groups API
  slug: discourse-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discourse/openapi/discourse-groups-api-openapi.yml
- filename: discourse-invites-api-openapi.yml
  format: yaml
  label: Discourse Invites API
  slug: discourse-invites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discourse/openapi/discourse-invites-api-openapi.yml
- filename: discourse-notifications-api-openapi.yml
  format: yaml
  label: Discourse Notifications API
  slug: discourse-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discourse/openapi/discourse-notifications-api-openapi.yml
- filename: discourse-posts-api-openapi.yml
  format: yaml
  label: Discourse Posts API
  slug: discourse-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discourse/openapi/discourse-posts-api-openapi.yml
- filename: discourse-private-messages-api-openapi.yml
  format: yaml
  label: Discourse Private Messages API
  slug: discourse-private-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discourse/openapi/discourse-private-messages-api-openapi.yml
- filename: discourse-search-api-openapi.yml
  format: yaml
  label: Discourse Search API
  slug: discourse-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discourse/openapi/discourse-search-api-openapi.yml
- filename: discourse-site-api-openapi.yml
  format: yaml
  label: Discourse Site API
  slug: discourse-site-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discourse/openapi/discourse-site-api-openapi.yml
- filename: discourse-tags-api-openapi.yml
  format: yaml
  label: Discourse Tags API
  slug: discourse-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discourse/openapi/discourse-tags-api-openapi.yml
- filename: discourse-topics-api-openapi.yml
  format: yaml
  label: Discourse Topics API
  slug: discourse-topics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discourse/openapi/discourse-topics-api-openapi.yml
- filename: discourse-uploads-api-openapi.yml
  format: yaml
  label: Discourse Uploads API
  slug: discourse-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discourse/openapi/discourse-uploads-api-openapi.yml
- filename: discourse-users-api-openapi.yml
  format: yaml
  label: Discourse Users API
  slug: discourse-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discourse/openapi/discourse-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: We maintain SOC 2 Type II accreditation. Our current report is available at discourse.org/forms/soc2 .
    type: Type II accreditation
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: We maintain ISO 27001:2013 certification. Our current certificate is available at discourse.org/forms/iso27001 .
    type: certification (ISO 27001:2013)
  trust_center:
    url: https://www.discourse.org/security
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Discourse
provenance_date: '2026-11-09'
provider_name: Discourse
provider_slug: discourse
slug: discourse-compliance
source_date: '2026-11-09'
source_filename: discourse-compliance.yml
source_heading: Compliance
source_page: https://www.discourse.org/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Discourse\naid: discourse\nurl: https://www.discourse.org/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/discourse-trust-center.yml\ntrust_center:\n  url: https://www.discourse.org/security\nattestations:\n- framework: SOC2\n  type: Type II accreditation\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: We maintain SOC 2 Type II accreditation. Our current report is available at discourse.org/forms/soc2 .\n- framework: ISO27001\n  type: certification (ISO 27001:2013)\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: We maintain\
  \ ISO 27001:2013 certification. Our current certificate is available at discourse.org/forms/iso27001\n    .\n"
source_yaml_url: https://artifacts.apis.io/discourse/compliance/discourse-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Discourse's own page on 2026-11-09.
synthetic: false
tags:
- Community
- Forums
- Open Source
---
