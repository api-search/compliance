---
api_specs:
- filename: getvocal-contact-api-openapi.yml
  format: yaml
  label: GetVocal Contact API
  slug: getvocal-contact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getvocal/openapi/getvocal-contact-api-openapi.yml
- filename: getvocal-llms-txt-api-openapi.yml
  format: yaml
  label: GetVocal Llms.txt API
  slug: getvocal-llms-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getvocal/openapi/getvocal-llms-txt-api-openapi.yml
- filename: getvocal-well-known-api-openapi.yml
  format: yaml
  label: GetVocal .well Known API
  slug: getvocal-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getvocal/openapi/getvocal-well-known-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001, SOC 2 and HIPAA postures available
    type: posture
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001, SOC 2 and HIPAA postures available
    type: posture
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001, SOC 2 and HIPAA postures available
    type: posture
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR and EU AI Act aligned
    type: aligned
  - framework: SOC2
    issuer: null
    period: '2026'
    report_access: on_request
    scope: null
    source: https://trust.getvocal.ai/
    text: Request GetVocal AI SOC 2 Type 2 2026
    type: Type 2
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: null
    source: https://trust.getvocal.ai/
    text: Request GetVocal Certificate-ISO-IEC 27001-2022-4716
    type: certificate
  trust_center:
    url: https://www.getvocal.ai/llms.txt
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
name: GetVocal
provenance_date: '2026-11-09'
provider_name: GetVocal
provider_slug: getvocal
slug: getvocal-compliance
source_date: '2026-11-09'
source_filename: getvocal-compliance.yml
source_heading: Compliance
source_page: https://www.getvocal.ai/llms.txt
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: GetVocal\naid: getvocal\nurl: https://www.getvocal.ai/llms.txt\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/getvocal-trust-center.yml\n  sources:\n  - https://trust.getvocal.ai/\n  - https://www.getvocal.ai/llms.txt\ntrust_center:\n  url: https://www.getvocal.ai/llms.txt\nattestations:\n- framework: ISO27001\n  type: posture\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001, SOC 2 and HIPAA postures available\n- framework: SOC2\n  type: posture\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001, SOC 2 and HIPAA\
  \ postures available\n- framework: HIPAA\n  type: posture\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001, SOC 2 and HIPAA postures available\n- framework: GDPR\n  type: aligned\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR and EU AI Act aligned\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: on_request\n  text: Request GetVocal AI SOC 2 Type 2 2026\n  source: https://trust.getvocal.ai/\n- framework: ISO27001\n  type: certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Request GetVocal Certificate-ISO-IEC 27001-2022-4716\n  source: https://trust.getvocal.ai/\n"
source_yaml_url: https://artifacts.apis.io/getvocal/compliance/getvocal-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from GetVocal's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Voice AI
- Conversational AI
- Customer Experience
- AI Agents
- Contact Center
- Agent Governance
- MCP
- Agent-Native
---
