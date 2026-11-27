---
api_specs:
- filename: amazon-sqs-messages-api-openapi.yml
  format: yaml
  label: Amazon SQS Messages API
  slug: amazon-sqs-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-sqs/openapi/amazon-sqs-messages-api-openapi.yml
- filename: amazon-sqs-permissions-api-openapi.yml
  format: yaml
  label: Amazon SQS Permissions API
  slug: amazon-sqs-permissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-sqs/openapi/amazon-sqs-permissions-api-openapi.yml
- filename: amazon-sqs-queues-api-openapi.yml
  format: yaml
  label: Amazon SQS Queues API
  slug: amazon-sqs-queues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-sqs/openapi/amazon-sqs-queues-api-openapi.yml
- filename: amazon-sqs-tags-api-openapi.yml
  format: yaml
  label: Amazon SQS Tags API
  slug: amazon-sqs-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-sqs/openapi/amazon-sqs-tags-api-openapi.yml
claim_count: 10
description: ''
doc:
  attestations:
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: AWS services in scope; SQS not named in visible text
    text: FedRAMP Federal Risk and Authorization Management Program
    type: Program listed
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: AWS services in scope; SQS not named in visible text
    text: HIPAA BAA Health Insurance Portability and Accountability Act
    type: BAA listed
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: AWS services in scope; SQS not named in visible text
    text: PCI Payment Card Industry Standards
    type: Program listed
  - framework: C5
    issuer: null
    period: null
    report_access: unstated
    scope: AWS services in scope; SQS not named in visible text
    text: C5 Cloud Computing Compliance Controls Catalog
    type: Program listed
  - framework: IRAP
    issuer: null
    period: null
    report_access: unstated
    scope: AWS services in scope; SQS not named in visible text
    text: IRAP Information Security Registered Assessors Program
    type: Program listed
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: AWS services in scope; SQS not named in visible text
    text: Cloud Security Alliance (CSA) Security Trust Assurance and Risk (STAR)
    type: Certification listed
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://aws.amazon.com/compliance/
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.
    type: certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://aws.amazon.com/compliance/
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.
    type: certification
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://aws.amazon.com/compliance/
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://aws.amazon.com/compliance/
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.
    type: regulation
  trust_center:
    url: https://aws.amazon.com/compliance/services-in-scope/
frameworks:
- C5
- CSA-STAR
- FedRAMP
- GDPR
- HIPAA
- IRAP
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Amazon SQS
provenance_date: '2026-11-09'
provider_name: Amazon SQS
provider_slug: amazon-sqs
slug: amazon-sqs-compliance
source_date: '2026-11-09'
source_filename: amazon-sqs-compliance.yml
source_heading: Compliance
source_page: https://aws.amazon.com/compliance/services-in-scope/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Amazon SQS\naid: amazon-sqs\nurl: https://aws.amazon.com/compliance/services-in-scope/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/amazon-sqs-trust-center.yml\n  sources:\n  - https://aws.amazon.com/compliance/\n  - https://aws.amazon.com/compliance/services-in-scope/\ntrust_center:\n  url: https://aws.amazon.com/compliance/services-in-scope/\nattestations:\n- framework: FedRAMP\n  type: Program listed\n  scope: AWS services in scope; SQS not named in visible text\n  period: null\n  issuer: null\n  report_access: unstated\n  text: FedRAMP Federal Risk and Authorization Management Program\n- framework:\
  \ HIPAA\n  type: BAA listed\n  scope: AWS services in scope; SQS not named in visible text\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA BAA Health Insurance Portability and Accountability Act\n- framework: PCI-DSS\n  type: Program listed\n  scope: AWS services in scope; SQS not named in visible text\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI Payment Card Industry Standards\n- framework: C5\n  type: Program listed\n  scope: AWS services in scope; SQS not named in visible text\n  period: null\n  issuer: null\n  report_access: unstated\n  text: C5 Cloud Computing Compliance Controls Catalog\n- framework: IRAP\n  type: Program listed\n  scope: AWS services in scope; SQS not named in visible text\n  period: null\n  issuer: null\n  report_access: unstated\n  text: IRAP Information Security Registered Assessors Program\n- framework: CSA-STAR\n  type: Certification listed\n  scope: AWS services in scope; SQS not named in visible text\n\
  \  period: null\n  issuer: null\n  report_access: unstated\n  text: Cloud Security Alliance (CSA) Security Trust Assurance and Risk (STAR)\n- framework: PCI-DSS\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.\n  source: https://aws.amazon.com/compliance/\n- framework: HIPAA\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.\n  source: https://aws.amazon.com/compliance/\n- framework: FedRAMP\n  type: certification\n  scope: null\n  period: null\n \
  \ issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.\n  source: https://aws.amazon.com/compliance/\n- framework: GDPR\n  type: regulation\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.\n  source: https://aws.amazon.com/compliance/\n"
source_yaml_url: https://artifacts.apis.io/amazon-sqs/compliance/amazon-sqs-compliance.yml
stated_fields:
- attestations
summary_line: 10 quoted statements, read from Amazon SQS's own page on 2026-11-09.
synthetic: false
tags:
- Amazon Web Services
- Cloud
- Distributed Systems
- Messaging
- Microservices
- Queues
---
