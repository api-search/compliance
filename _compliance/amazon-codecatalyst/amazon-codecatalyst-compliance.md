---
api_specs:
- filename: amazon-codecatalyst-session-api-openapi.yml
  format: yaml
  label: Amazon CodeCatalyst Session API
  slug: amazon-codecatalyst-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-codecatalyst/openapi/amazon-codecatalyst-session-api-openapi.yml
- filename: amazon-codecatalyst-spaces-api-openapi.yml
  format: yaml
  label: Amazon CodeCatalyst Spaces API
  slug: amazon-codecatalyst-spaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-codecatalyst/openapi/amazon-codecatalyst-spaces-api-openapi.yml
- filename: amazon-codecatalyst-devenvironments-api-openapi.yml
  format: yaml
  label: Amazon CodeCatalyst Codecatalyst Devenvironments API
  slug: amazon-codecatalyst-devenvironments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-codecatalyst/openapi/amazon-codecatalyst-devenvironments-api-openapi.yml
- filename: amazon-codecatalyst-operations-api-openapi.yml
  format: yaml
  label: Amazon CodeCatalyst Codecatalyst Operations API
  slug: amazon-codecatalyst-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-codecatalyst/openapi/amazon-codecatalyst-operations-api-openapi.yml
- filename: amazon-codecatalyst-workflowruns-api-openapi.yml
  format: yaml
  label: Amazon CodeCatalyst Codecatalyst Workflowruns API
  slug: amazon-codecatalyst-workflowruns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-codecatalyst/openapi/amazon-codecatalyst-workflowruns-api-openapi.yml
- filename: amazon-codecatalyst-access-tokens-api-openapi.yml
  format: yaml
  label: Amazon CodeCatalyst Access Tokens API
  slug: amazon-codecatalyst-access-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-codecatalyst/openapi/amazon-codecatalyst-access-tokens-api-openapi.yml
- filename: amazon-codecatalyst-user-details-api-openapi.yml
  format: yaml
  label: Amazon CodeCatalyst User Details API
  slug: amazon-codecatalyst-user-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-codecatalyst/openapi/amazon-codecatalyst-user-details-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: on_request
    scope: AWS-wide
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: compliance certification (AWS-wide)
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: AWS-wide
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: compliance certification (AWS-wide)
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: on_request
    scope: AWS-wide
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: compliance certification (AWS-wide)
  - framework: GDPR
    issuer: null
    period: null
    report_access: on_request
    scope: AWS-wide
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: compliance regime (AWS-wide)
  trust_center:
    url: https://aws.amazon.com/compliance/
frameworks:
- FedRAMP
- GDPR
- HIPAA
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Amazon CodeCatalyst
provenance_date: '2026-11-09'
provider_name: Amazon CodeCatalyst
provider_slug: amazon-codecatalyst
slug: amazon-codecatalyst-compliance
source_date: '2026-11-09'
source_filename: amazon-codecatalyst-compliance.yml
source_heading: Compliance
source_page: https://aws.amazon.com/compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Amazon CodeCatalyst\naid: amazon-codecatalyst\nurl: https://aws.amazon.com/compliance/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/amazon-codecatalyst-trust-center.yml\ntrust_center:\n  url: https://aws.amazon.com/compliance/\nattestations:\n- framework: PCI-DSS\n  type: compliance certification (AWS-wide)\n  scope: AWS-wide\n  period: null\n  issuer: null\n  report_access: on_request\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n- framework: HIPAA\n  type: compliance certification (AWS-wide)\n\
  \  scope: AWS-wide\n  period: null\n  issuer: null\n  report_access: on_request\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n- framework: FedRAMP\n  type: compliance certification (AWS-wide)\n  scope: AWS-wide\n  period: null\n  issuer: null\n  report_access: on_request\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n- framework: GDPR\n  type: compliance regime (AWS-wide)\n  scope: AWS-wide\n  period: null\n  issuer: null\n  report_access: on_request\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n"
source_yaml_url: https://artifacts.apis.io/amazon-codecatalyst/compliance/amazon-codecatalyst-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Amazon CodeCatalyst's own page on 2026-11-09.
synthetic: false
tags:
- Amazon
- Amazon Web Services
- Developer Tools
- CI/CD
- Collaboration
- DevOps
- Version Control
---
