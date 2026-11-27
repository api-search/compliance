---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: HITRUST
    issuer: HITRUST
    period: null
    report_access: unstated
    scope: The Brightside platform and all supporting infrastructure
    text: The Brightside platform and all supporting infrastructure has earned Certified status for information security by HITRUST and is HIPAA compliant.
    type: Certified status for information security
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: The Brightside platform and all supporting infrastructure
    text: is HIPAA compliant.
    type: Compliance
  trust_center:
    url: https://www.brightside.com/about/
frameworks:
- HIPAA
- HITRUST
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Brightside Health
provenance_date: '2026-11-09'
provider_name: Brightside Health
provider_slug: brightside-health
slug: brightside-health-compliance
source_date: '2026-11-09'
source_filename: brightside-health-compliance.yml
source_heading: Compliance
source_page: https://www.brightside.com/about/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Brightside Health\naid: brightside-health\nurl: https://www.brightside.com/about/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.brightside.com/about/\nattestations:\n- framework: HITRUST\n  type: Certified status for information security\n  scope: The Brightside platform and all supporting infrastructure\n  period: null\n  issuer: HITRUST\n  report_access: unstated\n  text: The Brightside platform and all supporting infrastructure has earned Certified status for information security\n    by HITRUST and is HIPAA compliant.\n- framework: HIPAA\n  type: Compliance\n  scope: The Brightside platform\
  \ and all supporting infrastructure\n  period: null\n  issuer: null\n  report_access: unstated\n  text: is HIPAA compliant.\n"
source_yaml_url: https://artifacts.apis.io/brightside-health/compliance/brightside-health-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Brightside Health's own page on 2026-11-09.
synthetic: false
tags:
- Telehealth
- Mental Health
- Behavioral Health
- Psychiatry
- Therapy
- Digital Health
- Healthcare
- Medication Management
- Substance Use Disorder
- Suicide Prevention
- Health Plans
---
