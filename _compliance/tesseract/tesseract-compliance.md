---
api_specs:
- filename: tesseract-clients-api-openapi.yml
  format: yaml
  label: Tesseract Clients API
  slug: tesseract-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tesseract/openapi/tesseract-clients-api-openapi.yml
- filename: tesseract-health-api-openapi.yml
  format: yaml
  label: Tesseract Health API
  slug: tesseract-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tesseract/openapi/tesseract-health-api-openapi.yml
- filename: tesseract-insights-api-openapi.yml
  format: yaml
  label: Tesseract Insights API
  slug: tesseract-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tesseract/openapi/tesseract-insights-api-openapi.yml
- filename: tesseract-strategies-api-openapi.yml
  format: yaml
  label: Tesseract Strategies API
  slug: tesseract-strategies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tesseract/openapi/tesseract-strategies-api-openapi.yml
- filename: tesseract-vaults-api-openapi.yml
  format: yaml
  label: Tesseract Vaults API
  slug: tesseract-vaults-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tesseract/openapi/tesseract-vaults-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: other
    issuer: null
    period: null
    report_access: nda
    scope: Custody, portfolio management and transfer services for DCV service
    text: MiCA CASP authorisation (Tesseract Investment Oy)
    type: MiCA CASP authorisation
  - framework: ISO27001
    issuer: Prescient Security
    period: valid to October 2027
    report_access: nda
    scope: null
    text: valid to October 2027, audited by Prescient Security. Reports available on request under NDA.
    type: ISO/IEC 27001:2022 certification
  - framework: SOC2
    issuer: Prescient Security
    period: three consecutive years
    report_access: nda
    scope: null
    text: three consecutive years, audited by Prescient Security. Reports available on request under NDA.
    type: SOC 2 Type II
  trust_center:
    url: https://docs.tesseract.fi/tesseract/security-and-compliance.md
frameworks:
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Tesseract
provenance_date: '2026-11-10'
provider_name: Tesseract
provider_slug: tesseract
slug: tesseract-compliance
source_date: '2026-11-10'
source_filename: tesseract-compliance.yml
source_heading: Compliance
source_page: https://docs.tesseract.fi/tesseract/security-and-compliance.md
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Tesseract\naid: tesseract\nurl: https://docs.tesseract.fi/tesseract/security-and-compliance.md\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://docs.tesseract.fi/tesseract/security-and-compliance.md\nattestations:\n- framework: other\n  type: MiCA CASP authorisation\n  scope: Custody, portfolio management and transfer services for DCV service\n  period: null\n  issuer: null\n  report_access: nda\n  text: MiCA CASP authorisation (Tesseract Investment Oy)\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 certification\n  scope: null\n  period: valid to October 2027\n  issuer: Prescient Security\n  report_access:\
  \ nda\n  text: valid to October 2027, audited by Prescient Security. Reports available on request under NDA.\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: three consecutive years\n  issuer: Prescient Security\n  report_access: nda\n  text: three consecutive years, audited by Prescient Security. Reports available on request under NDA.\n"
source_yaml_url: https://artifacts.apis.io/tesseract/compliance/tesseract-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Tesseract's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Cryptocurrency
- DeFi
- Lending
- Yield
- Digital Assets
- Ethereum
- MiCA
- Vault
- Institutional
---
