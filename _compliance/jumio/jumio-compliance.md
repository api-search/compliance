---
api_specs:
- filename: jumio-callback-asyncapi.yml
  format: yaml
  label: Jumio Callback / Webhook
  slug: callback
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/jumio/asyncapi/jumio-callback-asyncapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Not stated
    text: SOC 2 Compliant
    type: Compliance badge
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Not stated
    text: ISO 27001 Compliant
    type: Compliance badge
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Not stated
    text: PCI DSS 4.0.1 Compliant
    type: Compliance badge
  trust_center:
    url: https://trust.jumio.com/
frameworks:
- ISO27001
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Jumio
provenance_date: '2026-11-09'
provider_name: Jumio
provider_slug: jumio
slug: jumio-compliance
source_date: '2026-11-09'
source_filename: jumio-compliance.yml
source_heading: Compliance
source_page: https://trust.jumio.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Jumio\naid: jumio\nurl: https://trust.jumio.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/jumio-trust-center.yml\ntrust_center:\n  url: https://trust.jumio.com/\nattestations:\n- framework: SOC2\n  type: Compliance badge\n  scope: Not stated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Compliant\n- framework: ISO27001\n  type: Compliance badge\n  scope: Not stated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 Compliant\n- framework: PCI-DSS\n  type: Compliance badge\n  scope: Not stated\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: PCI DSS 4.0.1 Compliant\n"
source_yaml_url: https://artifacts.apis.io/jumio/compliance/jumio-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Jumio's own page on 2026-11-09.
synthetic: false
tags:
- KYC
- Identity Verification
- Biometrics
- AML
- Fraud Prevention
- KYX
---
