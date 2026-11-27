---
api_specs:
- filename: developerportal
  format: yaml
  label: Hexagon Nexus API
  slug: nexus-api
  spec_type: OpenAPI
  url: https://nexus.hexagon.com/developerportal
- filename: hexagon-eam-ion-api-openapi.yml
  format: yaml
  label: HxGN EAM REST API
  slug: hxgn-eam-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hexagon/openapi/hexagon-eam-ion-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Hexagon GeoCloud in scope of HxDR platform ISO27001:2022 certificate
    text: Hexagon GeoCloud is in scope of the ISO27001:2022 certificate of the HxDR platform .
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Hexagon GeoCloud
    text: Hexagon GeoCloud has achieved SOC 2 Type II certification
    type: SOC 2 Type II certification
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: CSA STAR Level 1
    text: CSA STAR Level 1
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Hexagon Data Protection Program
    text: The Hexagon Data Protection Program is based on and compliant with GDPR.
    type: compliance statement
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: Hexagon GeoCloud customer privacy
    text: Hexagon GeoCloud meets or exceeds the requirements of CCPA for customer privacy.
    type: compliance statement
  trust_center:
    url: https://geocloud.hexagon.com/security-compliance/
frameworks:
- CCPA
- CSA-STAR
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Hexagon
provenance_date: '2026-11-09'
provider_name: Hexagon
provider_slug: hexagon
slug: hexagon-compliance
source_date: '2026-11-09'
source_filename: hexagon-compliance.yml
source_heading: Compliance
source_page: https://geocloud.hexagon.com/security-compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Hexagon\naid: hexagon\nurl: https://geocloud.hexagon.com/security-compliance/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://geocloud.hexagon.com/security-compliance/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Hexagon GeoCloud in scope of HxDR platform ISO27001:2022 certificate\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Hexagon GeoCloud is in scope of the ISO27001:2022 certificate of the HxDR platform .\n- framework: SOC2\n  type: SOC 2 Type II certification\n  scope: Hexagon GeoCloud\n  period: null\n  issuer: null\n  report_access: unstated\n  text:\
  \ Hexagon GeoCloud has achieved SOC 2 Type II certification\n- framework: CSA-STAR\n  type: certification\n  scope: CSA STAR Level 1\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CSA STAR Level 1\n- framework: GDPR\n  type: compliance statement\n  scope: Hexagon Data Protection Program\n  period: null\n  issuer: null\n  report_access: unstated\n  text: The Hexagon Data Protection Program is based on and compliant with GDPR.\n- framework: CCPA\n  type: compliance statement\n  scope: Hexagon GeoCloud customer privacy\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Hexagon GeoCloud meets or exceeds the requirements of CCPA for customer privacy.\n"
source_yaml_url: https://artifacts.apis.io/hexagon/compliance/hexagon-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Hexagon's own page on 2026-11-09.
synthetic: false
tags:
- Manufacturing
- Metrology
- Quality Inspection
- Digital Factory
- Production Monitoring
- Industrial IoT
- Smart Manufacturing
- Geospatial
---
