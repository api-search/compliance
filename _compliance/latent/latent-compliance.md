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
    text: Latent receives third SOC 2 Type II Report!
    type: Type II
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA-compliant data handling
    type: null
  trust_center:
    url: https://security.latenthealth.com/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Latent
provenance_date: '2026-11-09'
provider_name: Latent
provider_slug: latent
slug: latent-compliance
source_date: '2026-11-09'
source_filename: latent-compliance.yml
source_heading: Compliance
source_page: https://security.latenthealth.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Latent\naid: latent\nurl: https://security.latenthealth.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://security.latenthealth.com/\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Latent receives third SOC 2 Type II Report!\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA-compliant data handling\n"
source_yaml_url: https://artifacts.apis.io/latent/compliance/latent-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Latent's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Health Systems
- Pharmacy
- Prior Authorization
- Medication Access
- Clinical AI
- 340B
- EHR Integration
- Artificial Intelligence
---
