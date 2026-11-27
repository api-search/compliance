---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Blueprint platform
    text: Blueprint is HIPAA compliant to ensure your clients’ health information remains protected and confidential.
    type: compliance statement
  - framework: SOC2
    issuer: null
    period: annually the past 6 years
    report_access: unstated
    scope: security and privacy practices
    text: Our security and privacy practices have been externally audited annually the past 6 years.
    type: Type 2 audit
  trust_center:
    url: https://www.blueprint.ai/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Blueprint Health
provenance_date: '2026-11-09'
provider_name: Blueprint Health
provider_slug: blueprint-health
slug: blueprint-health-compliance
source_date: '2026-11-09'
source_filename: blueprint-health-compliance.yml
source_heading: Compliance
source_page: https://www.blueprint.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Blueprint Health\naid: blueprint-health\nurl: https://www.blueprint.ai/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.blueprint.ai/\nattestations:\n- framework: HIPAA\n  type: compliance statement\n  scope: Blueprint platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Blueprint is HIPAA compliant to ensure your clients’ health information remains protected and confidential.\n- framework: SOC2\n  type: Type 2 audit\n  scope: security and privacy practices\n  period: annually the past 6 years\n  issuer: null\n  report_access: unstated\n  text: Our security and privacy practices\
  \ have been externally audited annually the past 6 years.\n"
source_yaml_url: https://artifacts.apis.io/blueprint-health/compliance/blueprint-health-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Blueprint Health's own page on 2026-11-09.
synthetic: false
tags:
- Health Tech
- Artificial Intelligence
- Therapy
- Software-as-a-Service
- Mental Health
---
