---
api_specs:
- filename: splunk-data-inputs-api-openapi.yml
  format: yaml
  label: Splunk Data Inputs API
  slug: splunk-data-inputs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/splunk/openapi/splunk-data-inputs-api-openapi.yml
- filename: splunk-index-api-openapi.yml
  format: yaml
  label: Splunk Index API
  slug: splunk-index-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/splunk/openapi/splunk-index-api-openapi.yml
- filename: splunk-search-api-openapi.yml
  format: yaml
  label: Splunk Search API
  slug: splunk-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/splunk/openapi/splunk-search-api-openapi.yml
claim_count: 9
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II
    type: SOC 2 Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: null
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: null
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI
    type: null
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: FedRAMP Moderate
    type: FedRAMP Moderate
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001
    type: null
  - framework: ISO27017
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27017
    type: null
  - framework: ISO27018
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27018
    type: null
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CSA STAR 2
    type: CSA STAR 2
  trust_center:
    url: https://customertrust.splunk.com/
frameworks:
- CSA-STAR
- FedRAMP
- GDPR
- HIPAA
- ISO27001
- ISO27017
- ISO27018
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Splunk
provenance_date: '2026-11-10'
provider_name: Splunk
provider_slug: splunk
slug: splunk-compliance
source_date: '2026-11-10'
source_filename: splunk-compliance.yml
source_heading: Compliance
source_page: https://customertrust.splunk.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Splunk\naid: splunk\nurl: https://customertrust.splunk.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://customertrust.splunk.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n- framework: PCI-DSS\n  type: null\n  scope: null\n  period: null\n  issuer:\
  \ null\n  report_access: unstated\n  text: PCI\n- framework: FedRAMP\n  type: FedRAMP Moderate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: FedRAMP Moderate\n- framework: ISO27001\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001\n- framework: ISO27017\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27017\n- framework: ISO27018\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27018\n- framework: CSA-STAR\n  type: CSA STAR 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CSA STAR 2\n"
source_yaml_url: https://artifacts.apis.io/splunk/compliance/splunk-compliance.yml
stated_fields:
- attestations
summary_line: 9 quoted statements, read from Splunk's own page on 2026-11-10.
synthetic: false
tags:
- Analytics
- Data Analysis
- Logging
- Machine Data
- Monitoring
- Observability
- Platform
- Security
- SIEM
---
