---
api_specs:
- filename: rhel-advisories-api-openapi.yml
  format: yaml
  label: Red Hat Enterprise Linux Advisories API
  slug: rhel-advisories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rhel/openapi/rhel-advisories-api-openapi.yml
- filename: rhel-oval-api-openapi.yml
  format: yaml
  label: Red Hat Enterprise Linux OVAL API
  slug: rhel-oval-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rhel/openapi/rhel-oval-api-openapi.yml
- filename: rhel-subscriptions-api-openapi.yml
  format: yaml
  label: Red Hat Enterprise Linux Subscriptions API
  slug: rhel-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rhel/openapi/rhel-subscriptions-api-openapi.yml
- filename: rhel-systems-api-openapi.yml
  format: yaml
  label: Red Hat Enterprise Linux Systems API
  slug: rhel-systems-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rhel/openapi/rhel-systems-api-openapi.yml
- filename: rhel-cves-api-openapi.yml
  format: yaml
  label: Red Hat Enterprise Linux CV Es API
  slug: rhel-cves-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rhel/openapi/rhel-cves-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: products in Red Hat product compliance catalog
    text: FedRAMP Federal Risk and Authorization Management Program
    type: compliance listing
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: products in Red Hat product compliance catalog
    text: ISO 42001 provides requirements for an AI management system to ensure responsible development, deployment, and use of AI.
    type: compliance listing
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: products in Red Hat product compliance catalog
    text: HIPAA Health Insurance Portability and Accountability Act
    type: compliance listing
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: products in Red Hat product compliance catalog
    text: FIPS Federal Information Processing Standards
    type: compliance listing (FIPS)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: products in Red Hat product compliance catalog
    text: The Common Criteria for Information Security Evaluation is an international standard for computer security certification
    type: compliance listing (Common Criteria)
  trust_center:
    url: https://access.redhat.com/compliance
frameworks:
- FedRAMP
- HIPAA
- ISO42001
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Red Hat Enterprise Linux
provenance_date: '2026-11-10'
provider_name: Red Hat Enterprise Linux
provider_slug: rhel
slug: rhel-compliance
source_date: '2026-11-10'
source_filename: rhel-compliance.yml
source_heading: Compliance
source_page: https://access.redhat.com/compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Red Hat Enterprise Linux\naid: rhel\nurl: https://access.redhat.com/compliance\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/rhel-trust-center.yml\ntrust_center:\n  url: https://access.redhat.com/compliance\nattestations:\n- framework: FedRAMP\n  type: compliance listing\n  scope: products in Red Hat product compliance catalog\n  period: null\n  issuer: null\n  report_access: unstated\n  text: FedRAMP Federal Risk and Authorization Management Program\n- framework: ISO42001\n  type: compliance listing\n  scope: products in Red Hat product compliance catalog\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: ISO 42001 provides requirements for an AI management system to ensure responsible development, deployment,\n    and use of AI.\n- framework: HIPAA\n  type: compliance listing\n  scope: products in Red Hat product compliance catalog\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Health Insurance Portability and Accountability Act\n- framework: other\n  type: compliance listing (FIPS)\n  scope: products in Red Hat product compliance catalog\n  period: null\n  issuer: null\n  report_access: unstated\n  text: FIPS Federal Information Processing Standards\n- framework: other\n  type: compliance listing (Common Criteria)\n  scope: products in Red Hat product compliance catalog\n  period: null\n  issuer: null\n  report_access: unstated\n  text: The Common Criteria for Information Security Evaluation is an international standard for computer security\n    certification\n"
source_yaml_url: https://artifacts.apis.io/rhel/compliance/rhel-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Red Hat Enterprise Linux's own page on 2026-11-10.
synthetic: false
tags:
- Automation
- Compliance
- Enterprise
- Linux
- Operating System
- Red Hat
- RHEL
- Security
- Subscription Management
- Vulnerability Management
---
