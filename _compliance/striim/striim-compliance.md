---
api_specs:
- filename: striim-application-api-openapi.yml
  format: yaml
  label: Striim Application API
  slug: striim-application-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/striim/openapi/striim-application-api-openapi.yml
- filename: striim-applicationmetadata-api-openapi.yml
  format: yaml
  label: Striim Application Metadata API
  slug: striim-applicationmetadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/striim/openapi/striim-applicationmetadata-api-openapi.yml
- filename: striim-checkpoint-api-openapi.yml
  format: yaml
  label: Striim Checkpoint API
  slug: striim-checkpoint-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/striim/openapi/striim-checkpoint-api-openapi.yml
- filename: striim-monitoring-api-openapi.yml
  format: yaml
  label: Striim Monitoring API
  slug: striim-monitoring-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/striim/openapi/striim-monitoring-api-openapi.yml
- filename: striim-template-api-openapi.yml
  format: yaml
  label: Striim Template API
  slug: striim-template-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/striim/openapi/striim-template-api-openapi.yml
- filename: striim-tqlfiles-api-openapi.yml
  format: yaml
  label: Striim Tqlfiles API
  slug: striim-tqlfiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/striim/openapi/striim-tqlfiles-api-openapi.yml
- filename: striim-tungsten-api-openapi.yml
  format: yaml
  label: Striim Tungsten API
  slug: striim-tungsten-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/striim/openapi/striim-tungsten-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: We are SOC 2 Type 2, PCI DSS 4.0, HIPAA, and GDPR compliant.
    type: SOC 2 Type 2
  - framework: PCI-DSS
    issuer: null
    period: '2026'
    report_access: on_request
    scope: null
    text: PCI-DSS 4.0 ROC/AOC 2026
    type: PCI DSS 4.0 ROC/AOC
  - framework: HIPAA
    issuer: null
    period: '2026'
    report_access: on_request
    scope: null
    text: HIPAA Security Compliance 2026
    type: HIPAA Security Compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We are SOC 2 Type 2, PCI DSS 4.0, HIPAA, and GDPR compliant.
    type: GDPR compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA CCPA COMPLIANT CCPA
    type: CCPA compliance
  - framework: CyberEssentials
    issuer: null
    period: '2026'
    report_access: on_request
    scope: null
    text: UK Cyber Essentials 2026
    type: UK Cyber Essentials
  trust_center:
    url: https://trust.striim.com/
frameworks:
- CCPA
- CyberEssentials
- GDPR
- HIPAA
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Striim
provenance_date: '2026-11-10'
provider_name: Striim
provider_slug: striim
slug: striim-compliance
source_date: '2026-11-10'
source_filename: striim-compliance.yml
source_heading: Compliance
source_page: https://trust.striim.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Striim\naid: striim\nurl: https://trust.striim.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/striim-trust-center.yml\ntrust_center:\n  url: https://trust.striim.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: We are SOC 2 Type 2, PCI DSS 4.0, HIPAA, and GDPR compliant.\n- framework: PCI-DSS\n  type: PCI DSS 4.0 ROC/AOC\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: on_request\n  text: PCI-DSS 4.0 ROC/AOC 2026\n- framework: HIPAA\n  type: HIPAA Security Compliance\n  scope: null\n\
  \  period: '2026'\n  issuer: null\n  report_access: on_request\n  text: HIPAA Security Compliance 2026\n- framework: GDPR\n  type: GDPR compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are SOC 2 Type 2, PCI DSS 4.0, HIPAA, and GDPR compliant.\n- framework: CCPA\n  type: CCPA compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA CCPA COMPLIANT CCPA\n- framework: CyberEssentials\n  type: UK Cyber Essentials\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: on_request\n  text: UK Cyber Essentials 2026\n"
source_yaml_url: https://artifacts.apis.io/striim/compliance/striim-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Striim's own page on 2026-11-10.
synthetic: false
tags:
- Data
- Streaming
- Change Data Capture
- Real-Time
- Data Integration
- Streaming Analytics
---
