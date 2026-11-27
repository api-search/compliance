---
api_specs:
- filename: automat-extract-api-openapi.yml
  format: yaml
  label: Automat Extract API
  slug: automat-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/automat/openapi/automat-extract-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Ace (Automat Workforce) environment
    text: with SOC 2 controls
    type: controls referenced in product security description
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2, GDPR, HIPAA, and ISO 27001 certified
    type: certification claim
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Automat Workforce
    text: SOC 2, HIPAA, and GDPR coverage
    type: coverage claim
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Automat Workforce
    text: SOC 2, HIPAA, and GDPR coverage
    type: coverage claim
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.runautomat.com/
    text: SOC 2 Type 2 Compliant
    type: SOC 2 Type 2
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.runautomat.com/
    text: HIPAA Compliant
    type: HIPAA compliance
  trust_center:
    url: https://runautomat.com/llms.txt
frameworks:
- GDPR
- HIPAA
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Automat
provenance_date: '2026-11-09'
provider_name: Automat
provider_slug: automat
slug: automat-compliance
source_date: '2026-11-09'
source_filename: automat-compliance.yml
source_heading: Compliance
source_page: https://runautomat.com/llms.txt
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Automat\naid: automat\nurl: https://runautomat.com/llms.txt\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/automat-trust-center.yml\n  sources:\n  - https://runautomat.com/llms.txt\n  - https://trust.runautomat.com/\ntrust_center:\n  url: https://runautomat.com/llms.txt\nattestations:\n- framework: SOC2\n  type: controls referenced in product security description\n  scope: Ace (Automat Workforce) environment\n  period: null\n  issuer: null\n  report_access: unstated\n  text: with SOC 2 controls\n- framework: ISO27001\n  type: certification claim\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: SOC 2, GDPR, HIPAA, and ISO 27001 certified\n- framework: HIPAA\n  type: coverage claim\n  scope: Automat Workforce\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2, HIPAA, and GDPR coverage\n- framework: GDPR\n  type: coverage claim\n  scope: Automat Workforce\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2, HIPAA, and GDPR coverage\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 Compliant\n  source: https://trust.runautomat.com/\n- framework: HIPAA\n  type: HIPAA compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Compliant\n  source: https://trust.runautomat.com/\n"
source_yaml_url: https://artifacts.apis.io/automat/compliance/automat-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Automat's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise Saas
- Automation
- RPA
- Document Extraction
- Intelligent Document Processing
- iPaaS
- AI Agents
- Computer Use
- Document Processing
---
