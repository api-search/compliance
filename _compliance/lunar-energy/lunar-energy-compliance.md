---
api_specs:
- filename: lunar-energy-devices-api-openapi.yml
  format: yaml
  label: Lunar Energy Devices API
  slug: lunar-energy-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lunar-energy/openapi/lunar-energy-devices-api-openapi.yml
- filename: lunar-energy-diff-requests-api-openapi.yml
  format: yaml
  label: Lunar Energy Diff Requests API
  slug: lunar-energy-diff-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lunar-energy/openapi/lunar-energy-diff-requests-api-openapi.yml
- filename: lunar-energy-dynamic-tariffs-api-openapi.yml
  format: yaml
  label: Lunar Energy Dynamic Tariffs API
  slug: lunar-energy-dynamic-tariffs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lunar-energy/openapi/lunar-energy-dynamic-tariffs-api-openapi.yml
- filename: lunar-energy-flex-dispatches-api-openapi.yml
  format: yaml
  label: Lunar Energy Flex Dispatches API
  slug: lunar-energy-flex-dispatches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lunar-energy/openapi/lunar-energy-flex-dispatches-api-openapi.yml
- filename: lunar-energy-flex-events-api-openapi.yml
  format: yaml
  label: Lunar Energy Flex Events API
  slug: lunar-energy-flex-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lunar-energy/openapi/lunar-energy-flex-events-api-openapi.yml
- filename: lunar-energy-flex-groups-api-openapi.yml
  format: yaml
  label: Lunar Energy Flex Groups API
  slug: lunar-energy-flex-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lunar-energy/openapi/lunar-energy-flex-groups-api-openapi.yml
- filename: lunar-energy-operation-mode-api-openapi.yml
  format: yaml
  label: Lunar Energy Operation Mode API
  slug: lunar-energy-operation-mode-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lunar-energy/openapi/lunar-energy-operation-mode-api-openapi.yml
- filename: lunar-energy-periodical-tariffs-api-openapi.yml
  format: yaml
  label: Lunar Energy Periodical Tariffs API
  slug: lunar-energy-periodical-tariffs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lunar-energy/openapi/lunar-energy-periodical-tariffs-api-openapi.yml
- filename: lunar-energy-plans-api-openapi.yml
  format: yaml
  label: Lunar Energy Plans API
  slug: lunar-energy-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lunar-energy/openapi/lunar-energy-plans-api-openapi.yml
- filename: lunar-energy-prognoses-api-openapi.yml
  format: yaml
  label: Lunar Energy Prognoses API
  slug: lunar-energy-prognoses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lunar-energy/openapi/lunar-energy-prognoses-api-openapi.yml
- filename: lunar-energy-sites-api-openapi.yml
  format: yaml
  label: Lunar Energy Sites API
  slug: lunar-energy-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lunar-energy/openapi/lunar-energy-sites-api-openapi.yml
- filename: lunar-energy-telemetry-api-openapi.yml
  format: yaml
  label: Lunar Energy Telemetry API
  slug: lunar-energy-telemetry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lunar-energy/openapi/lunar-energy-telemetry-api-openapi.yml
- filename: lunar-energy-visits-api-openapi.yml
  format: yaml
  label: Lunar Energy Visits API
  slug: lunar-energy-visits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lunar-energy/openapi/lunar-energy-visits-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022 - Certificate
    type: certificate
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: SOC 2 Type I - Report [NDA Required]
    type: Type I attestation and report
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: SOC 2 Type II - Report [NDA Required]
    type: Type II attestation and report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: compliance listing
  - framework: NIST-CSF
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: NIST CSF 2.0
    type: compliance listing
  - framework: NIST-800-53
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: NIST 800-53
    type: compliance listing
  trust_center:
    url: https://trust.lunarenergy.com/
frameworks:
- GDPR
- ISO27001
- NIST-800-53
- NIST-CSF
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Lunar Energy
provenance_date: '2026-11-10'
provider_name: Lunar Energy
provider_slug: lunar-energy
slug: lunar-energy-compliance
source_date: '2026-11-10'
source_filename: lunar-energy-compliance.yml
source_heading: Compliance
source_page: https://trust.lunarenergy.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Lunar Energy\naid: lunar-energy\nurl: https://trust.lunarenergy.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/lunar-energy-trust-center.yml\ntrust_center:\n  url: https://trust.lunarenergy.com/\nattestations:\n- framework: ISO27001\n  type: certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022 - Certificate\n- framework: SOC2\n  type: Type I attestation and report\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: SOC 2 Type I - Report [NDA Required]\n- framework: SOC2\n  type: Type II attestation and report\n\
  \  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: SOC 2 Type II - Report [NDA Required]\n- framework: GDPR\n  type: compliance listing\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: NIST-CSF\n  type: compliance listing\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: NIST CSF 2.0\n- framework: NIST-800-53\n  type: compliance listing\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: NIST 800-53\n"
source_yaml_url: https://artifacts.apis.io/lunar-energy/compliance/lunar-energy-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Lunar Energy's own page on 2026-11-10.
synthetic: false
tags:
- Energy
- Home Battery
- Solar
- Virtual Power Plant
- DERMS
- Distributed Energy Resources
- Grid Services
- Demand Response
- Storage
- Inverters
- Smart Home
- Energy Management
- Tariffs
- Telemetry
- VPP
- Flex Events
- Energy Storage
---
