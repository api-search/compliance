---
api_specs:
- filename: amazon-compute-optimizer-aws-compute-optimizer-api-openapi.yml
  format: yaml
  label: Amazon Compute Optimizer AWS Compute Optimizer API
  slug: amazon-compute-optimizer-aws-compute-optimizer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-compute-optimizer/openapi/amazon-compute-optimizer-aws-compute-optimizer-api-openapi.yml
- filename: amazon-compute-optimizer-operations-api-openapi.yml
  format: yaml
  label: Amazon Compute Optimizer Compute Optimizer Operations API
  slug: amazon-compute-optimizer-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-compute-optimizer/openapi/amazon-compute-optimizer-operations-api-openapi.yml
- filename: amazon-compute-optimizer-account-api-openapi.yml
  format: yaml
  label: Amazon Compute Optimizer Compute Optimizer Account API
  slug: amazon-compute-optimizer-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-compute-optimizer/openapi/amazon-compute-optimizer-account-api-openapi.yml
- filename: amazon-compute-optimizer-automation-event-api-openapi.yml
  format: yaml
  label: Amazon Compute Optimizer Compute Optimizer Automation Event API
  slug: amazon-compute-optimizer-automation-event-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-compute-optimizer/openapi/amazon-compute-optimizer-automation-event-api-openapi.yml
- filename: amazon-compute-optimizer-automation-rule-api-openapi.yml
  format: yaml
  label: Amazon Compute Optimizer Compute Optimizer Automation Rule API
  slug: amazon-compute-optimizer-automation-rule-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-compute-optimizer/openapi/amazon-compute-optimizer-automation-rule-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: null
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: null
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: null
  - framework: GDPR
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: null
  - framework: other
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: FIPS 140-3
  - framework: other
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: NIST 800-171
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
name: Amazon Compute Optimizer
provenance_date: '2026-11-09'
provider_name: Amazon Compute Optimizer
provider_slug: amazon-compute-optimizer
slug: amazon-compute-optimizer-compliance
source_date: '2026-11-09'
source_filename: amazon-compute-optimizer-compliance.yml
source_heading: Compliance
source_page: https://aws.amazon.com/compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Amazon Compute Optimizer\naid: amazon-compute-optimizer\nurl: https://aws.amazon.com/compliance/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/amazon-compute-optimizer-trust-center.yml\ntrust_center:\n  url: https://aws.amazon.com/compliance/\nattestations:\n- framework: PCI-DSS\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer:\
  \ null\n  report_access: on_request\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n- framework: FedRAMP\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n- framework: other\n  type: FIPS 140-3\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n\
  - framework: other\n  type: NIST 800-171\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n"
source_yaml_url: https://artifacts.apis.io/amazon-compute-optimizer/compliance/amazon-compute-optimizer-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Amazon Compute Optimizer's own page on 2026-11-09.
synthetic: false
tags:
- Amazon Web Services
- Cost Optimization
- FinOps
- Machine Learning
- Resource Recommendations
---
