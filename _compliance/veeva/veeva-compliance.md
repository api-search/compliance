---
api_specs:
- filename: veeva-authentication-api-openapi.yml
  format: yaml
  label: veeva Authentication API
  slug: veeva-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veeva/openapi/veeva-authentication-api-openapi.yml
- filename: veeva-documents-api-openapi.yml
  format: yaml
  label: veeva Documents API
  slug: veeva-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veeva/openapi/veeva-documents-api-openapi.yml
- filename: veeva-objects-api-openapi.yml
  format: yaml
  label: veeva Objects API
  slug: veeva-objects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veeva/openapi/veeva-objects-api-openapi.yml
- filename: veeva-query-api-openapi.yml
  format: yaml
  label: veeva Query API
  slug: veeva-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veeva/openapi/veeva-query-api-openapi.yml
- filename: veeva-users-api-openapi.yml
  format: yaml
  label: veeva Users API
  slug: veeva-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veeva/openapi/veeva-users-api-openapi.yml
- filename: veeva-workflows-api-openapi.yml
  format: yaml
  label: veeva Workflows API
  slug: veeva-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veeva/openapi/veeva-workflows-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: accredited third-party certification body
    period: null
    report_access: unstated
    scope: Veeva products and supporting infrastructure per certificate, also ISO 27017 and ISO 27018 controls
    text: At least once a year we are audited by an accredited third-party certification body for compliance with ISO (International Organization for Standardization) 27001, ISO 27017, and ISO 27018 controls.
    type: certification
  - framework: SOC2
    issuer: third-party auditor
    period: null
    report_access: unstated
    scope: Security and Availability Trust Service Principles for various Veeva products and supporting infrastructure
    text: We publish our Service Organization Controls 2 (SOC 2) Type II report under the Security and Availability Trust Service Principles (TSPs).
    type: SOC 2 Type II report
  - framework: ISO9001
    issuer: null
    period: null
    report_access: unstated
    scope: Quality Management System for those Veeva products described in certificate
    text: We maintain certification to ISO 9001 for its Quality Management System.
    type: certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Health personal data hosting under French law, Veeva products in certificate, applicable to health data produced in France
    text: We maintain a Health Data Hosting (HDS) certificate as required for all entities hosting personal health data under French law
    type: Health Data Hosting (HDS) certificate
  - framework: other
    issuer: sanctioned third-party GxP audit specialists
    period: null
    report_access: on_request
    scope: Veeva QMS and MSA controls
    text: 'Independent GxP audit reports can be purchased from: Rx-360'
    type: independent GxP attestation reports
  trust_center:
    url: https://www.veeva.com/trust/
frameworks:
- ISO27001
- ISO9001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Veeva
provenance_date: '2026-11-10'
provider_name: Veeva
provider_slug: veeva
slug: veeva-compliance
source_date: '2026-11-10'
source_filename: veeva-compliance.yml
source_heading: Compliance
source_page: https://www.veeva.com/trust/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Veeva\naid: veeva\nurl: https://www.veeva.com/trust/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.veeva.com/trust/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Veeva products and supporting infrastructure per certificate, also ISO 27017 and ISO 27018 controls\n  period: null\n  issuer: accredited third-party certification body\n  report_access: unstated\n  text: At least once a year we are audited by an accredited third-party certification body for compliance with\n    ISO (International Organization for Standardization) 27001, ISO 27017, and ISO 27018 controls.\n- framework:\
  \ SOC2\n  type: SOC 2 Type II report\n  scope: Security and Availability Trust Service Principles for various Veeva products and supporting infrastructure\n  period: null\n  issuer: third-party auditor\n  report_access: unstated\n  text: We publish our Service Organization Controls 2 (SOC 2) Type II report under the Security and Availability\n    Trust Service Principles (TSPs).\n- framework: ISO9001\n  type: certification\n  scope: Quality Management System for those Veeva products described in certificate\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We maintain certification to ISO 9001 for its Quality Management System.\n- framework: other\n  type: Health Data Hosting (HDS) certificate\n  scope: Health personal data hosting under French law, Veeva products in certificate, applicable to health data\n    produced in France\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We maintain a Health Data Hosting (HDS) certificate as required for all entities\
  \ hosting personal health\n    data under French law\n- framework: other\n  type: independent GxP attestation reports\n  scope: Veeva QMS and MSA controls\n  period: null\n  issuer: sanctioned third-party GxP audit specialists\n  report_access: on_request\n  text: 'Independent GxP audit reports can be purchased from: Rx-360'\n"
source_yaml_url: https://artifacts.apis.io/veeva/compliance/veeva-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Veeva's own page on 2026-11-10.
synthetic: false
tags:
- Life Sciences
- Pharmaceuticals
- Clinical Trials
- Regulatory
- Quality Management
- Document Management
- Content Management
- Healthcare
- Software-as-a-Service
- Enterprise
- MCP
- Agents
- Clinical Research
---
