---
api_specs:
- filename: amazon-codepipeline-executions-api-openapi.yml
  format: yaml
  label: Amazon CodePipeline Executions API
  slug: amazon-codepipeline-executions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-codepipeline/openapi/amazon-codepipeline-executions-api-openapi.yml
- filename: amazon-codepipeline-pipelines-api-openapi.yml
  format: yaml
  label: Amazon CodePipeline Pipelines API
  slug: amazon-codepipeline-pipelines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-codepipeline/openapi/amazon-codepipeline-pipelines-api-openapi.yml
- filename: amazon-codepipeline-aws-codepipeline-api-openapi.yml
  format: yaml
  label: Amazon CodePipeline AWS CodePipeline API
  slug: amazon-codepipeline-aws-codepipeline-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-codepipeline/openapi/amazon-codepipeline-aws-codepipeline-api-openapi.yml
- filename: amazon-codepipeline-operations-api-openapi.yml
  format: yaml
  label: Amazon CodePipeline Codepipeline Operations API
  slug: amazon-codepipeline-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-codepipeline/openapi/amazon-codepipeline-operations-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: AWS
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.
    type: certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: AWS
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.
    type: certification
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: AWS
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: AWS
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.
    type: regulation
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: AWS
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.
    type: standard (FIPS 140-3)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: AWS
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.
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
name: Amazon CodePipeline
provenance_date: '2026-11-09'
provider_name: Amazon CodePipeline
provider_slug: amazon-codepipeline
slug: amazon-codepipeline-compliance
source_date: '2026-11-09'
source_filename: amazon-codepipeline-compliance.yml
source_heading: Compliance
source_page: https://aws.amazon.com/compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Amazon CodePipeline\naid: amazon-codepipeline\nurl: https://aws.amazon.com/compliance/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/amazon-codepipeline-trust-center.yml\ntrust_center:\n  url: https://aws.amazon.com/compliance/\nattestations:\n- framework: PCI-DSS\n  type: certification\n  scope: AWS\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.\n- framework: HIPAA\n\
  \  type: certification\n  scope: AWS\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.\n- framework: FedRAMP\n  type: certification\n  scope: AWS\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.\n- framework: GDPR\n  type: regulation\n  scope: AWS\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the\
  \ globe.\n- framework: other\n  type: standard (FIPS 140-3)\n  scope: AWS\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.\n- framework: other\n  type: standard (NIST 800-171)\n  scope: AWS\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.\n"
source_yaml_url: https://artifacts.apis.io/amazon-codepipeline/compliance/amazon-codepipeline-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Amazon CodePipeline's own page on 2026-11-09.
synthetic: false
tags:
- Amazon
- Amazon Web Services
- CI/CD
- Continuous Delivery
- Developer Tools
- DevOps
- Pipelines
- Release Automation
---
