---
api_specs:
- filename: amazon-network-firewall-aws-network-firewall-api-openapi.yml
  format: yaml
  label: Amazon Network Firewall AWS Network Firewall API
  slug: amazon-network-firewall-aws-network-firewall-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-network-firewall/openapi/amazon-network-firewall-aws-network-firewall-api-openapi.yml
- filename: amazon-network-firewall-network-firewall-transit-gateway-attachment-api-openapi.yml
  format: yaml
  label: Amazon Network Firewall Network Firewall Network Firewall Transit Gateway Attachment API
  slug: amazon-network-firewall-network-firewall-transit-gateway-attachment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-network-firewall/openapi/amazon-network-firewall-network-firewall-transit-gateway-attachment-api-openapi.yml
- filename: amazon-network-firewall-container-association-api-openapi.yml
  format: yaml
  label: Amazon Network Firewall Network Firewall Container Association API
  slug: amazon-network-firewall-container-association-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-network-firewall/openapi/amazon-network-firewall-container-association-api-openapi.yml
- filename: amazon-network-firewall-operations-api-openapi.yml
  format: yaml
  label: Amazon Network Firewall Network Firewall Operations API
  slug: amazon-network-firewall-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-network-firewall/openapi/amazon-network-firewall-operations-api-openapi.yml
- filename: amazon-network-firewall-proxy-api-openapi.yml
  format: yaml
  label: Amazon Network Firewall Network Firewall Proxy API
  slug: amazon-network-firewall-proxy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-network-firewall/openapi/amazon-network-firewall-proxy-api-openapi.yml
- filename: amazon-network-firewall-proxy-configuration-api-openapi.yml
  format: yaml
  label: Amazon Network Firewall Network Firewall Proxy Configuration API
  slug: amazon-network-firewall-proxy-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-network-firewall/openapi/amazon-network-firewall-proxy-configuration-api-openapi.yml
- filename: amazon-network-firewall-proxy-rule-api-openapi.yml
  format: yaml
  label: Amazon Network Firewall Network Firewall Proxy Rule API
  slug: amazon-network-firewall-proxy-rule-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-network-firewall/openapi/amazon-network-firewall-proxy-rule-api-openapi.yml
- filename: amazon-network-firewall-proxy-rule-group-api-openapi.yml
  format: yaml
  label: Amazon Network Firewall Network Firewall Proxy Rule Group API
  slug: amazon-network-firewall-proxy-rule-group-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-network-firewall/openapi/amazon-network-firewall-proxy-rule-group-api-openapi.yml
- filename: amazon-network-firewall-vpc-endpoint-association-api-openapi.yml
  format: yaml
  label: Amazon Network Firewall Network Firewall Vpc Endpoint Association API
  slug: amazon-network-firewall-vpc-endpoint-association-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-network-firewall/openapi/amazon-network-firewall-vpc-endpoint-association-api-openapi.yml
- filename: amazon-network-firewall-firewall-policy-v2-api-openapi.yml
  format: yaml
  label: Amazon Network Firewall Network Firewall Firewall Policy V2 API
  slug: amazon-network-firewall-firewall-policy-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-network-firewall/openapi/amazon-network-firewall-firewall-policy-v2-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.
    type: certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.
    type: certification
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.
    type: certification
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
name: Amazon Network Firewall
provenance_date: '2026-11-09'
provider_name: Amazon Network Firewall
provider_slug: amazon-network-firewall
slug: amazon-network-firewall-compliance
source_date: '2026-11-09'
source_filename: amazon-network-firewall-compliance.yml
source_heading: Compliance
source_page: https://aws.amazon.com/compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Amazon Network Firewall\naid: amazon-network-firewall\nurl: https://aws.amazon.com/compliance/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/amazon-network-firewall-trust-center.yml\ntrust_center:\n  url: https://aws.amazon.com/compliance/\nattestations:\n- framework: PCI-DSS\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.\n\
  - framework: HIPAA\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.\n- framework: FedRAMP\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance requirements around the globe.\n- framework: GDPR\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171, helping customers satisfy compliance\
  \ requirements around the globe.\n"
source_yaml_url: https://artifacts.apis.io/amazon-network-firewall/compliance/amazon-network-firewall-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Amazon Network Firewall's own page on 2026-11-09.
synthetic: false
tags:
- Amazon Web Services
- Firewall
- Intrusion Detection
- Network Security
- VPC
---
