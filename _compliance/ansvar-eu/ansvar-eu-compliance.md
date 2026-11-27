---
api_specs:
- filename: ansvar-eu-openapi-generated.yml
  format: yaml
  label: ansvar-eu API
  slug: ansvar-eu-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ansvar-eu/openapi/_ae-authored/ansvar-eu-openapi-generated.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: BSI
    period: November 2026
    report_access: nda
    scope: null
    text: Passed BSI's ISO/IEC 27001:2022 certification audit, November 2026. Certificate to follow.
    type: Certification audit passed; certificate to follow
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: Ansvar Gateway CAIQ v4.0.3
    text: 'Listed in the CSA STAR Registry: Ansvar Gateway’s CAIQ v4.0.3 self-assessment.'
    type: Self-assessment listed in CSA STAR Registry (Level 1)
  - framework: ISO27001
    issuer: BSI
    period: November 2026
    report_access: nda
    scope: Ansvar platform ISMS
    source: https://ansvar.eu/trust#disclosure
    text: Passed BSI's ISO/IEC 27001:2022 certification audit, November 2026. Certificate to follow.
    type: certification audit passed, certificate to follow
  - framework: CSA-STAR
    issuer: CSA STAR Registry (self-published)
    period: null
    report_access: unstated
    scope: Ansvar Gateway
    source: https://ansvar.eu/trust#disclosure
    text: A published self-assessment, not a third-party certification.
    type: self-assessment (CAIQ v4.0.3), CSA STAR Level 1 registry listing
  trust_center:
    url: https://ansvar.eu/trust
frameworks:
- CSA-STAR
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: ansvar-eu
provenance_date: '2026-11-09'
provider_name: ansvar-eu
provider_slug: ansvar-eu
slug: ansvar-eu-compliance
source_date: '2026-11-09'
source_filename: ansvar-eu-compliance.yml
source_heading: Compliance
source_page: https://ansvar.eu/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: ansvar-eu\naid: ansvar-eu\nurl: https://ansvar.eu/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://ansvar.eu/trust\n  - https://ansvar.eu/trust#disclosure\ntrust_center:\n  url: https://ansvar.eu/trust\nattestations:\n- framework: ISO27001\n  type: Certification audit passed; certificate to follow\n  scope: null\n  period: November 2026\n  issuer: BSI\n  report_access: nda\n  text: Passed BSI's ISO/IEC 27001:2022 certification audit, November 2026. Certificate to follow.\n- framework: CSA-STAR\n  type: Self-assessment listed in CSA STAR Registry (Level 1)\n  scope: Ansvar Gateway CAIQ v4.0.3\n  period:\
  \ null\n  issuer: null\n  report_access: unstated\n  text: 'Listed in the CSA STAR Registry: Ansvar Gateway’s CAIQ v4.0.3 self-assessment.'\n- framework: ISO27001\n  type: certification audit passed, certificate to follow\n  scope: Ansvar platform ISMS\n  period: November 2026\n  issuer: BSI\n  report_access: nda\n  text: Passed BSI's ISO/IEC 27001:2022 certification audit, November 2026. Certificate to follow.\n  source: https://ansvar.eu/trust#disclosure\n- framework: CSA-STAR\n  type: self-assessment (CAIQ v4.0.3), CSA STAR Level 1 registry listing\n  scope: Ansvar Gateway\n  period: null\n  issuer: CSA STAR Registry (self-published)\n  report_access: unstated\n  text: A published self-assessment, not a third-party certification.\n  source: https://ansvar.eu/trust#disclosure\n"
source_yaml_url: https://artifacts.apis.io/ansvar-eu/compliance/ansvar-eu-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from ansvar-eu's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Compliance
- Legal
- Security
- Data
---
