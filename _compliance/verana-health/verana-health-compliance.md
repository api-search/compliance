---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: de-identified registry datasets
    text: An independent team of qualified personnel at Verana Health de-identifies all registry data into high-quality, HIPAA-compliant datasets.
    type: HIPAA-compliant datasets
  trust_center:
    url: https://veranahealth.com/patient-privacy/
frameworks:
- HIPAA
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Verana Health
provenance_date: '2026-11-10'
provider_name: Verana Health
provider_slug: verana-health
slug: verana-health-compliance
source_date: '2026-11-10'
source_filename: verana-health-compliance.yml
source_heading: Compliance
source_page: https://veranahealth.com/patient-privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Verana Health\naid: verana-health\nurl: https://veranahealth.com/patient-privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://veranahealth.com/patient-privacy/\nattestations:\n- framework: HIPAA\n  type: HIPAA-compliant datasets\n  scope: de-identified registry datasets\n  period: null\n  issuer: null\n  report_access: unstated\n  text: An independent team of qualified personnel at Verana Health de-identifies all registry data into high-quality,\n    HIPAA-compliant datasets.\n"
source_yaml_url: https://artifacts.apis.io/verana-health/compliance/verana-health-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Verana Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Life Sciences
- Healthcare
- Real-World Data
- Clinical Research
- Data Analytics
- Ophthalmology
- HIPAA
---
