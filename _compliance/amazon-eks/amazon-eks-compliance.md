---
api_specs:
- filename: amazon-eks-clusters-api-openapi.yml
  format: yaml
  label: Amazon EKS Clusters API
  slug: amazon-eks-clusters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-eks/openapi/amazon-eks-clusters-api-openapi.yml
- filename: amazon-eks-fargate-profiles-api-openapi.yml
  format: yaml
  label: Amazon EKS Fargate Profiles API
  slug: amazon-eks-fargate-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-eks/openapi/amazon-eks-fargate-profiles-api-openapi.yml
- filename: amazon-eks-node-groups-api-openapi.yml
  format: yaml
  label: Amazon EKS Node Groups API
  slug: amazon-eks-node-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-eks/openapi/amazon-eks-node-groups-api-openapi.yml
- filename: amazon-eks-add-ons-api-openapi.yml
  format: yaml
  label: Amazon EKS Add Ons API
  slug: amazon-eks-add-ons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-eks/openapi/amazon-eks-add-ons-api-openapi.yml
- filename: amazon-eks-access-entries-api-openapi.yml
  format: yaml
  label: Amazon EKS Eks Access Entries API
  slug: amazon-eks-access-entries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-eks/openapi/amazon-eks-access-entries-api-openapi.yml
- filename: amazon-eks-access-policies-api-openapi.yml
  format: yaml
  label: Amazon EKS Eks Access Policies API
  slug: amazon-eks-access-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-eks/openapi/amazon-eks-access-policies-api-openapi.yml
- filename: amazon-eks-capabilities-api-openapi.yml
  format: yaml
  label: Amazon EKS Eks Capabilities API
  slug: amazon-eks-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-eks/openapi/amazon-eks-capabilities-api-openapi.yml
- filename: amazon-eks-certificate-authorities-api-openapi.yml
  format: yaml
  label: Amazon EKS Eks Certificate Authorities API
  slug: amazon-eks-certificate-authorities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-eks/openapi/amazon-eks-certificate-authorities-api-openapi.yml
- filename: amazon-eks-eks-anywhere-subscriptions-api-openapi.yml
  format: yaml
  label: Amazon EKS Eks Eks Anywhere Subscriptions API
  slug: amazon-eks-eks-anywhere-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-eks/openapi/amazon-eks-eks-anywhere-subscriptions-api-openapi.yml
- filename: amazon-eks-identity-provider-configs-api-openapi.yml
  format: yaml
  label: Amazon EKS Eks Identity Provider Configs API
  slug: amazon-eks-identity-provider-configs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-eks/openapi/amazon-eks-identity-provider-configs-api-openapi.yml
- filename: amazon-eks-operations-api-openapi.yml
  format: yaml
  label: Amazon EKS Eks Operations API
  slug: amazon-eks-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-eks/openapi/amazon-eks-operations-api-openapi.yml
- filename: amazon-eks-pod-identity-associations-api-openapi.yml
  format: yaml
  label: Amazon EKS Eks Pod Identity Associations API
  slug: amazon-eks-pod-identity-associations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-eks/openapi/amazon-eks-pod-identity-associations-api-openapi.yml
- filename: amazon-eks-tags-api-openapi.yml
  format: yaml
  label: Amazon EKS Eks Tags API
  slug: amazon-eks-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-eks/openapi/amazon-eks-tags-api-openapi.yml
- filename: amazon-eks-updates-api-openapi.yml
  format: yaml
  label: Amazon EKS Eks Updates API
  slug: amazon-eks-updates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-eks/openapi/amazon-eks-updates-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: AWS services
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: certification support
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: AWS services
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: certification support
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: AWS services
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: certification support
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: AWS services
    text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP, GDPR, FIPS 140-3, and NIST 800-171
    type: compliance support
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
name: Amazon EKS
provenance_date: '2026-11-09'
provider_name: Amazon EKS
provider_slug: amazon-eks
slug: amazon-eks-compliance
source_date: '2026-11-09'
source_filename: amazon-eks-compliance.yml
source_heading: Compliance
source_page: https://aws.amazon.com/compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Amazon EKS\naid: amazon-eks\nurl: https://aws.amazon.com/compliance/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://aws.amazon.com/compliance/\nattestations:\n- framework: PCI-DSS\n  type: certification support\n  scope: AWS services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n- framework: HIPAA\n  type: certification support\n  scope: AWS services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports\
  \ 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n- framework: FedRAMP\n  type: certification support\n  scope: AWS services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n- framework: GDPR\n  type: compliance support\n  scope: AWS services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS supports 143 security standards and compliance certifications, including PCI-DSS, HIPAA/HITECH, FedRAMP,\n    GDPR, FIPS 140-3, and NIST 800-171\n"
source_yaml_url: https://artifacts.apis.io/amazon-eks/compliance/amazon-eks-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Amazon EKS's own page on 2026-11-09.
synthetic: false
tags:
- Amazon Web Services
- Container Orchestration
- Containers
- EKS
- Kubernetes
---
