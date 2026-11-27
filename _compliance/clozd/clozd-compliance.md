---
api_specs:
- filename: clozd-programs-api-openapi.yml
  format: yaml
  label: Clozd /programs API
  slug: clozd-programs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clozd/openapi/clozd-programs-api-openapi.yml
- filename: clozd-programs-program-id-competitors-api-openapi.yml
  format: yaml
  label: Clozd /programs/:program Id/competitors API
  slug: clozd-programs-program-id-competitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clozd/openapi/clozd-programs-program-id-competitors-api-openapi.yml
- filename: clozd-programs-program-id-deals-api-openapi.yml
  format: yaml
  label: Clozd /programs/:program Id/deals API
  slug: clozd-programs-program-id-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clozd/openapi/clozd-programs-program-id-deals-api-openapi.yml
- filename: clozd-programs-program-id-deals-deal-id-api-openapi.yml
  format: yaml
  label: Clozd /programs/:program Id/deals/:deal ID API
  slug: clozd-programs-program-id-deals-deal-id-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clozd/openapi/clozd-programs-program-id-deals-deal-id-api-openapi.yml
- filename: clozd-programs-program-id-deals-import-api-openapi.yml
  format: yaml
  label: Clozd /programs/:program Id/deals/import API
  slug: clozd-programs-program-id-deals-import-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clozd/openapi/clozd-programs-program-id-deals-import-api-openapi.yml
- filename: clozd-programs-program-id-touchpoints-api-openapi.yml
  format: yaml
  label: Clozd /programs/:program Id/touchpoints API
  slug: clozd-programs-program-id-touchpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clozd/openapi/clozd-programs-program-id-touchpoints-api-openapi.yml
- filename: clozd-programs-program-id-touchpoints-touchpoint-id-api-openapi.yml
  format: yaml
  label: Clozd /programs/:program Id/touchpoints/:touchpoint ID API
  slug: clozd-programs-program-id-touchpoints-touchpoint-id-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clozd/openapi/clozd-programs-program-id-touchpoints-touchpoint-id-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Clozd platform and personal data safeguarding
    text: Clozd is ISO 27001 compliant and maintains industry-best technical and organizational security measures
    type: certification
  - framework: ISO27001
    issuer: null
    period: annually
    report_access: unstated
    scope: Clozd
    text: Clozd is audited annually for ISO 27001 and SOC 2 Type II compliance
    type: audit
  - framework: SOC2
    issuer: null
    period: annually
    report_access: unstated
    scope: Clozd
    text: Clozd is audited annually for ISO 27001 and SOC 2 Type II compliance
    type: audit
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: unstated
    source: https://trust.clozd.com/
    text: SOC 2 Type II
    type: Type II
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: unstated
    source: https://trust.clozd.com/
    text: ISO 27001:2022
    type: certificate
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: unstated
    source: https://trust.clozd.com/
    text: ISO 27701
    type: certificate
  trust_center:
    url: https://www.clozd.com/privacy/gdpr
frameworks:
- ISO27001
- ISO27701
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Clozd
provenance_date: '2026-11-09'
provider_name: Clozd
provider_slug: clozd
slug: clozd-compliance
source_date: '2026-11-09'
source_filename: clozd-compliance.yml
source_heading: Compliance
source_page: https://www.clozd.com/privacy/gdpr
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Clozd\naid: clozd\nurl: https://www.clozd.com/privacy/gdpr\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://trust.clozd.com/\n  - https://www.clozd.com/privacy/gdpr\ntrust_center:\n  url: https://www.clozd.com/privacy/gdpr\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Clozd platform and personal data safeguarding\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Clozd is ISO 27001 compliant and maintains industry-best technical and organizational security measures\n- framework: ISO27001\n  type: audit\n  scope: Clozd\n  period: annually\n  issuer: null\n  report_access:\
  \ unstated\n  text: Clozd is audited annually for ISO 27001 and SOC 2 Type II compliance\n- framework: SOC2\n  type: audit\n  scope: Clozd\n  period: annually\n  issuer: null\n  report_access: unstated\n  text: Clozd is audited annually for ISO 27001 and SOC 2 Type II compliance\n- framework: SOC2\n  type: Type II\n  scope: unstated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n  source: https://trust.clozd.com/\n- framework: ISO27001\n  type: certificate\n  scope: unstated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022\n  source: https://trust.clozd.com/\n- framework: ISO27701\n  type: certificate\n  scope: unstated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27701\n  source: https://trust.clozd.com/\n"
source_yaml_url: https://artifacts.apis.io/clozd/compliance/clozd-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Clozd's own page on 2026-11-09.
synthetic: false
tags:
- Win-Loss Analysis
- Customer Feedback
- Decision Intelligence
- Sales Intelligence
- Market Research
- Competitive Intelligence
- Voice of Customer
- Revenue Intelligence
- Software-as-a-Service
- MCP
- Agent-Native
---
