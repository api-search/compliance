---
api_specs:
- filename: finout-cost-api-openapi.yml
  format: yaml
  label: Finout Cost API
  slug: finout-cost-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finout/openapi/finout-cost-api-openapi.yml
- filename: finout-costguard-api-openapi.yml
  format: yaml
  label: Finout CostGuard API
  slug: finout-costguard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finout/openapi/finout-costguard-api-openapi.yml
- filename: finout-endpoints-api-openapi.yml
  format: yaml
  label: Finout Endpoints API
  slug: finout-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finout/openapi/finout-endpoints-api-openapi.yml
- filename: finout-query-language-api-openapi.yml
  format: yaml
  label: Finout Query Language API
  slug: finout-query-language-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finout/openapi/finout-query-language-api-openapi.yml
- filename: finout-virtual-tag-metadata-api-openapi.yml
  format: yaml
  label: Finout Virtual Tag Metadata API
  slug: finout-virtual-tag-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finout/openapi/finout-virtual-tag-metadata-api-openapi.yml
- filename: finout-virtual-tags-api-openapi.yml
  format: yaml
  label: Finout Virtual Tags API
  slug: finout-virtual-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finout/openapi/finout-virtual-tags-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: Information Security Management System (ISMS)
    text: Finout is ISO/IEC 27001:2022 certified, reflecting our commitment to maintaining a strong Information Security Management System (ISMS).
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: security, availability, and confidentiality
    text: Finout is SOC 2 Type II certified, affirming that our systems and processes meet rigorous standards for security, availability, and confidentiality.
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data handling
    text: Finout is fully compliant with the General Data Protection Regulation (GDPR), ensuring that all personal data is handled lawfully, transparently, and with strict security safeguards.
    type: compliance statement
  trust_center:
    url: https://www.finout.io/compliance
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Finout
provenance_date: '2026-11-09'
provider_name: Finout
provider_slug: finout
slug: finout-compliance
source_date: '2026-11-09'
source_filename: finout-compliance.yml
source_heading: Compliance
source_page: https://www.finout.io/compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Finout\naid: finout\nurl: https://www.finout.io/compliance\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.finout.io/compliance\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Information Security Management System (ISMS)\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Finout is ISO/IEC 27001:2022 certified, reflecting our commitment to maintaining a strong Information Security\n    Management System (ISMS).\n- framework: SOC2\n  type: certification\n  scope: security, availability, and confidentiality\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: Finout is SOC 2 Type II certified, affirming that our systems and processes meet rigorous standards for\n    security, availability, and confidentiality.\n- framework: GDPR\n  type: compliance statement\n  scope: personal data handling\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Finout is fully compliant with the General Data Protection Regulation (GDPR), ensuring that all personal\n    data is handled lawfully, transparently, and with strict security safeguards.\n"
source_yaml_url: https://artifacts.apis.io/finout/compliance/finout-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Finout's own page on 2026-11-09.
synthetic: false
tags:
- Budgets
- Costs
- FinOps
---
