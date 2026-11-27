---
api_specs:
- filename: caspio-applications-api-openapi.yml
  format: yaml
  label: Caspio Applications API
  slug: caspio-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caspio/openapi/caspio-applications-api-openapi.yml
- filename: caspio-authentication-api-openapi.yml
  format: yaml
  label: Caspio Authentication API
  slug: caspio-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caspio/openapi/caspio-authentication-api-openapi.yml
- filename: caspio-files-api-openapi.yml
  format: yaml
  label: Caspio Files API
  slug: caspio-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caspio/openapi/caspio-files-api-openapi.yml
- filename: caspio-tables-api-openapi.yml
  format: yaml
  label: Caspio Tables API
  slug: caspio-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caspio/openapi/caspio-tables-api-openapi.yml
- filename: caspio-tasks-api-openapi.yml
  format: yaml
  label: Caspio Tasks API
  slug: caspio-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caspio/openapi/caspio-tasks-api-openapi.yml
- filename: caspio-users-api-openapi.yml
  format: yaml
  label: Caspio Users API
  slug: caspio-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caspio/openapi/caspio-users-api-openapi.yml
- filename: caspio-views-api-openapi.yml
  format: yaml
  label: Caspio Views API
  slug: caspio-views-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caspio/openapi/caspio-views-api-openapi.yml
claim_count: 7
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent auditor
    period: null
    report_access: nda
    scope: security controls across five trust service criteria
    text: Caspio is SOC 2 Type II certified, with security controls independently certified annually across five trust service criteria
    type: SOC 2 Type II certification
  - framework: HIPAA
    issuer: independent certification
    period: Annual
    report_access: nda
    scope: HIPAA Edition dedicated cloud environment
    text: HIPAA Independent certification of HIPAA compliance controls Annual
    type: HIPAA compliance controls certification
  - framework: GDPR
    issuer: independent certification
    period: Annual
    report_access: unstated
    scope: GDPR compliance controls with Data Processing Agreement and EU-U.S. Data Privacy Framework adherence
    text: GDPR compliance controls are independently certified annually.
    type: GDPR compliance controls certification
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: included in all paid plans
    text: PCI DSS Level 1 Validated compliance, included in all paid plans
    type: PCI DSS Level 1 validated compliance
  - framework: ISO27001
    issuer: Amazon Web Services
    period: null
    report_access: unstated
    scope: ISO 27001, 27017 and 27018 via AWS infrastructure
    text: Because Caspio operates on AWS, it leverages AWS certifications including ISO 27001, 27017 and 27018
    type: inherited AWS certifications
  - framework: FedRAMP
    issuer: AWS GovCloud validation
    period: null
    report_access: unstated
    scope: GovCloud Edition on AWS GovCloud
    text: FIPS 140-2 AWS GovCloud validated cryptographic modules (GovCloud Edition)
    type: FIPS 140-2 validated cryptographic modules
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: digital accessibility
    text: Caspio adheres to WCAG standards and supports ADA and Section 508 requirements
    type: Standards adherence (WCAG, ADA, Section 508)
  trust_center:
    url: https://www.caspio.com/compliance/
frameworks:
- FedRAMP
- GDPR
- HIPAA
- ISO27001
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Caspio
provenance_date: '2026-11-09'
provider_name: Caspio
provider_slug: caspio
slug: caspio-compliance
source_date: '2026-11-09'
source_filename: caspio-compliance.yml
source_heading: Compliance
source_page: https://www.caspio.com/compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Caspio\naid: caspio\nurl: https://www.caspio.com/compliance/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/caspio-trust-center.yml\ntrust_center:\n  url: https://www.caspio.com/compliance/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II certification\n  scope: security controls across five trust service criteria\n  period: null\n  issuer: independent auditor\n  report_access: nda\n  text: Caspio is SOC 2 Type II certified, with security controls independently certified annually across five trust\n    service criteria\n- framework: HIPAA\n  type: HIPAA compliance controls certification\n\
  \  scope: HIPAA Edition dedicated cloud environment\n  period: Annual\n  issuer: independent certification\n  report_access: nda\n  text: HIPAA Independent certification of HIPAA compliance controls Annual\n- framework: GDPR\n  type: GDPR compliance controls certification\n  scope: GDPR compliance controls with Data Processing Agreement and EU-U.S. Data Privacy Framework adherence\n  period: Annual\n  issuer: independent certification\n  report_access: unstated\n  text: GDPR compliance controls are independently certified annually.\n- framework: PCI-DSS\n  type: PCI DSS Level 1 validated compliance\n  scope: included in all paid plans\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS Level 1 Validated compliance, included in all paid plans\n- framework: ISO27001\n  type: inherited AWS certifications\n  scope: ISO 27001, 27017 and 27018 via AWS infrastructure\n  period: null\n  issuer: Amazon Web Services\n  report_access: unstated\n  text: Because Caspio operates\
  \ on AWS, it leverages AWS certifications including ISO 27001, 27017 and 27018\n- framework: FedRAMP\n  type: FIPS 140-2 validated cryptographic modules\n  scope: GovCloud Edition on AWS GovCloud\n  period: null\n  issuer: AWS GovCloud validation\n  report_access: unstated\n  text: FIPS 140-2 AWS GovCloud validated cryptographic modules (GovCloud Edition)\n- framework: other\n  type: Standards adherence (WCAG, ADA, Section 508)\n  scope: digital accessibility\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Caspio adheres to WCAG standards and supports ADA and Section 508 requirements\n"
source_yaml_url: https://artifacts.apis.io/caspio/compliance/caspio-compliance.yml
stated_fields:
- attestations
summary_line: 7 quoted statements, read from Caspio's own page on 2026-11-09.
synthetic: false
tags:
- Low-Code
- No-Code
- Database
- Application Platform
- Cloud Database
- Online Forms
- Workflow Automation
---
