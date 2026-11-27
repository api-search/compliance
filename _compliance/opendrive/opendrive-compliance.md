---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: other
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    text: SAS 70 Type II certified
    type: SAS 70 Type II certified
  - framework: SOC2
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    text: SOC 2 audited
    type: audit
  trust_center:
    url: https://www.opendrive.com/security
frameworks:
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: OpenDrive
provenance_date: '2026-11-10'
provider_name: OpenDrive
provider_slug: opendrive
slug: opendrive-compliance
source_date: '2026-11-10'
source_filename: opendrive-compliance.yml
source_heading: Compliance
source_page: https://www.opendrive.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: OpenDrive\naid: opendrive\nurl: https://www.opendrive.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.opendrive.com/security\nattestations:\n- framework: other\n  type: SAS 70 Type II certified\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: SAS 70 Type II certified\n- framework: SOC2\n  type: audit\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: SOC 2 audited\n"
source_yaml_url: https://artifacts.apis.io/opendrive/compliance/opendrive-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from OpenDrive's own page on 2026-11-10.
synthetic: false
tags:
- Cloud Storage
- Backup
- File Sync
- Collaboration
---
