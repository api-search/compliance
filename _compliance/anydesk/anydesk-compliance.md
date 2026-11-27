---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: AnyDesk personal data processing
    text: We have implemented technical and organizational measures to ensure that data processing complies with the General Data Protection Regulation (GDPR).
    type: self-stated compliance with regulation
  trust_center:
    url: https://support.anydesk.com/docs/gdpr-compliance
frameworks:
- GDPR
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: AnyDesk
provenance_date: '2026-11-09'
provider_name: AnyDesk
provider_slug: anydesk
slug: anydesk-compliance
source_date: '2026-11-09'
source_filename: anydesk-compliance.yml
source_heading: Compliance
source_page: https://support.anydesk.com/docs/gdpr-compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: AnyDesk\naid: anydesk\nurl: https://support.anydesk.com/docs/gdpr-compliance\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://support.anydesk.com/docs/gdpr-compliance\nattestations:\n- framework: GDPR\n  type: self-stated compliance with regulation\n  scope: AnyDesk personal data processing\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We have implemented technical and organizational measures to ensure that data processing complies with the\n    General Data Protection Regulation (GDPR).\n"
source_yaml_url: https://artifacts.apis.io/anydesk/compliance/anydesk-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from AnyDesk's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Remote Work
- Remote Desktop
- Remote Access
- Remote Support
- IT Management
- REST API
- Security
---
