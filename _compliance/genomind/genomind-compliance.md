---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: other
    issuer: College of American Pathologists (CAP)
    period: null
    report_access: unstated
    scope: Genomind laboratory
    text: 'Our laboratory is fully certified and accredited by: College of American Pathologists (CAP) – the international leader in laboratory quality assurance.'
    type: CAP laboratory accreditation
  - framework: other
    issuer: Centers for Medicare and Medicaid Services (CMS)
    period: null
    report_access: unstated
    scope: Laboratory testing
    text: Clinical Laboratory Improvement Amendments (CLIA) – established by the United States Centers for Medicare and Medicaid Services (CMS).
    type: CLIA certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Genomind
    text: Genomind is fully compliant with HIPAA, HITECH, and GINA regulations.
    type: compliance statement
  trust_center:
    url: https://genomind.com/compliance/
frameworks:
- HIPAA
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Genomind
provenance_date: '2026-11-09'
provider_name: Genomind
provider_slug: genomind
slug: genomind-compliance
source_date: '2026-11-09'
source_filename: genomind-compliance.yml
source_heading: Compliance
source_page: https://genomind.com/compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Genomind\naid: genomind\nurl: https://genomind.com/compliance/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://genomind.com/compliance/\nattestations:\n- framework: other\n  type: CAP laboratory accreditation\n  scope: Genomind laboratory\n  period: null\n  issuer: College of American Pathologists (CAP)\n  report_access: unstated\n  text: 'Our laboratory is fully certified and accredited by: College of American Pathologists (CAP) – the international\n    leader in laboratory quality assurance.'\n- framework: other\n  type: CLIA certification\n  scope: Laboratory testing\n  period: null\n  issuer: Centers\
  \ for Medicare and Medicaid Services (CMS)\n  report_access: unstated\n  text: Clinical Laboratory Improvement Amendments (CLIA) – established by the United States Centers for Medicare\n    and Medicaid Services (CMS).\n- framework: HIPAA\n  type: compliance statement\n  scope: Genomind\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Genomind is fully compliant with HIPAA, HITECH, and GINA regulations.\n"
source_yaml_url: https://artifacts.apis.io/genomind/compliance/genomind-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Genomind's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Genomics
- Pharmacogenomics
- Precision Medicine
- Mental Health
- Diagnostics
- Laboratory
- Clinical Decision Support
- HIPAA
- EHR Integration
---
