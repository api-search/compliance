---
api_specs:
- filename: geneos-rest-api-api-openapi.yml
  format: yaml
  label: Geneos REST API
  slug: geneos-rest-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geneos/openapi/geneos-rest-api-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    text: View ISO certificate
    type: certificate
  - framework: GDPR
    issuer: unstated
    period: null
    report_access: unstated
    scope: data classification process
    text: complies with regulations like the GDPR
    type: stated compliance
  trust_center:
    url: https://www.itrsgroup.com/about/security-center
frameworks:
- GDPR
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Geneos
provenance_date: '2026-11-09'
provider_name: Geneos
provider_slug: geneos
slug: geneos-compliance
source_date: '2026-11-09'
source_filename: geneos-compliance.yml
source_heading: Compliance
source_page: https://www.itrsgroup.com/about/security-center
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Geneos\naid: geneos\nurl: https://www.itrsgroup.com/about/security-center\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/geneos-trust-center.yml\ntrust_center:\n  url: https://www.itrsgroup.com/about/security-center\nattestations:\n- framework: ISO27001\n  type: certificate\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: View ISO certificate\n- framework: GDPR\n  type: stated compliance\n  scope: data classification process\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: complies with regulations like the GDPR\n"
source_yaml_url: https://artifacts.apis.io/geneos/compliance/geneos-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Geneos's own page on 2026-11-09.
synthetic: false
tags:
- APM
- Capital Markets
- Infrastructure
- ITRS
- Monitoring
- Observability
- Real-Time
- Trading Systems
- XML-RPC
- OpenAPI
---
