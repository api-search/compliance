---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC3
    issuer: null
    period: null
    report_access: unstated
    scope: Apple Private Cloud Compute
    text: Apple Private Cloud Compute SOC 3 audit reports
    type: audit reports
  trust_center:
    url: https://support.apple.com/guide/certifications/welcome/web
frameworks:
- SOC3
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Apple Safari
provenance_date: '2026-11-09'
provider_name: Apple Safari
provider_slug: apple-safari
slug: apple-safari-compliance
source_date: '2026-11-09'
source_filename: apple-safari-compliance.yml
source_heading: Compliance
source_page: https://support.apple.com/guide/certifications/welcome/web
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Apple Safari\naid: apple-safari\nurl: https://support.apple.com/guide/certifications/welcome/web\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/apple-safari-trust-center.yml\ntrust_center:\n  url: https://support.apple.com/guide/certifications/welcome/web\nattestations:\n- framework: SOC3\n  type: audit reports\n  scope: Apple Private Cloud Compute\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Apple Private Cloud Compute SOC 3 audit reports\n"
source_yaml_url: https://artifacts.apis.io/apple-safari/compliance/apple-safari-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Apple Safari's own page on 2026-11-09.
synthetic: false
tags:
- Apple
- Browser
- Privacy
- Web Browser
- Webkit
---
