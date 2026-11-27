---
api_specs:
- filename: webrix-api-openapi.json
  format: json
  label: Willow API API
  slug: willow-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webrix/openapi/_original/webrix-api-openapi.json
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: December 1, 2025 to February 28, 2026
    report_access: on_request
    scope: Managed SaaS environment; Security and Confidentiality trust services criteria
    text: The Security and Confidentiality trust services criteria, examined over a three-month observation period from December 1, 2025 to February 28, 2026.
    type: Type II
  - framework: other
    issuer: Sayfer
    period: August 2026 test
    report_access: public
    scope: Willow Platform
    text: 'Sayfer''s public attestation for the August 2026 test: scope, methodology, retest outcome, and residual risk.'
    type: Penetration test attestation (public certificate)
  - framework: other
    issuer: Cyber Answer
    period: May 2026 review
    report_access: public
    scope: Endpoint sensor code, reviewed to a specific commit
    text: Cyber Answer's public attestation for the May 2026 review of the sensor
    type: Sensor code review attestation (public)
  trust_center:
    url: https://trust.withwillow.ai/
frameworks:
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Willow AI Governance Control Plane
provenance_date: '2026-11-10'
provider_name: Willow AI Governance Control Plane
provider_slug: webrix
slug: webrix-compliance
source_date: '2026-11-10'
source_filename: webrix-compliance.yml
source_heading: Compliance
source_page: https://trust.withwillow.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Willow AI Governance Control Plane\naid: webrix\nurl: https://trust.withwillow.ai/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.withwillow.ai/\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: Managed SaaS environment; Security and Confidentiality trust services criteria\n  period: December 1, 2025 to February 28, 2026\n  issuer: null\n  report_access: on_request\n  text: The Security and Confidentiality trust services criteria, examined over a three-month observation period\n    from December 1, 2025 to February 28, 2026.\n- framework: other\n  type: Penetration test attestation\
  \ (public certificate)\n  scope: Willow Platform\n  period: August 2026 test\n  issuer: Sayfer\n  report_access: public\n  text: 'Sayfer''s public attestation for the August 2026 test: scope, methodology, retest outcome, and residual\n    risk.'\n- framework: other\n  type: Sensor code review attestation (public)\n  scope: Endpoint sensor code, reviewed to a specific commit\n  period: May 2026 review\n  issuer: Cyber Answer\n  report_access: public\n  text: Cyber Answer's public attestation for the May 2026 review of the sensor\n"
source_yaml_url: https://artifacts.apis.io/webrix/compliance/webrix-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Willow AI Governance Control Plane's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Governance
- Platform
- Enterprise
---
