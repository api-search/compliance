---
api_specs:
- filename: mrscraper-analytic-api-openapi.yml
  format: yaml
  label: MrScraper Analytic API
  slug: mrscraper-analytic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mrscraper/openapi/mrscraper-analytic-api-openapi.yml
- filename: mrscraper-auth-api-openapi.yml
  format: yaml
  label: MrScraper Auth API
  slug: mrscraper-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mrscraper/openapi/mrscraper-auth-api-openapi.yml
- filename: mrscraper-gateway-api-openapi.yml
  format: yaml
  label: MrScraper Gateway API
  slug: mrscraper-gateway-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mrscraper/openapi/mrscraper-gateway-api-openapi.yml
- filename: mrscraper-jobs-api-openapi.yml
  format: yaml
  label: MrScraper Jobs API
  slug: mrscraper-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mrscraper/openapi/mrscraper-jobs-api-openapi.yml
- filename: mrscraper-proxies-api-openapi.yml
  format: yaml
  label: MrScraper Proxies API
  slug: mrscraper-proxies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mrscraper/openapi/mrscraper-proxies-api-openapi.yml
- filename: mrscraper-results-api-openapi.yml
  format: yaml
  label: MrScraper Results API
  slug: mrscraper-results-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mrscraper/openapi/mrscraper-results-api-openapi.yml
- filename: mrscraper-storage-api-openapi.yml
  format: yaml
  label: MrScraper Storage API
  slug: mrscraper-storage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mrscraper/openapi/mrscraper-storage-api-openapi.yml
- filename: mrscraper-tasks-api-openapi.yml
  format: yaml
  label: MrScraper Tasks API
  slug: mrscraper-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mrscraper/openapi/mrscraper-tasks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: AICPA Trust Services Criteria
    text: Yes. MrScraper is SOC 2 compliant against the AICPA Trust Services Criteria, and the current status is published on our Trust Center.
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: information security management systems
    text: Yes. MrScraper is compliant with ISO 27001:2022, the current revision of the information security management standard.
    type: certification
  trust_center:
    url: https://mrscraper.com/trust
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: MrScraper
provenance_date: '2026-11-10'
provider_name: MrScraper
provider_slug: mrscraper
slug: mrscraper-compliance
source_date: '2026-11-10'
source_filename: mrscraper-compliance.yml
source_heading: Compliance
source_page: https://mrscraper.com/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: MrScraper\naid: mrscraper\nurl: https://mrscraper.com/trust\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://mrscraper.com/trust\nattestations:\n- framework: SOC2\n  type: certification\n  scope: AICPA Trust Services Criteria\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Yes. MrScraper is SOC 2 compliant against the AICPA Trust Services Criteria, and the current status is published\n    on our Trust Center.\n- framework: ISO27001\n  type: certification\n  scope: information security management systems\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Yes. MrScraper\
  \ is compliant with ISO 27001:2022, the current revision of the information security management\n    standard.\n"
source_yaml_url: https://artifacts.apis.io/mrscraper/compliance/mrscraper-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from MrScraper's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Web Scraping
- Data Extraction
- Proxies
- AI Agents
- MCP
- Search
- Browser Automation
---
