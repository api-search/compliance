---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Administration of the SSR when performed through the CLI
    text: Administration of the SSR is only Common Criteria-certified when performed through the CLI.
    type: Common Criteria certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: OpenSSH v7.4 and OpenSSL v1.0.2k used by the SSR
    text: These versions are certified for FIPS 140-2 compliance.
    type: FIPS 140-2 certification
  trust_center:
    url: https://docs.128technology.com/docs/cc_fips_intro/
frameworks:
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: 128 Technology
provenance_date: '2026-11-09'
provider_name: 128 Technology
provider_slug: 128-technology
slug: 128-technology-compliance
source_date: '2026-11-09'
source_filename: 128-technology-compliance.yml
source_heading: Compliance
source_page: https://docs.128technology.com/docs/cc_fips_intro/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: 128 Technology\naid: 128-technology\nurl: https://docs.128technology.com/docs/cc_fips_intro/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://docs.128technology.com/docs/cc_fips_intro/\nattestations:\n- framework: other\n  type: Common Criteria certification\n  scope: Administration of the SSR when performed through the CLI\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Administration of the SSR is only Common Criteria-certified when performed through the CLI.\n- framework: other\n  type: FIPS 140-2 certification\n  scope: OpenSSH v7.4 and OpenSSL v1.0.2k used by the SSR\n  period:\
  \ null\n  issuer: null\n  report_access: unstated\n  text: These versions are certified for FIPS 140-2 compliance.\n"
source_yaml_url: https://artifacts.apis.io/128-technology/compliance/128-technology-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from 128 Technology's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Networking
- SD-WAN
- Routing
- Network Management
- Session Smart Networking
- NETCONF
- YANG
- Telecommunications
- Infrastructure
---
