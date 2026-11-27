---
api_specs:
- filename: amazon-organizations-organizations-api-openapi.yml
  format: yaml
  label: Amazon Organizations API
  slug: amazon-organizations-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-organizations/openapi/amazon-organizations-organizations-api-openapi.yml
- filename: amazon-organizations-account-api-openapi.yml
  format: yaml
  label: Amazon Organizations Organizations Account API
  slug: amazon-organizations-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-organizations/openapi/amazon-organizations-account-api-openapi.yml
- filename: amazon-organizations-aws-service-access-api-openapi.yml
  format: yaml
  label: Amazon Organizations Organizations Aws Service Access API
  slug: amazon-organizations-aws-service-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-organizations/openapi/amazon-organizations-aws-service-access-api-openapi.yml
- filename: amazon-organizations-delegated-administrator-api-openapi.yml
  format: yaml
  label: Amazon Organizations Organizations Delegated Administrator API
  slug: amazon-organizations-delegated-administrator-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-organizations/openapi/amazon-organizations-delegated-administrator-api-openapi.yml
- filename: amazon-organizations-handshake-api-openapi.yml
  format: yaml
  label: Amazon Organizations Organizations Handshake API
  slug: amazon-organizations-handshake-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-organizations/openapi/amazon-organizations-handshake-api-openapi.yml
- filename: amazon-organizations-operations-api-openapi.yml
  format: yaml
  label: Amazon Organizations Organizations Operations API
  slug: amazon-organizations-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-organizations/openapi/amazon-organizations-operations-api-openapi.yml
- filename: amazon-organizations-organizational-unit-api-openapi.yml
  format: yaml
  label: Amazon Organizations Organizations Organizational Unit API
  slug: amazon-organizations-organizational-unit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-organizations/openapi/amazon-organizations-organizational-unit-api-openapi.yml
- filename: amazon-organizations-policy-api-openapi.yml
  format: yaml
  label: Amazon Organizations Organizations Policy API
  slug: amazon-organizations-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-organizations/openapi/amazon-organizations-policy-api-openapi.yml
- filename: amazon-organizations-resource-policy-api-openapi.yml
  format: yaml
  label: Amazon Organizations Organizations Resource Policy API
  slug: amazon-organizations-resource-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-organizations/openapi/amazon-organizations-resource-policy-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: certification
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: regulation
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: standard
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
name: Amazon Organizations
provenance_date: '2026-11-09'
provider_name: Amazon Organizations
provider_slug: amazon-organizations
slug: amazon-organizations-compliance
source_date: '2026-11-09'
source_filename: amazon-organizations-compliance.yml
source_heading: Compliance
source_page: https://aws.amazon.com/compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Amazon Organizations\naid: amazon-organizations\nurl: https://aws.amazon.com/compliance/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://aws.amazon.com/compliance/\nattestations:\n- framework: PCI-DSS\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n- framework: HIPAA\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security\
  \ standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n- framework: FedRAMP\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n- framework: GDPR\n  type: regulation\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n- framework: other\n  type: standard\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n"
source_yaml_url: https://artifacts.apis.io/amazon-organizations/compliance/amazon-organizations-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Amazon Organizations's own page on 2026-11-09.
synthetic: false
tags:
- Account Management
- Amazon Web Services
- Consolidated Billing
- Governance
- Multi-Account
- Organization
- Policies
---
