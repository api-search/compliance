---
claim_count: 9
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: TrueContext's SOC 2 Type II, HIPAA, and Title 21 CFR Part 11 reports are available upon request under NDA.
    type: SOC 2 Type II report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: TrueContext's SOC 2 Type II, HIPAA, and Title 21 CFR Part 11 reports are available upon request under NDA.
    type: HIPAA report
  - framework: other
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: TrueContext's SOC 2 Type II, HIPAA, and Title 21 CFR Part 11 reports are available upon request under NDA.
    type: Title 21 CFR Part 11 report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: HIPAA Security Rule and HITECH act
    source: https://truecontext.com/product/compliance-security/
    text: TrueContext is third-party-verified for the HIPAA Security Rule and HITECH act to ensure all electronic health information is protected.
    type: third-party verified
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: security, confidentiality, and availability of customer data within the platform
    source: https://truecontext.com/product/compliance-security/
    text: Internal controls for security, confidentiality, and availability of customer data within the platform are regularly evaluated and certified.
    type: SOC 2 Type II audited
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: validity, security, and audit visibility of electronic records and electronic signatures
    source: https://truecontext.com/product/compliance-security/
    text: Title 21 CFR part 11 audited.
    type: Title 21 CFR Part 11 audited
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: null
    source: https://trust.truecontext.com/%20(TrueContext%20Trust%20Center,%20powered%20by%20Conveyor);%20https://truecontext.com/product/compliance-security/
    text: TrueContext's SOC 2 Type II, HIPAA, and Title 21 CFR Part 11 reports are available upon request under NDA.
    type: SOC 2 Type II report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: nda
    scope: null
    source: https://trust.truecontext.com/%20(TrueContext%20Trust%20Center,%20powered%20by%20Conveyor);%20https://truecontext.com/product/compliance-security/
    text: TrueContext's SOC 2 Type II, HIPAA, and Title 21 CFR Part 11 reports are available upon request under NDA.
    type: HIPAA report
  - framework: other
    issuer: null
    period: null
    report_access: nda
    scope: null
    source: https://trust.truecontext.com/%20(TrueContext%20Trust%20Center,%20powered%20by%20Conveyor);%20https://truecontext.com/product/compliance-security/
    text: TrueContext's SOC 2 Type II, HIPAA, and Title 21 CFR Part 11 reports are available upon request under NDA.
    type: Title 21 CFR Part 11 report
  trust_center:
    url: https://trust.truecontext.com/
frameworks:
- HIPAA
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: TrueContext
provenance_date: '2026-11-10'
provider_name: TrueContext
provider_slug: truecontext
slug: truecontext-compliance
source_date: '2026-11-10'
source_filename: truecontext-compliance.yml
source_heading: Compliance
source_page: https://trust.truecontext.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: TrueContext\naid: truecontext\nurl: https://trust.truecontext.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/truecontext-trust-center.yml\n  sources:\n  - https://truecontext.com/product/compliance-security/\n  - https://trust.truecontext.com/\n  - https://trust.truecontext.com/%20(TrueContext%20Trust%20Center,%20powered%20by%20Conveyor);%20https://truecontext.com/product/compliance-security/\ntrust_center:\n  url: https://trust.truecontext.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: TrueContext's\
  \ SOC 2 Type II, HIPAA, and Title 21 CFR Part 11 reports are available upon request under NDA.\n- framework: HIPAA\n  type: HIPAA report\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: TrueContext's SOC 2 Type II, HIPAA, and Title 21 CFR Part 11 reports are available upon request under NDA.\n- framework: other\n  type: Title 21 CFR Part 11 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: TrueContext's SOC 2 Type II, HIPAA, and Title 21 CFR Part 11 reports are available upon request under NDA.\n- framework: HIPAA\n  type: third-party verified\n  scope: HIPAA Security Rule and HITECH act\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TrueContext is third-party-verified for the HIPAA Security Rule and HITECH act to ensure all electronic\n    health information is protected.\n  source: https://truecontext.com/product/compliance-security/\n- framework: SOC2\n  type: SOC 2 Type II audited\n  scope: security,\
  \ confidentiality, and availability of customer data within the platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Internal controls for security, confidentiality, and availability of customer data within the platform are\n    regularly evaluated and certified.\n  source: https://truecontext.com/product/compliance-security/\n- framework: other\n  type: Title 21 CFR Part 11 audited\n  scope: validity, security, and audit visibility of electronic records and electronic signatures\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Title 21 CFR part 11 audited.\n  source: https://truecontext.com/product/compliance-security/\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: TrueContext's SOC 2 Type II, HIPAA, and Title 21 CFR Part 11 reports are available upon request under NDA.\n  source: https://trust.truecontext.com/%20(TrueContext%20Trust%20Center,%20powered%20by%20Conveyor);%20https://truecontext.com/product/compliance-security/\n\
  - framework: HIPAA\n  type: HIPAA report\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: TrueContext's SOC 2 Type II, HIPAA, and Title 21 CFR Part 11 reports are available upon request under NDA.\n  source: https://trust.truecontext.com/%20(TrueContext%20Trust%20Center,%20powered%20by%20Conveyor);%20https://truecontext.com/product/compliance-security/\n- framework: other\n  type: Title 21 CFR Part 11 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: TrueContext's SOC 2 Type II, HIPAA, and Title 21 CFR Part 11 reports are available upon request under NDA.\n  source: https://trust.truecontext.com/%20(TrueContext%20Trust%20Center,%20powered%20by%20Conveyor);%20https://truecontext.com/product/compliance-security/\n"
source_yaml_url: https://artifacts.apis.io/truecontext/compliance/truecontext-compliance.yml
stated_fields:
- attestations
summary_line: 9 quoted statements, read from TrueContext's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Field Service Management
- Mobile Forms
- Workflow Automation
- Data Collection
- Field Intelligence
- Low-Code
- Dispatch
- Inspection
- Compliance
---
