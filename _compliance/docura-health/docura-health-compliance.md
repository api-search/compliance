---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA SOC 2
    type: null
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA SOC 2
    type: null
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://docurahealth.com/
    text: HIPAA compliant
    type: null
  trust_center:
    url: https://trust.docurahealth.com/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Docura Health
provenance_date: '2026-11-09'
provider_name: Docura Health
provider_slug: docura-health
slug: docura-health-compliance
source_date: '2026-11-09'
source_filename: docura-health-compliance.yml
source_heading: Compliance
source_page: https://trust.docurahealth.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Docura Health\naid: docura-health\nurl: https://trust.docurahealth.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/docura-health-trust-center.yml\n  sources:\n  - https://docurahealth.com/\n  - https://trust.docurahealth.com/\ntrust_center:\n  url: https://trust.docurahealth.com/\nattestations:\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA SOC 2\n- framework: SOC2\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA SOC 2\n- framework: HIPAA\n  type: null\n  scope: null\n\
  \  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA compliant\n  source: https://docurahealth.com/\n"
source_yaml_url: https://artifacts.apis.io/docura-health/compliance/docura-health-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Docura Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Health
- Medical-Legal
- Medical Records
- Impairment Rating
- IME
- QME
- Workers Compensation
- HIPAA
- Clinical Documentation
---
