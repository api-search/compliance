---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent auditor
    period: null
    report_access: unstated
    scope: Clearbit services
    text: Clearbit is SOC 2 Type 2 Compliant
    type: SOC 2 Type 2
  trust_center:
    url: https://clearbit.com/trust
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Clearbit Logo
provenance_date: '2026-11-09'
provider_name: Clearbit Logo
provider_slug: clearbit-logo
slug: clearbit-logo-compliance
source_date: '2026-11-09'
source_filename: clearbit-logo-compliance.yml
source_heading: Compliance
source_page: https://clearbit.com/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Clearbit Logo\naid: clearbit-logo\nurl: https://clearbit.com/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/clearbit-logo-trust-center.yml\ntrust_center:\n  url: https://clearbit.com/trust\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: Clearbit services\n  period: null\n  issuer: independent auditor\n  report_access: unstated\n  text: Clearbit is SOC 2 Type 2 Compliant\n"
source_yaml_url: https://artifacts.apis.io/clearbit-logo/compliance/clearbit-logo-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Clearbit Logo's own page on 2026-11-09.
synthetic: false
tags:
- Business
- Public APIs
---
