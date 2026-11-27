---
api_specs:
- filename: mendix-apps-api-openapi.yml
  format: yaml
  label: Mendix Apps API
  slug: mendix-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mendix/openapi/mendix-apps-api-openapi.yml
- filename: mendix-environments-api-openapi.yml
  format: yaml
  label: Mendix Environments API
  slug: mendix-environments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mendix/openapi/mendix-environments-api-openapi.yml
- filename: mendix-logs-api-openapi.yml
  format: yaml
  label: Mendix Logs API
  slug: mendix-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mendix/openapi/mendix-logs-api-openapi.yml
- filename: mendix-packages-api-openapi.yml
  format: yaml
  label: Mendix Packages API
  slug: mendix-packages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mendix/openapi/mendix-packages-api-openapi.yml
- filename: mendix-tags-api-openapi.yml
  format: yaml
  label: Mendix Tags API
  slug: mendix-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mendix/openapi/mendix-tags-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Mendix holds the Type 2 report for SOC 1, SOC 2, and SOC 3 assurance reports.
    type: Type 2
  - framework: SOC2
    issuer: null
    period: November 1st till October 31st of the following year
    report_access: unstated
    scope: null
    text: The Mendix SOC2 audit period runs from November 1st till October 31st of the following year.
    type: Type 2
  - framework: SOC3
    issuer: null
    period: null
    report_access: public
    scope: null
    text: it can be freely distributed to the public
    type: Type 2
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Other reports that run on the same schedule include the SOC1, SOC3, ISAE3000, and ISAE3402 reports.
    type: ISAE3000 and ISAE3402 reports
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Mendix Cloud uptime
    text: Mendix has a certified Business Continuity Management System in place to safeguard the uptime agreed upon with our customers.
    type: certified Business Continuity Management System
  trust_center:
    url: https://www.mendix.com/trust/
frameworks:
- SOC1
- SOC2
- SOC3
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Mendix
provenance_date: '2026-11-10'
provider_name: Mendix
provider_slug: mendix
slug: mendix-compliance
source_date: '2026-11-10'
source_filename: mendix-compliance.yml
source_heading: Compliance
source_page: https://www.mendix.com/trust/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Mendix\naid: mendix\nurl: https://www.mendix.com/trust/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.mendix.com/trust/\nattestations:\n- framework: SOC1\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Mendix holds the Type 2 report for SOC 1, SOC 2, and SOC 3 assurance reports.\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: November 1st till October 31st of the following year\n  issuer: null\n  report_access: unstated\n  text: The Mendix SOC2 audit period runs from November 1st till October 31st of the following year.\n- framework:\
  \ SOC3\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: public\n  text: it can be freely distributed to the public\n- framework: other\n  type: ISAE3000 and ISAE3402 reports\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Other reports that run on the same schedule include the SOC1, SOC3, ISAE3000, and ISAE3402 reports.\n- framework: other\n  type: certified Business Continuity Management System\n  scope: Mendix Cloud uptime\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Mendix has a certified Business Continuity Management System in place to safeguard the uptime agreed upon\n    with our customers.\n"
source_yaml_url: https://artifacts.apis.io/mendix/compliance/mendix-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Mendix's own page on 2026-11-10.
synthetic: false
tags:
- Low-Code
- Application Development
- Enterprise Platform
- Application Lifecycle
- Deployment
- Governance
---
