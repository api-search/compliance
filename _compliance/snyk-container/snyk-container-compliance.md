---
api_specs:
- filename: snyk-container-container-projects-api-openapi.yml
  format: yaml
  label: Snyk Container Projects API
  slug: snyk-container-container-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snyk-container/openapi/snyk-container-container-projects-api-openapi.yml
- filename: snyk-container-issues-api-openapi.yml
  format: yaml
  label: Snyk Container Issues API
  slug: snyk-container-issues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snyk-container/openapi/snyk-container-issues-api-openapi.yml
- filename: snyk-container-targets-api-openapi.yml
  format: yaml
  label: Snyk Container Targets API
  slug: snyk-container-targets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snyk-container/openapi/snyk-container-targets-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022
    type: certification
  - framework: ISO27017
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27017:2015
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II
    type: report
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI DSS - SAQ A
    type: self-assessment questionnaire
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: FedRAMP Rev. 5
    type: authorization
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR compliance
    type: compliance claim
  trust_center:
    url: https://trust.snyk.io/
frameworks:
- FedRAMP
- GDPR
- ISO27001
- ISO27017
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Snyk Container
provenance_date: '2026-11-10'
provider_name: Snyk Container
provider_slug: snyk-container
slug: snyk-container-compliance
source_date: '2026-11-10'
source_filename: snyk-container-compliance.yml
source_heading: Compliance
source_page: https://trust.snyk.io/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Snyk Container\naid: snyk-container\nurl: https://trust.snyk.io/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/snyk-container-trust-center.yml\ntrust_center:\n  url: https://trust.snyk.io/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022\n- framework: ISO27017\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27017:2015\n- framework: SOC2\n  type: report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: SOC 2 Type II\n- framework: PCI-DSS\n  type: self-assessment questionnaire\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS - SAQ A\n- framework: FedRAMP\n  type: authorization\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: FedRAMP Rev. 5\n- framework: GDPR\n  type: compliance claim\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR compliance\n"
source_yaml_url: https://artifacts.apis.io/snyk-container/compliance/snyk-container-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Snyk Container's own page on 2026-11-10.
synthetic: false
tags:
- Container Images
- Containers
- Kubernetes
- Security
- Vulnerability Management
- DevSecOps
- Open Source
---
