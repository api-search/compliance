---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Prescient Assurance
    period: null
    report_access: on_request
    scope: information security practices, policies, procedures, and operations
    text: Equip Health, Inc successfully completed the AICPA Service Organization Control (SOC) 2 Type I audit.
    type: SOC 2 Type 1 audit
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: platform
    text: Our platform is HIPAA-compliant and SOC2 certified, ensuring your data is always protected.
    type: HIPAA-compliant platform statement
  trust_center:
    url: https://equip.health/security
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Equip Health
provenance_date: '2026-11-09'
provider_name: Equip Health
provider_slug: equip-health
slug: equip-health-compliance
source_date: '2026-11-09'
source_filename: equip-health-compliance.yml
source_heading: Compliance
source_page: https://equip.health/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Equip Health\naid: equip-health\nurl: https://equip.health/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://equip.health/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 1 audit\n  scope: information security practices, policies, procedures, and operations\n  period: null\n  issuer: Prescient Assurance\n  report_access: on_request\n  text: Equip Health, Inc successfully completed the AICPA Service Organization Control (SOC) 2 Type I audit.\n- framework: HIPAA\n  type: HIPAA-compliant platform statement\n  scope: platform\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: Our platform is HIPAA-compliant and SOC2 certified, ensuring your data is always protected.\n"
source_yaml_url: https://artifacts.apis.io/equip-health/compliance/equip-health-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Equip Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Digital Health
- Telehealth
- Mental Health
- Eating Disorder Treatment
- Virtual Care
- Health Insurance
---
