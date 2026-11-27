---
api_specs:
- filename: hookdeploy-openapi-generated.yml
  format: yaml
  label: HookDeploy API
  slug: hookdeploy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hookdeploy/openapi/_ae-authored/hookdeploy-openapi-generated.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: HookDeploy platform
    text: HookDeploy is not currently SOC 2 certified. We plan to begin a formal SOC 2 audit engagement by the end of 2026.
    type: readiness / planned independent examination
  trust_center:
    url: https://hookdeploy.dev/security/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: HookDeploy
provenance_date: '2026-11-09'
provider_name: HookDeploy
provider_slug: hookdeploy
slug: hookdeploy-compliance
source_date: '2026-11-09'
source_filename: hookdeploy-compliance.yml
source_heading: Compliance
source_page: https://hookdeploy.dev/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: HookDeploy\naid: hookdeploy\nurl: https://hookdeploy.dev/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://hookdeploy.dev/security/\nattestations:\n- framework: SOC2\n  type: readiness / planned independent examination\n  scope: HookDeploy platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HookDeploy is not currently SOC 2 certified. We plan to begin a formal SOC 2 audit engagement by the end\n    of 2026.\n"
source_yaml_url: https://artifacts.apis.io/hookdeploy/compliance/hookdeploy-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from HookDeploy's own page on 2026-11-09.
synthetic: false
tags:
- Webhook
- PrivateInfrastructure
- Security
- Integration
- Developer Tools
---
