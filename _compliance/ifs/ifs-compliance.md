---
api_specs:
- filename: ifs-finance-api-openapi.yml
  format: yaml
  label: IFS Finance API
  slug: ifs-finance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ifs/openapi/ifs-finance-api-openapi.yml
- filename: ifs-inventory-api-openapi.yml
  format: yaml
  label: IFS Inventory API
  slug: ifs-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ifs/openapi/ifs-inventory-api-openapi.yml
- filename: ifs-procurement-api-openapi.yml
  format: yaml
  label: IFS Procurement API
  slug: ifs-procurement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ifs/openapi/ifs-procurement-api-openapi.yml
- filename: ifs-work-orders-api-openapi.yml
  format: yaml
  label: IFS Work Orders API
  slug: ifs-work-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ifs/openapi/ifs-work-orders-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Information Security Management System (ISMS)
    text: By using industry best practice security frameworks including ISO 27001, NIST SP 800-171, SSAE18/ISAE3402/ISAE3000 to create and maintain our Information Security Management System (ISMS)
    type: Framework used for ISMS
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Information Security Management System (ISMS)
    text: NIST SP 800-171
    type: Framework used for ISMS (NIST SP 800-171)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Information security practices
    text: Our information security practices are subject to external independent reviews.
    type: External independent reviews
  trust_center:
    url: https://www.ifs.com/en/about/trust-center
frameworks:
- ISO27001
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: IFS
provenance_date: '2026-11-09'
provider_name: IFS
provider_slug: ifs
slug: ifs-compliance
source_date: '2026-11-09'
source_filename: ifs-compliance.yml
source_heading: Compliance
source_page: https://www.ifs.com/en/about/trust-center
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: IFS\naid: ifs\nurl: https://www.ifs.com/en/about/trust-center\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.ifs.com/en/about/trust-center\nattestations:\n- framework: ISO27001\n  type: Framework used for ISMS\n  scope: Information Security Management System (ISMS)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: By using industry best practice security frameworks including ISO 27001, NIST SP 800-171, SSAE18/ISAE3402/ISAE3000\n    to create and maintain our Information Security Management System (ISMS)\n- framework: other\n  type: Framework used for ISMS (NIST SP 800-171)\n  scope:\
  \ Information Security Management System (ISMS)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: NIST SP 800-171\n- framework: other\n  type: External independent reviews\n  scope: Information security practices\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our information security practices are subject to external independent reviews.\n"
source_yaml_url: https://artifacts.apis.io/ifs/compliance/ifs-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from IFS's own page on 2026-11-09.
synthetic: false
tags:
- ERP
- Field Service Management
- Asset Management
- Manufacturing
- Energy
- Cloud
- Sweden
---
