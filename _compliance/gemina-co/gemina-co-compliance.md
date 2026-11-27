---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliant
    type: compliance statement
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA Compliant
    type: compliance statement
  - framework: other
    issuer: AppSec Labs
    period: null
    report_access: unstated
    scope: staging API and console
    text: AppSec Labs completed an independent compliance penetration test of Gemina’s staging API and console.
    type: penetration test
  trust_center:
    url: https://www.gemina.co/trust-center
frameworks:
- CCPA
- GDPR
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: gemina-co
provenance_date: '2026-11-09'
provider_name: gemina-co
provider_slug: gemina-co
slug: gemina-co-compliance
source_date: '2026-11-09'
source_filename: gemina-co-compliance.yml
source_heading: Compliance
source_page: https://www.gemina.co/trust-center
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: gemina-co\naid: gemina-co\nurl: https://www.gemina.co/trust-center\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.gemina.co/trust-center\nattestations:\n- framework: GDPR\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliant\n- framework: CCPA\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA Compliant\n- framework: other\n  type: penetration test\n  scope: staging API and console\n  period: null\n  issuer: AppSec Labs\n  report_access: unstated\n  text: AppSec\
  \ Labs completed an independent compliance penetration test of Gemina’s staging API and console.\n"
source_yaml_url: https://artifacts.apis.io/gemina-co/compliance/gemina-co-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from gemina-co's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Document AI
- Extraction
- Search
- Analytics
- Chat
---
