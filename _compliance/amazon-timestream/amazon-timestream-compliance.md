---
api_specs:
- filename: amazon-timestream-databases-api-openapi.yml
  format: yaml
  label: Amazon Timestream Databases API
  slug: amazon-timestream-databases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-timestream/openapi/amazon-timestream-databases-api-openapi.yml
- filename: amazon-timestream-query-api-openapi.yml
  format: yaml
  label: Amazon Timestream Query API
  slug: amazon-timestream-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-timestream/openapi/amazon-timestream-query-api-openapi.yml
- filename: amazon-timestream-tables-api-openapi.yml
  format: yaml
  label: Amazon Timestream Tables API
  slug: amazon-timestream-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-timestream/openapi/amazon-timestream-tables-api-openapi.yml
- filename: amazon-timestream-write-api-openapi.yml
  format: yaml
  label: Amazon Timestream Write API
  slug: amazon-timestream-write-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-timestream/openapi/amazon-timestream-write-api-openapi.yml
- filename: amazon-timestream-batch-load-task-api-openapi.yml
  format: yaml
  label: Amazon Timestream Timestream Batch Load Task API
  slug: amazon-timestream-batch-load-task-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-timestream/openapi/amazon-timestream-batch-load-task-api-openapi.yml
- filename: amazon-timestream-operations-api-openapi.yml
  format: yaml
  label: Amazon Timestream Timestream Operations API
  slug: amazon-timestream-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-timestream/openapi/amazon-timestream-operations-api-openapi.yml
- filename: amazon-timestream-scheduled-query-api-openapi.yml
  format: yaml
  label: Amazon Timestream Timestream Scheduled Query API
  slug: amazon-timestream-scheduled-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-timestream/openapi/amazon-timestream-scheduled-query-api-openapi.yml
- filename: amazon-timestream-db-backup-api-openapi.yml
  format: yaml
  label: Amazon Timestream Timestream Db Backup API
  slug: amazon-timestream-db-backup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-timestream/openapi/amazon-timestream-db-backup-api-openapi.yml
- filename: amazon-timestream-db-cluster-api-openapi.yml
  format: yaml
  label: Amazon Timestream Timestream Db Cluster API
  slug: amazon-timestream-db-cluster-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-timestream/openapi/amazon-timestream-db-cluster-api-openapi.yml
- filename: amazon-timestream-db-instance-api-openapi.yml
  format: yaml
  label: Amazon Timestream Timestream Db Instance API
  slug: amazon-timestream-db-instance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-timestream/openapi/amazon-timestream-db-instance-api-openapi.yml
- filename: amazon-timestream-db-parameter-group-api-openapi.yml
  format: yaml
  label: Amazon Timestream Timestream Db Parameter Group API
  slug: amazon-timestream-db-parameter-group-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-timestream/openapi/amazon-timestream-db-parameter-group-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: AWS-wide, not stated for Timestream
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: AWS-wide, not stated for Timestream
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: certification
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: AWS-wide, not stated for Timestream
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: AWS-wide, not stated for Timestream
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: regulation
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: AWS-wide, not stated for Timestream
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: standard (FIPS 140-3)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: AWS-wide, not stated for Timestream
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
name: Amazon Timestream
provenance_date: '2026-11-09'
provider_name: Amazon Timestream
provider_slug: amazon-timestream
slug: amazon-timestream-compliance
source_date: '2026-11-09'
source_filename: amazon-timestream-compliance.yml
source_heading: Compliance
source_page: https://aws.amazon.com/compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Amazon Timestream\naid: amazon-timestream\nurl: https://aws.amazon.com/compliance/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/amazon-timestream-trust-center.yml\ntrust_center:\n  url: https://aws.amazon.com/compliance/\nattestations:\n- framework: PCI-DSS\n  type: certification\n  scope: AWS-wide, not stated for Timestream\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n- framework: HIPAA\n  type: certification\n  scope: AWS-wide,\
  \ not stated for Timestream\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n- framework: FedRAMP\n  type: certification\n  scope: AWS-wide, not stated for Timestream\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n- framework: GDPR\n  type: regulation\n  scope: AWS-wide, not stated for Timestream\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n- framework: other\n  type: standard (FIPS 140-3)\n  scope: AWS-wide, not stated for Timestream\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n- framework: other\n  type: standard (NIST 800-171)\n  scope: AWS-wide, not stated for Timestream\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n"
source_yaml_url: https://artifacts.apis.io/amazon-timestream/compliance/amazon-timestream-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Amazon Timestream's own page on 2026-11-09.
synthetic: false
tags:
- Amazon Web Services
- Database
- IoT
- Time Series
---
