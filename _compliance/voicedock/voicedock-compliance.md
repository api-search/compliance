---
api_specs:
- filename: voicedock-api-openapi-generated.yml
  format: yaml
  label: VoiceDock api API
  slug: api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voicedock/openapi/_ae-authored/voicedock-api-openapi-generated.yml
- filename: voicedock-reference-openapi-generated.yml
  format: yaml
  label: VoiceDock reference API
  slug: reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voicedock/openapi/_ae-authored/voicedock-reference-openapi-generated.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: infrastructure providers
    period: null
    report_access: unstated
    scope: EU cloud regions and hosting (held by infrastructure providers, not Flireo)
    text: Our platform runs on ISO 27001 and SOC 2 Type II certified EU cloud regions and hosting. These certifications are held by our infrastructure providers, not by Flireo.
    type: certification
  - framework: SOC2
    issuer: infrastructure providers
    period: null
    report_access: unstated
    scope: EU cloud regions and hosting (held by infrastructure providers, not Flireo)
    text: Our platform runs on ISO 27001 and SOC 2 Type II certified EU cloud regions and hosting. These certifications are held by our infrastructure providers, not by Flireo.
    type: certification (Type II)
  - framework: GDPR
    issuer: Flireo B.V.
    period: null
    report_access: nda
    scope: VoiceDock services
    text: A ready-to-sign, GDPR Article 28-compliant Standard DPA is included at no additional cost, whichever configuration you run.
    type: Standard DPA, GDPR Article 28-compliant
  trust_center:
    url: https://trust.voicedock.ai/
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: VoiceDock
provenance_date: '2026-11-10'
provider_name: VoiceDock
provider_slug: voicedock
slug: voicedock-compliance
source_date: '2026-11-10'
source_filename: voicedock-compliance.yml
source_heading: Compliance
source_page: https://trust.voicedock.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: VoiceDock\naid: voicedock\nurl: https://trust.voicedock.ai/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.voicedock.ai/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: EU cloud regions and hosting (held by infrastructure providers, not Flireo)\n  period: null\n  issuer: infrastructure providers\n  report_access: unstated\n  text: Our platform runs on ISO 27001 and SOC 2 Type II certified EU cloud regions and hosting. These certifications\n    are held by our infrastructure providers, not by Flireo.\n- framework: SOC2\n  type: certification (Type II)\n  scope: EU cloud regions\
  \ and hosting (held by infrastructure providers, not Flireo)\n  period: null\n  issuer: infrastructure providers\n  report_access: unstated\n  text: Our platform runs on ISO 27001 and SOC 2 Type II certified EU cloud regions and hosting. These certifications\n    are held by our infrastructure providers, not by Flireo.\n- framework: GDPR\n  type: Standard DPA, GDPR Article 28-compliant\n  scope: VoiceDock services\n  period: null\n  issuer: Flireo B.V.\n  report_access: nda\n  text: A ready-to-sign, GDPR Article 28-compliant Standard DPA is included at no additional cost, whichever configuration\n    you run.\n"
source_yaml_url: https://artifacts.apis.io/voicedock/compliance/voicedock-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from VoiceDock's own page on 2026-11-10.
synthetic: false
tags:
- Voice AI
- Telephony
- Communications
- Platform
- EU-Sovereign
- On-Premises
---
