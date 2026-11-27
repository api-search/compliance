---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Ambient.ai platform
    text: SOC 2 Type II certified
    type: Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: platform architecture
    text: GDPR and CCPA-aligned architecture
    type: alignment
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: platform architecture
    text: GDPR and CCPA-aligned architecture
    type: alignment
  trust_center:
    url: https://www.ambient.ai/ai-info
frameworks:
- CCPA
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Ambient.ai
provenance_date: '2026-11-09'
provider_name: Ambient.ai
provider_slug: ambientai
slug: ambientai-compliance
source_date: '2026-11-09'
source_filename: ambientai-compliance.yml
source_heading: Compliance
source_page: https://www.ambient.ai/ai-info
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Ambient.ai\naid: ambientai\nurl: https://www.ambient.ai/ai-info\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/ambientai-trust-center.yml\ntrust_center:\n  url: https://www.ambient.ai/ai-info\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: Ambient.ai platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II certified\n- framework: GDPR\n  type: alignment\n  scope: platform architecture\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR and CCPA-aligned architecture\n- framework: CCPA\n  type: alignment\n  scope: platform architecture\n\
  \  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR and CCPA-aligned architecture\n"
source_yaml_url: https://artifacts.apis.io/ambientai/compliance/ambientai-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Ambient.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Physical Security
- Computer Vision
- Artificial Intelligence
- Video Analytics
- Access Control
- Threat Detection
- Enterprise Security
- AI Agents
---
