---
api_specs:
- filename: amazon-firewall-manager-admin-accounts-api-openapi.yml
  format: yaml
  label: Amazon Firewall Manager Admin Accounts API
  slug: amazon-firewall-manager-admin-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-firewall-manager/openapi/amazon-firewall-manager-admin-accounts-api-openapi.yml
- filename: amazon-firewall-manager-compliance-api-openapi.yml
  format: yaml
  label: Amazon Firewall Manager Compliance API
  slug: amazon-firewall-manager-compliance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-firewall-manager/openapi/amazon-firewall-manager-compliance-api-openapi.yml
- filename: amazon-firewall-manager-member-accounts-api-openapi.yml
  format: yaml
  label: Amazon Firewall Manager Member Accounts API
  slug: amazon-firewall-manager-member-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-firewall-manager/openapi/amazon-firewall-manager-member-accounts-api-openapi.yml
- filename: amazon-firewall-manager-policies-api-openapi.yml
  format: yaml
  label: Amazon Firewall Manager Policies API
  slug: amazon-firewall-manager-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-firewall-manager/openapi/amazon-firewall-manager-policies-api-openapi.yml
- filename: amazon-firewall-manager-resources-api-openapi.yml
  format: yaml
  label: Amazon Firewall Manager Resources API
  slug: amazon-firewall-manager-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-firewall-manager/openapi/amazon-firewall-manager-resources-api-openapi.yml
- filename: amazon-firewall-manager-apps-list-api-openapi.yml
  format: yaml
  label: Amazon Firewall Manager Firewall Manager Apps List API
  slug: amazon-firewall-manager-apps-list-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-firewall-manager/openapi/amazon-firewall-manager-apps-list-api-openapi.yml
- filename: amazon-firewall-manager-notification-channel-api-openapi.yml
  format: yaml
  label: Amazon Firewall Manager Firewall Manager Notification Channel API
  slug: amazon-firewall-manager-notification-channel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-firewall-manager/openapi/amazon-firewall-manager-notification-channel-api-openapi.yml
- filename: amazon-firewall-manager-operations-api-openapi.yml
  format: yaml
  label: Amazon Firewall Manager Firewall Manager Operations API
  slug: amazon-firewall-manager-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-firewall-manager/openapi/amazon-firewall-manager-operations-api-openapi.yml
- filename: amazon-firewall-manager-protocols-list-api-openapi.yml
  format: yaml
  label: Amazon Firewall Manager Firewall Manager Protocols List API
  slug: amazon-firewall-manager-protocols-list-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-firewall-manager/openapi/amazon-firewall-manager-protocols-list-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: AWS services
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.
    type: null
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: AWS services
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.
    type: null
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: AWS services
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.
    type: null
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: AWS services
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.
    type: null
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
name: Amazon Firewall Manager
provenance_date: '2026-11-09'
provider_name: Amazon Firewall Manager
provider_slug: amazon-firewall-manager
slug: amazon-firewall-manager-compliance
source_date: '2026-11-09'
source_filename: amazon-firewall-manager-compliance.yml
source_heading: Compliance
source_page: https://aws.amazon.com/compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Amazon Firewall Manager\naid: amazon-firewall-manager\nurl: https://aws.amazon.com/compliance/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/amazon-firewall-manager-trust-center.yml\ntrust_center:\n  url: https://aws.amazon.com/compliance/\nattestations:\n- framework: PCI-DSS\n  type: null\n  scope: AWS services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.\n-\
  \ framework: HIPAA\n  type: null\n  scope: AWS services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.\n- framework: FedRAMP\n  type: null\n  scope: AWS services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.\n- framework: GDPR\n  type: null\n  scope: AWS services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements\
  \ around the globe.\n"
source_yaml_url: https://artifacts.apis.io/amazon-firewall-manager/compliance/amazon-firewall-manager-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Amazon Firewall Manager's own page on 2026-11-09.
synthetic: false
tags:
- Amazon Web Services
- Compliance
- Firewall
- Network Security
- Security
---
