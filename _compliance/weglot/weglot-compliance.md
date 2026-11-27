---
api_specs:
- filename: weglot-languages-api-openapi.yml
  format: yaml
  label: Weglot Languages API
  slug: weglot-languages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weglot/openapi/weglot-languages-api-openapi.yml
- filename: weglot-status-api-openapi.yml
  format: yaml
  label: Weglot Status API
  slug: weglot-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weglot/openapi/weglot-status-api-openapi.yml
- filename: weglot-translate-api-openapi.yml
  format: yaml
  label: Weglot Translate API
  slug: weglot-translate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weglot/openapi/weglot-translate-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 2 Weglot’s SOC 2 compliance reassures customer data protection based on 5 trust service principles.
    type: SOC 2 Type 2
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Your personal data and privacy at Weglot is also protected by General Data Protection Regulation under EU Law.
    type: GDPR compliance
  trust_center:
    url: https://www.weglot.com/security
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Weglot
provenance_date: '2026-11-10'
provider_name: Weglot
provider_slug: weglot
slug: weglot-compliance
source_date: '2026-11-10'
source_filename: weglot-compliance.yml
source_heading: Compliance
source_page: https://www.weglot.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Weglot\naid: weglot\nurl: https://www.weglot.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/weglot-trust-center.yml\ntrust_center:\n  url: https://www.weglot.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 Weglot’s SOC 2 compliance reassures customer data protection based on 5 trust service principles.\n- framework: GDPR\n  type: GDPR compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Your personal data and privacy at Weglot is\
  \ also protected by General Data Protection Regulation under EU\n    Law.\n"
source_yaml_url: https://artifacts.apis.io/weglot/compliance/weglot-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Weglot's own page on 2026-11-10.
synthetic: false
tags:
- Translation
- Localization
- Internationalization
- Machine Translation
- Multilingual
---
