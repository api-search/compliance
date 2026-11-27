---
api_specs:
- filename: amazon-iam-access-analyzer-access-preview-api-openapi.yml
  format: yaml
  label: Amazon IAM Access Analyzer Access Preview API
  slug: amazon-iam-access-analyzer-access-preview-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-iam-access-analyzer/openapi/amazon-iam-access-analyzer-access-preview-api-openapi.yml
- filename: amazon-iam-access-analyzer-analyzed-resource-api-openapi.yml
  format: yaml
  label: Amazon IAM Access Analyzer Analyzed Resource API
  slug: amazon-iam-access-analyzer-analyzed-resource-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-iam-access-analyzer/openapi/amazon-iam-access-analyzer-analyzed-resource-api-openapi.yml
- filename: amazon-iam-access-analyzer-analyzer-api-openapi.yml
  format: yaml
  label: Amazon IAM Access Analyzer API
  slug: amazon-iam-access-analyzer-analyzer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-iam-access-analyzer/openapi/amazon-iam-access-analyzer-analyzer-api-openapi.yml
- filename: amazon-iam-access-analyzer-archive-rule-api-openapi.yml
  format: yaml
  label: Amazon IAM Access Analyzer Archive Rule API
  slug: amazon-iam-access-analyzer-archive-rule-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-iam-access-analyzer/openapi/amazon-iam-access-analyzer-archive-rule-api-openapi.yml
- filename: amazon-iam-access-analyzer-finding-api-openapi.yml
  format: yaml
  label: Amazon IAM Access Analyzer Finding API
  slug: amazon-iam-access-analyzer-finding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-iam-access-analyzer/openapi/amazon-iam-access-analyzer-finding-api-openapi.yml
- filename: amazon-iam-access-analyzer-policy-api-openapi.yml
  format: yaml
  label: Amazon IAM Access Analyzer Policy API
  slug: amazon-iam-access-analyzer-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-iam-access-analyzer/openapi/amazon-iam-access-analyzer-policy-api-openapi.yml
- filename: amazon-iam-access-analyzer-resource-api-openapi.yml
  format: yaml
  label: Amazon IAM Access Analyzer Resource API
  slug: amazon-iam-access-analyzer-resource-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-iam-access-analyzer/openapi/amazon-iam-access-analyzer-resource-api-openapi.yml
- filename: amazon-iam-access-analyzer-tags-api-openapi.yml
  format: yaml
  label: Amazon IAM Access Analyzer Tags API
  slug: amazon-iam-access-analyzer-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-iam-access-analyzer/openapi/amazon-iam-access-analyzer-tags-api-openapi.yml
- filename: amazon-iam-access-analyzer-operations-api-openapi.yml
  format: yaml
  label: Amazon IAM Access Analyzer Iam Access Analyzer Operations API
  slug: amazon-iam-access-analyzer-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-iam-access-analyzer/openapi/amazon-iam-access-analyzer-operations-api-openapi.yml
claim_count: 6
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
    type: certification (FIPS 140-3)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: standard (NIST 800-171)
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
name: Amazon IAM Access Analyzer
provenance_date: '2026-11-09'
provider_name: Amazon IAM Access Analyzer
provider_slug: amazon-iam-access-analyzer
slug: amazon-iam-access-analyzer-compliance
source_date: '2026-11-09'
source_filename: amazon-iam-access-analyzer-compliance.yml
source_heading: Compliance
source_page: https://aws.amazon.com/compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Amazon IAM Access Analyzer\naid: amazon-iam-access-analyzer\nurl: https://aws.amazon.com/compliance/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/amazon-iam-access-analyzer-trust-center.yml\ntrust_center:\n  url: https://aws.amazon.com/compliance/\nattestations:\n- framework: PCI-DSS\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n- framework: HIPAA\n  type: certification\n  scope: null\n  period:\
  \ null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n- framework: FedRAMP\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n- framework: GDPR\n  type: regulation\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n- framework: other\n  type: certification (FIPS 140-3)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n\
  \    GDPR, FIPS 140-3, and NIST 800-171\n- framework: other\n  type: standard (NIST 800-171)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n"
source_yaml_url: https://artifacts.apis.io/amazon-iam-access-analyzer/compliance/amazon-iam-access-analyzer-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Amazon IAM Access Analyzer's own page on 2026-11-09.
synthetic: false
tags:
- Access Control
- Amazon Web Services
- Compliance
- Identity and Access Management
- Policy Management
- Security
---
