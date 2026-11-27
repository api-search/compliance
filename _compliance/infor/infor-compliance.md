---
api_specs:
- filename: infor-contents-api-openapi.yml
  format: yaml
  label: Infor Contents API
  slug: infor-contents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infor/openapi/infor-contents-api-openapi.yml
- filename: infor-icua-api-openapi.yml
  format: yaml
  label: Infor ICUA API
  slug: infor-icua-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infor/openapi/infor-icua-api-openapi.yml
- filename: infor-languages-api-openapi.yml
  format: yaml
  label: Infor Languages API
  slug: infor-languages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infor/openapi/infor-languages-api-openapi.yml
- filename: infor-products-api-openapi.yml
  format: yaml
  label: Infor Products API
  slug: infor-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infor/openapi/infor-products-api-openapi.yml
- filename: infor-recenttopics-api-openapi.yml
  format: yaml
  label: Infor Recent Topics API
  slug: infor-recenttopics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infor/openapi/infor-recenttopics-api-openapi.yml
- filename: infor-s3-docs-api-openapi.yml
  format: yaml
  label: Infor S3 Docs API
  slug: infor-s3-docs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infor/openapi/infor-s3-docs-api-openapi.yml
- filename: infor-search-api-openapi.yml
  format: yaml
  label: Infor Search API
  slug: infor-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infor/openapi/infor-search-api-openapi.yml
- filename: infor-security-api-openapi.yml
  format: yaml
  label: Infor Security API
  slug: infor-security-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infor/openapi/infor-security-api-openapi.yml
- filename: infor-solutions-api-openapi.yml
  format: yaml
  label: Infor Solutions API
  slug: infor-solutions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infor/openapi/infor-solutions-api-openapi.yml
- filename: infor-userfavorites-api-openapi.yml
  format: yaml
  label: Infor User Favorites API
  slug: infor-userfavorites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infor/openapi/infor-userfavorites-api-openapi.yml
- filename: infor-web-api-openapi.yml
  format: yaml
  label: Infor Web API
  slug: infor-web-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infor/openapi/infor-web-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: SOC1
    issuer: null
    period: null
    report_access: on_request
    scope: Infor SaaS Solutions
    text: Customers can request the latest audit reports through Infor Concierge.
    type: SOC 1 audit report
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Infor SaaS Solutions
    text: Customers can request the latest audit reports through Infor Concierge.
    type: SOC 2 audit report
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: on_request
    scope: Infor Government Solutions (IGS)
    text: 'Federal Agencies may request Infor’s authorization package through the FedRAMP Marketplace at:'
    type: FedRAMP Moderate Authorization
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Infor OS (MT/ST), Infor BIRST (MT), Infor Mongoose (MT)
    text: 'HIPAA Infor attested products: Infor OS (MT/ST), Infor BIRST (MT), Infor Mongoose (MT)'
    type: HIPAA attested products
  - framework: TISAX
    issuer: null
    period: null
    report_access: unstated
    scope: Cloud Suite Automotive
    text: TISAX for Cloud Suite Automotive
    type: TISAX certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Latest solutions certified for ISO 27001
    text: Please click on the link to see the latest solutions certified for ISO 27001
    type: ISO 27001 certification
  trust_center:
    url: https://trust.infor.com/
frameworks:
- FedRAMP
- HIPAA
- ISO27001
- SOC1
- SOC2
- TISAX
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Infor
provenance_date: '2026-11-09'
provider_name: Infor
provider_slug: infor
slug: infor-compliance
source_date: '2026-11-09'
source_filename: infor-compliance.yml
source_heading: Compliance
source_page: https://trust.infor.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Infor\naid: infor\nurl: https://trust.infor.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.infor.com/\nattestations:\n- framework: SOC1\n  type: SOC 1 audit report\n  scope: Infor SaaS Solutions\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Customers can request the latest audit reports through Infor Concierge.\n- framework: SOC2\n  type: SOC 2 audit report\n  scope: Infor SaaS Solutions\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Customers can request the latest audit reports through Infor Concierge.\n- framework: FedRAMP\n  type: FedRAMP\
  \ Moderate Authorization\n  scope: Infor Government Solutions (IGS)\n  period: null\n  issuer: null\n  report_access: on_request\n  text: 'Federal Agencies may request Infor’s authorization package through the FedRAMP Marketplace at:'\n- framework: HIPAA\n  type: HIPAA attested products\n  scope: Infor OS (MT/ST), Infor BIRST (MT), Infor Mongoose (MT)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'HIPAA Infor attested products: Infor OS (MT/ST), Infor BIRST (MT), Infor Mongoose (MT)'\n- framework: TISAX\n  type: TISAX certification\n  scope: Cloud Suite Automotive\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TISAX for Cloud Suite Automotive\n- framework: ISO27001\n  type: ISO 27001 certification\n  scope: Latest solutions certified for ISO 27001\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Please click on the link to see the latest solutions certified for ISO 27001\n"
source_yaml_url: https://artifacts.apis.io/infor/compliance/infor-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Infor's own page on 2026-11-09.
synthetic: false
tags:
- ERP
- Manufacturing
- Supply Chain
- Cloud
- Integration
---
