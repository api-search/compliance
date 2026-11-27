---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: each year
    report_access: unstated
    scope: systems tested for security, reliability, privacy, and data protection
    text: ScreenCloud is independently audited each year for SOC 2 Type 2, meaning our systems are tested for security, reliability, privacy, and data protection.
    type: SOC 2 Type 2 audit
  - framework: CyberEssentials
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: we’re Cyber Essentials certified and listed on the Blockmark registry
    type: certification
  trust_center:
    url: https://screencloud.com/security
frameworks:
- CyberEssentials
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: ScreenCloud
provenance_date: '2026-11-10'
provider_name: ScreenCloud
provider_slug: screencloud
slug: screencloud-compliance
source_date: '2026-11-10'
source_filename: screencloud-compliance.yml
source_heading: Compliance
source_page: https://screencloud.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: ScreenCloud\naid: screencloud\nurl: https://screencloud.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/screencloud-trust-center.yml\ntrust_center:\n  url: https://screencloud.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 audit\n  scope: systems tested for security, reliability, privacy, and data protection\n  period: each year\n  issuer: null\n  report_access: unstated\n  text: ScreenCloud is independently audited each year for SOC 2 Type 2, meaning our systems are tested for security,\n    reliability, privacy, and data protection.\n- framework: CyberEssentials\n\
  \  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: we’re Cyber Essentials certified and listed on the Blockmark registry\n"
source_yaml_url: https://artifacts.apis.io/screencloud/compliance/screencloud-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from ScreenCloud's own page on 2026-11-10.
synthetic: false
tags:
- Digital Signage
- Screens
- Content Management
- GraphQL
- Media
- Playlists
- Displays
---
