---
api_specs:
- filename: signwell-api-application-api-openapi.yml
  format: yaml
  label: SignWell API Application API
  slug: signwell-api-application-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signwell/openapi/signwell-api-application-api-openapi.yml
- filename: signwell-bulk-send-api-openapi.yml
  format: yaml
  label: SignWell Bulk Send API
  slug: signwell-bulk-send-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signwell/openapi/signwell-bulk-send-api-openapi.yml
- filename: signwell-document-api-openapi.yml
  format: yaml
  label: SignWell Document API
  slug: signwell-document-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signwell/openapi/signwell-document-api-openapi.yml
- filename: signwell-me-api-openapi.yml
  format: yaml
  label: SignWell Me API
  slug: signwell-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signwell/openapi/signwell-me-api-openapi.yml
- filename: signwell-regional-api-openapi.yml
  format: yaml
  label: SignWell Regional API
  slug: signwell-regional-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signwell/openapi/signwell-regional-api-openapi.yml
- filename: signwell-template-api-openapi.yml
  format: yaml
  label: SignWell Template API
  slug: signwell-template-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signwell/openapi/signwell-template-api-openapi.yml
- filename: signwell-webhooks-api-openapi.yml
  format: yaml
  label: SignWell Webhooks API
  slug: signwell-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signwell/openapi/signwell-webhooks-api-openapi.yml
claim_count: 7
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent third-party CPA firm
    period: null
    report_access: on_request
    scope: Security, Availability, and Confidentiality
    text: Please contact @signwell.com to request SignWell's most recent SOC 2 report.
    type: SOC 2 Type II report
  - framework: HIPAA
    issuer: third party audit
    period: null
    report_access: on_request
    scope: SignWell platform; BAA for customers on paid plans
    text: SignWell signs a Business Associate Agreement (BAA) with customers on paid plans at no extra cost
    type: HIPAA compliance with Business Associate Agreement
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data of users
    text: SignWell has implemented these requirements and is compliant with all the principles of the GDPR.
    type: GDPR compliance statement
  - framework: ISO27001
    issuer: independent auditors
    period: null
    report_access: unstated
    scope: AWS data centers and services used by SignWell
    text: Both AWS data centers and services are certified by independent auditors according to ISO 27001
    type: AWS data center certification
  - framework: ISO27017
    issuer: independent auditors
    period: null
    report_access: unstated
    scope: AWS data centers and services used by SignWell
    text: ISO 27017 (information security management systems in the cloud)
    type: AWS data center certification
  - framework: ISO27018
    issuer: independent auditors
    period: null
    report_access: unstated
    scope: AWS data centers and services used by SignWell
    text: ISO 27018 (information privacy in the cloud)
    type: AWS data center certification
  - framework: other
    issuer: SeguriData, accredited Prestador de Servicios de Certificación
    period: null
    report_access: unstated
    scope: completed documents for businesses in Mexico
    text: SignWell supports NOM-151 compliance through our partnership with SeguriData
    type: NOM-151 preservation certificate support via SeguriData PSC partnership
  trust_center:
    url: https://www.signwell.com/security/
frameworks:
- GDPR
- HIPAA
- ISO27001
- ISO27017
- ISO27018
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: SignWell
provenance_date: '2026-11-10'
provider_name: SignWell
provider_slug: signwell
slug: signwell-compliance
source_date: '2026-11-10'
source_filename: signwell-compliance.yml
source_heading: Compliance
source_page: https://www.signwell.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: SignWell\naid: signwell\nurl: https://www.signwell.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/signwell-trust-center.yml\ntrust_center:\n  url: https://www.signwell.com/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: Security, Availability, and Confidentiality\n  period: null\n  issuer: independent third-party CPA firm\n  report_access: on_request\n  text: Please contact @signwell.com to request SignWell's most recent SOC 2 report.\n- framework: HIPAA\n  type: HIPAA compliance with Business Associate Agreement\n  scope: SignWell platform; BAA for\
  \ customers on paid plans\n  period: null\n  issuer: third party audit\n  report_access: on_request\n  text: SignWell signs a Business Associate Agreement (BAA) with customers on paid plans at no extra cost\n- framework: GDPR\n  type: GDPR compliance statement\n  scope: personal data of users\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SignWell has implemented these requirements and is compliant with all the principles of the GDPR.\n- framework: ISO27001\n  type: AWS data center certification\n  scope: AWS data centers and services used by SignWell\n  period: null\n  issuer: independent auditors\n  report_access: unstated\n  text: Both AWS data centers and services are certified by independent auditors according to ISO 27001\n- framework: ISO27017\n  type: AWS data center certification\n  scope: AWS data centers and services used by SignWell\n  period: null\n  issuer: independent auditors\n  report_access: unstated\n  text: ISO 27017 (information security management\
  \ systems in the cloud)\n- framework: ISO27018\n  type: AWS data center certification\n  scope: AWS data centers and services used by SignWell\n  period: null\n  issuer: independent auditors\n  report_access: unstated\n  text: ISO 27018 (information privacy in the cloud)\n- framework: other\n  type: NOM-151 preservation certificate support via SeguriData PSC partnership\n  scope: completed documents for businesses in Mexico\n  period: null\n  issuer: SeguriData, accredited Prestador de Servicios de Certificación\n  report_access: unstated\n  text: SignWell supports NOM-151 compliance through our partnership with SeguriData\n"
source_yaml_url: https://artifacts.apis.io/signwell/compliance/signwell-compliance.yml
stated_fields:
- attestations
summary_line: 7 quoted statements, read from SignWell's own page on 2026-11-10.
synthetic: false
tags:
- E-Signature
- Documents
- PDF
- Signing
- Templates
- Workflows
- HIPAA
- SOC 2
---
