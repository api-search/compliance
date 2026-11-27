---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We sign a BAA, and HIPAA mode adds the protections healthcare offices need.
    type: HIPAA-ready, BAA available
  - framework: other
    issuer: FCC
    period: null
    report_access: unstated
    scope: null
    text: we file our CPNI certification with the FCC every year.
    type: FCC CPNI rules certification
  - framework: other
    issuer: FCC
    period: null
    report_access: unstated
    scope: null
    text: We're filed and current in the FCC's database, and we honor Do-Not-Originate lists.
    type: FCC Robocall Mitigation Database filing
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: handling of protected health information
    source: https://cannonvoip.com/post/security-compliance#report
    text: we maintain HIPAA-aligned safeguards for handling protected health information
    type: HIPAA-aligned safeguards and BAA
  - framework: other
    issuer: FCC
    period: null
    report_access: unstated
    scope: anti-robocall certification
    source: https://cannonvoip.com/post/security-compliance#report
    text: We're filed and current in the database
    type: FCC Robocall Mitigation Database filing
  trust_center:
    url: https://cannonvoip.com/trust
frameworks:
- HIPAA
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Cannon VoIP
provenance_date: '2026-11-09'
provider_name: Cannon VoIP
provider_slug: cannonvoip-com
slug: cannonvoip-com-compliance
source_date: '2026-11-09'
source_filename: cannonvoip-com-compliance.yml
source_heading: Compliance
source_page: https://cannonvoip.com/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Cannon VoIP\naid: cannonvoip-com\nurl: https://cannonvoip.com/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://cannonvoip.com/post/security-compliance#report\n  - https://cannonvoip.com/trust\ntrust_center:\n  url: https://cannonvoip.com/trust\nattestations:\n- framework: HIPAA\n  type: HIPAA-ready, BAA available\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We sign a BAA, and HIPAA mode adds the protections healthcare offices need.\n- framework: other\n  type: FCC CPNI rules certification\n  scope: null\n  period: null\n  issuer: FCC\n  report_access: unstated\n \
  \ text: we file our CPNI certification with the FCC every year.\n- framework: other\n  type: FCC Robocall Mitigation Database filing\n  scope: null\n  period: null\n  issuer: FCC\n  report_access: unstated\n  text: We're filed and current in the FCC's database, and we honor Do-Not-Originate lists.\n- framework: HIPAA\n  type: HIPAA-aligned safeguards and BAA\n  scope: handling of protected health information\n  period: null\n  issuer: null\n  report_access: unstated\n  text: we maintain HIPAA-aligned safeguards for handling protected health information\n  source: https://cannonvoip.com/post/security-compliance#report\n- framework: other\n  type: FCC Robocall Mitigation Database filing\n  scope: anti-robocall certification\n  period: null\n  issuer: FCC\n  report_access: unstated\n  text: We're filed and current in the database\n  source: https://cannonvoip.com/post/security-compliance#report\n"
source_yaml_url: https://artifacts.apis.io/cannonvoip-com/compliance/cannonvoip-com-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Cannon VoIP's own page on 2026-11-09.
synthetic: false
tags:
- VoIP
- Business Communications
- Cloud Phone System
- US
- Software-as-a-Service
---
