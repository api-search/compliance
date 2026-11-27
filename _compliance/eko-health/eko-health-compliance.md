---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Eko is Service Organization Control 2 (SOC 2) certified to keep health system and patient data safe.
    type: certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: patient and customer data
    text: Eko maintains HIPAA compliant policies, procedures, and technical safeguards for patient and customer data.
    type: compliance statement
  trust_center:
    url: https://support.ekohealth.com/hc/en-us/articles/13156748752155-Security-and-HIPAA
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Eko Health
provenance_date: '2026-11-09'
provider_name: Eko Health
provider_slug: eko-health
slug: eko-health-compliance
source_date: '2026-11-09'
source_filename: eko-health-compliance.yml
source_heading: Compliance
source_page: https://support.ekohealth.com/hc/en-us/articles/13156748752155-Security-and-HIPAA
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Eko Health\naid: eko-health\nurl: https://support.ekohealth.com/hc/en-us/articles/13156748752155-Security-and-HIPAA\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://support.ekohealth.com/hc/en-us/articles/13156748752155-Security-and-HIPAA\nattestations:\n- framework: SOC2\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Eko is Service Organization Control 2 (SOC 2) certified to keep health system and patient data safe.\n- framework: HIPAA\n  type: compliance statement\n  scope: patient and customer data\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: Eko maintains HIPAA compliant policies, procedures, and technical safeguards for patient and customer data.\n"
source_yaml_url: https://artifacts.apis.io/eko-health/compliance/eko-health-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Eko Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Medical Devices
- Digital Health
- Telehealth
- Artificial Intelligence
- Cardiology
- Remote Patient Monitoring
- Commerce
---
