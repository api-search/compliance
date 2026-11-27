---
api_specs:
- filename: found-business-openapi.yml
  format: yaml
  label: Found Banking
  slug: found-banking
  spec_type: OpenAPI
  url: https://artifacts.apis.io/found-business/openapi/_original/found-business-openapi.yml
- filename: found-business-openapi.yml
  format: yaml
  label: Found Bookkeeping
  slug: found-bookkeeping
  spec_type: OpenAPI
  url: https://artifacts.apis.io/found-business/openapi/_original/found-business-openapi.yml
- filename: found-business-openapi.yml
  format: yaml
  label: Found Taxes
  slug: found-taxes
  spec_type: OpenAPI
  url: https://artifacts.apis.io/found-business/openapi/_original/found-business-openapi.yml
- filename: found-business-openapi.yml
  format: yaml
  label: Found Invoicing
  slug: found-invoicing
  spec_type: OpenAPI
  url: https://artifacts.apis.io/found-business/openapi/_original/found-business-openapi.yml
- filename: found-business-openapi.yml
  format: yaml
  label: Found Contractor Management
  slug: found-contractors
  spec_type: OpenAPI
  url: https://artifacts.apis.io/found-business/openapi/_original/found-business-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: third party
    period: annually
    report_access: unstated
    scope: Information Security Program
    text: Our Information Security Program follows the criteria set forth by the SOC 2 Framework and is assessed annually by a third party.
    type: Information Security Program following SOC 2 criteria, assessed annually by a third party
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: All our payment partners
    text: All our payment partners are PCI-DSS certified to safeguard all payment information.
    type: payment partners certified
  trust_center:
    url: https://found.com/security
frameworks:
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Found
provenance_date: '2026-11-09'
provider_name: Found
provider_slug: found-business
slug: found-business-compliance
source_date: '2026-11-09'
source_filename: found-business-compliance.yml
source_heading: Compliance
source_page: https://found.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Found\naid: found-business\nurl: https://found.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/found-business-trust-center.yml\ntrust_center:\n  url: https://found.com/security\nattestations:\n- framework: SOC2\n  type: Information Security Program following SOC 2 criteria, assessed annually by a third party\n  scope: Information Security Program\n  period: annually\n  issuer: third party\n  report_access: unstated\n  text: Our Information Security Program follows the criteria set forth by the SOC 2 Framework and is assessed annually\n    by a third party.\n- framework: PCI-DSS\n  type:\
  \ payment partners certified\n  scope: All our payment partners\n  period: null\n  issuer: null\n  report_access: unstated\n  text: All our payment partners are PCI-DSS certified to safeguard all payment information.\n"
source_yaml_url: https://artifacts.apis.io/found-business/compliance/found-business-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Found's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Business Banking
- Bookkeeping
- Tax
- Self-Employed
---
