---
api_specs:
- filename: amazon-s3-glacier-vaults-api-openapi.yml
  format: yaml
  label: Amazon S3 Glacier Vaults API
  slug: amazon-s3-glacier-vaults-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-s3-glacier/openapi/amazon-s3-glacier-vaults-api-openapi.yml
- filename: amazon-s3-glacier-access-policy-api-openapi.yml
  format: yaml
  label: Amazon S3 Glacier S3 Glacier Access Policy API
  slug: amazon-s3-glacier-access-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-s3-glacier/openapi/amazon-s3-glacier-access-policy-api-openapi.yml
- filename: amazon-s3-glacier-lock-policy-api-openapi.yml
  format: yaml
  label: Amazon S3 Glacier S3 Glacier Lock Policy API
  slug: amazon-s3-glacier-lock-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-s3-glacier/openapi/amazon-s3-glacier-lock-policy-api-openapi.yml
- filename: amazon-s3-glacier-multipart-uploads-api-openapi.yml
  format: yaml
  label: Amazon S3 Glacier S3 Glacier Multipart Uploads API
  slug: amazon-s3-glacier-multipart-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-s3-glacier/openapi/amazon-s3-glacier-multipart-uploads-api-openapi.yml
- filename: amazon-s3-glacier-notification-configuration-api-openapi.yml
  format: yaml
  label: Amazon S3 Glacier S3 Glacier Notification Configuration API
  slug: amazon-s3-glacier-notification-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-s3-glacier/openapi/amazon-s3-glacier-notification-configuration-api-openapi.yml
- filename: amazon-s3-glacier-operations-api-openapi.yml
  format: yaml
  label: Amazon S3 Glacier S3 Glacier Operations API
  slug: amazon-s3-glacier-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-s3-glacier/openapi/amazon-s3-glacier-operations-api-openapi.yml
- filename: amazon-s3-glacier-tags-api-openapi.yml
  format: yaml
  label: Amazon S3 Glacier S3 Glacier Tags API
  slug: amazon-s3-glacier-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-s3-glacier/openapi/amazon-s3-glacier-tags-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.
    type: null
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.
    type: null
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.
    type: null
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.
    type: null
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.
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
name: Amazon S3 Glacier
provenance_date: '2026-11-09'
provider_name: Amazon S3 Glacier
provider_slug: amazon-s3-glacier
slug: amazon-s3-glacier-compliance
source_date: '2026-11-09'
source_filename: amazon-s3-glacier-compliance.yml
source_heading: Compliance
source_page: https://aws.amazon.com/compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Amazon S3 Glacier\naid: amazon-s3-glacier\nurl: https://aws.amazon.com/compliance/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/amazon-s3-glacier-trust-center.yml\ntrust_center:\n  url: https://aws.amazon.com/compliance/\nattestations:\n- framework: PCI-DSS\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.\n- framework: HIPAA\n  type:\
  \ null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.\n- framework: FedRAMP\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.\n- framework: other\n\
  \  type: NIST 800-171\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.\n"
source_yaml_url: https://artifacts.apis.io/amazon-s3-glacier/compliance/amazon-s3-glacier-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Amazon S3 Glacier's own page on 2026-11-09.
synthetic: false
tags:
- Archives
- Amazon Web Services
- Backup
- Storage
---
