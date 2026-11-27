---
api_specs:
- filename: refold-openapi-generated.yml
  format: yaml
  label: Refold API
  slug: refold-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/refold/openapi/_ae-authored/refold-openapi-generated.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Compliant
    type: Compliant status
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001 v2022 Compliant
    type: Compliant status
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: VAPT Compliant
    type: VAPT compliant status
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliant
    type: Compliant status
  trust_center:
    url: https://security.refold.ai/
frameworks:
- GDPR
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Refold
provenance_date: '2026-11-10'
provider_name: Refold
provider_slug: refold
slug: refold-compliance
source_date: '2026-11-10'
source_filename: refold-compliance.yml
source_heading: Compliance
source_page: https://security.refold.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Refold\naid: refold\nurl: https://security.refold.ai/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://security.refold.ai/\nattestations:\n- framework: SOC2\n  type: Compliant status\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Compliant\n- framework: ISO27001\n  type: Compliant status\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 v2022 Compliant\n- framework: other\n  type: VAPT compliant status\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: VAPT Compliant\n- framework: GDPR\n\
  \  type: Compliant status\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliant\n"
source_yaml_url: https://artifacts.apis.io/refold/compliance/refold-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Refold's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Integration
- Enterprise
- Automation
---
