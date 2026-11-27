---
api_specs:
- filename: aws-healthlake-datastore-api-openapi.yml
  format: yaml
  label: AWS HealthLake Datastore API
  slug: aws-healthlake-datastore-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aws-healthlake/openapi/aws-healthlake-datastore-api-openapi.yml
- filename: aws-healthlake-export-api-openapi.yml
  format: yaml
  label: AWS HealthLake Export API
  slug: aws-healthlake-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aws-healthlake/openapi/aws-healthlake-export-api-openapi.yml
- filename: aws-healthlake-import-api-openapi.yml
  format: yaml
  label: AWS HealthLake Import API
  slug: aws-healthlake-import-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aws-healthlake/openapi/aws-healthlake-import-api-openapi.yml
- filename: aws-healthlake-tags-api-openapi.yml
  format: yaml
  label: AWS HealthLake Tags API
  slug: aws-healthlake-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aws-healthlake/openapi/aws-healthlake-tags-api-openapi.yml
- filename: aws-healthlake-data-transformation-job-api-openapi.yml
  format: yaml
  label: AWS HealthLake Healthlake Data Transformation Job API
  slug: aws-healthlake-data-transformation-job-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aws-healthlake/openapi/aws-healthlake-data-transformation-job-api-openapi.yml
- filename: aws-healthlake-data-transformation-profile-api-openapi.yml
  format: yaml
  label: AWS HealthLake Healthlake Data Transformation Profile API
  slug: aws-healthlake-data-transformation-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aws-healthlake/openapi/aws-healthlake-data-transformation-profile-api-openapi.yml
- filename: aws-healthlake-operations-api-openapi.yml
  format: yaml
  label: AWS HealthLake Healthlake Operations API
  slug: aws-healthlake-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aws-healthlake/openapi/aws-healthlake-operations-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: AWS overall
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: compliance certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: AWS overall
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: compliance certification
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: AWS overall
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: compliance certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: AWS overall
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: compliance certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: AWS overall
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: compliance certification (NIST 800-171)
  trust_center:
    url: https://aws.amazon.com/compliance/
frameworks:
- FedRAMP
- GDPR
- HIPAA
- PCI-DSS
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: AWS HealthLake
provenance_date: '2026-11-09'
provider_name: AWS HealthLake
provider_slug: aws-healthlake
slug: aws-healthlake-compliance
source_date: '2026-11-09'
source_filename: aws-healthlake-compliance.yml
source_heading: Compliance
source_page: https://aws.amazon.com/compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: AWS HealthLake\naid: aws-healthlake\nurl: https://aws.amazon.com/compliance/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/aws-healthlake-trust-center.yml\ntrust_center:\n  url: https://aws.amazon.com/compliance/\nattestations:\n- framework: PCI-DSS\n  type: compliance certification\n  scope: AWS overall\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n- framework: HIPAA\n  type: compliance certification\n  scope: AWS overall\n  period:\
  \ null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n- framework: FedRAMP\n  type: compliance certification\n  scope: AWS overall\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n- framework: GDPR\n  type: compliance certification\n  scope: AWS overall\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n- framework: other\n  type: compliance certification (NIST 800-171)\n  scope: AWS overall\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance\
  \ certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n"
source_yaml_url: https://artifacts.apis.io/aws-healthlake/compliance/aws-healthlake-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from AWS HealthLake's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- FHIR
- Health Data
- Clinical Data
- HIPAA
- Interoperability
- Natural Language Processing
- Medical
- HL7
- Amazon Web Services
---
