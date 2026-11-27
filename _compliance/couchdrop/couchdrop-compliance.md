---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: third-party auditor
    period: annual
    report_access: on_request
    scope: null
    text: Couchdrop is SOC 2 Type II certified and has annual third-party SOC 2 audits
    type: Type II certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: dedicated HIPAA-ready infrastructure
    text: Couchdrop will sign a BAA and provides dedicated HIPAA-ready infrastructure
    type: HIPAA-ready, will sign BAA
  - framework: GDPR
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Couchdrop is audited for GDPR and has a DPA available to view in our Trust Center
    type: GDPR-ready, audited
  trust_center:
    url: https://www.couchdrop.io/privacy
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Couchdrop
provenance_date: '2026-11-09'
provider_name: Couchdrop
provider_slug: couchdrop
slug: couchdrop-compliance
source_date: '2026-11-09'
source_filename: couchdrop-compliance.yml
source_heading: Compliance
source_page: https://www.couchdrop.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Couchdrop\naid: couchdrop\nurl: https://www.couchdrop.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.couchdrop.io/privacy\nattestations:\n- framework: SOC2\n  type: Type II certification\n  scope: null\n  period: annual\n  issuer: third-party auditor\n  report_access: on_request\n  text: Couchdrop is SOC 2 Type II certified and has annual third-party SOC 2 audits\n- framework: HIPAA\n  type: HIPAA-ready, will sign BAA\n  scope: dedicated HIPAA-ready infrastructure\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Couchdrop will sign a BAA and provides dedicated HIPAA-ready\
  \ infrastructure\n- framework: GDPR\n  type: GDPR-ready, audited\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Couchdrop is audited for GDPR and has a DPA available to view in our Trust Center\n"
source_yaml_url: https://artifacts.apis.io/couchdrop/compliance/couchdrop-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Couchdrop's own page on 2026-11-09.
synthetic: false
tags:
- File Transfer
- SFTP
- Automation
- Integration
- Cloud
---
