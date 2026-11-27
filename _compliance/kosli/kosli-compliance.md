---
api_specs:
- filename: kosli-openapi-generated.yml
  format: yaml
  label: Kosli API
  slug: kosli-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kosli/openapi/_ae-authored/kosli-openapi-generated.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Prescient Assurance
    period: null
    report_access: nda
    scope: information security practices, policies, procedures, and operations
    text: Customers and prospects can request access to the audit report here ( add a link to a form to fill out by your partners and customers to request SOC 2 report and accept NDA terms).
    type: SOC 2 Type II audit
  trust_center:
    url: https://www.kosli.com/security/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Kosli
provenance_date: '2026-11-09'
provider_name: Kosli
provider_slug: kosli
slug: kosli-compliance
source_date: '2026-11-09'
source_filename: kosli-compliance.yml
source_heading: Compliance
source_page: https://www.kosli.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Kosli\naid: kosli\nurl: https://www.kosli.com/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.kosli.com/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: information security practices, policies, procedures, and operations\n  period: null\n  issuer: Prescient Assurance\n  report_access: nda\n  text: Customers and prospects can request access to the audit report here ( add a link to a form to fill out by\n    your partners and customers to request SOC 2 report and accept NDA terms).\n"
source_yaml_url: https://artifacts.apis.io/kosli/compliance/kosli-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Kosli's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Governance
- Compliance
- DevOps
---
