---
api_specs:
- filename: openapi.json
  format: json
  label: BenchSci API
  slug: benchsci-api
  spec_type: OpenAPI
  url: https://api.benchsci.com/openapi.json
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: BenchSci is SOC 2 Type II attested
    type: Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: compliant with GDPR, CCPA, and applicable US state privacy laws
    type: compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: compliant with GDPR, CCPA, and applicable US state privacy laws
    type: compliance
  trust_center:
    url: https://www.benchsci.com/security
frameworks:
- CCPA
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: BenchSci
provenance_date: '2026-11-09'
provider_name: BenchSci
provider_slug: benchsci
slug: benchsci-compliance
source_date: '2026-11-09'
source_filename: benchsci-compliance.yml
source_heading: Compliance
source_page: https://www.benchsci.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: BenchSci\naid: benchsci\nurl: https://www.benchsci.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/benchsci-trust-center.yml\ntrust_center:\n  url: https://www.benchsci.com/security\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: BenchSci is SOC 2 Type II attested\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: compliant with GDPR, CCPA, and applicable US state privacy laws\n- framework: CCPA\n  type: compliance\n  scope: null\n\
  \  period: null\n  issuer: null\n  report_access: unstated\n  text: compliant with GDPR, CCPA, and applicable US state privacy laws\n"
source_yaml_url: https://artifacts.apis.io/benchsci/compliance/benchsci-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from BenchSci's own page on 2026-11-09.
synthetic: false
tags:
- Biopharma
- Drug Discovery
- Artificial Intelligence
- Reagents
- Antibodies
- Scientific Research
- Life Sciences
- Preclinical Research
---
