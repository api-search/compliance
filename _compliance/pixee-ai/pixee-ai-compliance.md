---
api_specs:
- filename: pixee-ai-findings-api-openapi.yml
  format: yaml
  label: Pixee Findings API
  slug: pixee-ai-findings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pixee-ai/openapi/pixee-ai-findings-api-openapi.yml
- filename: pixee-ai-fixes-api-openapi.yml
  format: yaml
  label: Pixee Fixes API
  slug: pixee-ai-fixes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pixee-ai/openapi/pixee-ai-fixes-api-openapi.yml
- filename: pixee-ai-repositories-api-openapi.yml
  format: yaml
  label: Pixee Repositories API
  slug: pixee-ai-repositories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pixee-ai/openapi/pixee-ai-repositories-api-openapi.yml
- filename: pixee-ai-scans-api-openapi.yml
  format: yaml
  label: Pixee Scans API
  slug: pixee-ai-scans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pixee-ai/openapi/pixee-ai-scans-api-openapi.yml
- filename: pixee-ai-webhooks-api-openapi.yml
  format: yaml
  label: Pixee Webhooks API
  slug: pixee-ai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pixee-ai/openapi/pixee-ai-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Compliant
    type: null
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CIS Controls Compliant
    type: null
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001 Compliant
    type: null
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CSA Star Compliant
    type: null
  trust_center:
    url: https://trust.pixee.ai/
frameworks:
- CSA-STAR
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Pixee
provenance_date: '2026-11-10'
provider_name: Pixee
provider_slug: pixee-ai
slug: pixee-ai-compliance
source_date: '2026-11-10'
source_filename: pixee-ai-compliance.yml
source_heading: Compliance
source_page: https://trust.pixee.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Pixee\naid: pixee-ai\nurl: https://trust.pixee.ai/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/pixee-ai-trust-center.yml\ntrust_center:\n  url: https://trust.pixee.ai/\nattestations:\n- framework: SOC2\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Compliant\n- framework: other\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CIS Controls Compliant\n- framework: ISO27001\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 Compliant\n- framework:\
  \ CSA-STAR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CSA Star Compliant\n"
source_yaml_url: https://artifacts.apis.io/pixee-ai/compliance/pixee-ai-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Pixee's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Application Security
- AppSec
- Vulnerability-Remediation
- Static Analysis
- SARIF
- Code Security
- Artificial Intelligence
- Developer Tools
---
