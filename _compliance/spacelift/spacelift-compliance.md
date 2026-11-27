---
api_specs:
- filename: spacelift-graph-ql-api-openapi.yml
  format: yaml
  label: Spacelift Graph QL API
  slug: spacelift-graph-ql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spacelift/openapi/spacelift-graph-ql-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent external auditor
    period: null
    report_access: unstated
    scope: security, availability, processing integrity, confidentiality, and privacy of customer data
    text: SOC2 Type II certification performed by an independent external auditor confirms the effectiveness of internal controls in terms of Spacelift security, availability, processing integrity, confidentiality, and privacy of customer data.
    type: SOC2 Type II certification
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Spacelift is the first infrastructure-as-code (IaC) orchestration platform to receive FedRAMP authorization
    type: FedRAMP authorization
  trust_center:
    url: https://spacelift.io/security
frameworks:
- FedRAMP
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Spacelift
provenance_date: '2026-11-10'
provider_name: Spacelift
provider_slug: spacelift
slug: spacelift-compliance
source_date: '2026-11-10'
source_filename: spacelift-compliance.yml
source_heading: Compliance
source_page: https://spacelift.io/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Spacelift\naid: spacelift\nurl: https://spacelift.io/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/spacelift-trust-center.yml\ntrust_center:\n  url: https://spacelift.io/security\nattestations:\n- framework: SOC2\n  type: SOC2 Type II certification\n  scope: security, availability, processing integrity, confidentiality, and privacy of customer data\n  period: null\n  issuer: independent external auditor\n  report_access: unstated\n  text: SOC2 Type II certification performed by an independent external auditor confirms the effectiveness of internal\n    controls in terms of Spacelift security,\
  \ availability, processing integrity, confidentiality, and privacy of\n    customer data.\n- framework: FedRAMP\n  type: FedRAMP authorization\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Spacelift is the first infrastructure-as-code (IaC) orchestration platform to receive FedRAMP authorization\n"
source_yaml_url: https://artifacts.apis.io/spacelift/compliance/spacelift-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Spacelift's own page on 2026-11-10.
synthetic: false
tags:
- Infrastructure as Code
- FinOps
- DevOps
- Platform Engineering
- Terraform
- GitOps
---
