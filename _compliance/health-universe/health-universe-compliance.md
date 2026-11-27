---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: Annual
    report_access: unstated
    scope: security, availability, and privacy controls
    text: Annual third-party audit of security, availability, and privacy controls.
    type: SOC 2 Type II
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA Compliant BAAs with every partner.
    type: HIPAA Compliant
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: §170.315(b)(11) for AI-based clinical decision support
    text: Certified §170.315(b)(11) for AI-based clinical decision support.
    type: ONC Health IT Certified
  trust_center:
    url: https://www.healthuniverse.com/security
frameworks:
- HIPAA
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Health Universe
provenance_date: '2026-11-09'
provider_name: Health Universe
provider_slug: health-universe
slug: health-universe-compliance
source_date: '2026-11-09'
source_filename: health-universe-compliance.yml
source_heading: Compliance
source_page: https://www.healthuniverse.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Health Universe\naid: health-universe\nurl: https://www.healthuniverse.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.healthuniverse.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: security, availability, and privacy controls\n  period: Annual\n  issuer: null\n  report_access: unstated\n  text: Annual third-party audit of security, availability, and privacy controls.\n- framework: HIPAA\n  type: HIPAA Compliant\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Compliant BAAs with every partner.\n- framework: other\n\
  \  type: ONC Health IT Certified\n  scope: §170.315(b)(11) for AI-based clinical decision support\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Certified §170.315(b)(11) for AI-based clinical decision support.\n"
source_yaml_url: https://artifacts.apis.io/health-universe/compliance/health-universe-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Health Universe's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Artificial Intelligence
- AI Agents
- Clinical
- Deployment
- FHIR
- A2A
- HIPAA
- Life Sciences
---
