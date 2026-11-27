---
api_specs:
- filename: getdynamiq-api-reference-openapi-generated.yml
  format: yaml
  label: Dynamiq API Reference API
  slug: api-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getdynamiq/openapi/_ae-authored/getdynamiq-api-reference-openapi-generated.yml
- filename: getdynamiq-platform-openapi-generated.yml
  format: yaml
  label: Dynamiq Platform API
  slug: platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getdynamiq/openapi/_ae-authored/getdynamiq-platform-openapi-generated.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: security controls
    text: The report is available on request under NDA.
    type: independent audit of security controls
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: HIPAA workloads
    text: We sign a Business Associate Agreement (BAA) with covered entities.
    type: Business Associate Agreement
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data processing
    text: A Data Processing Agreement (DPA) is available, and our sub-processors are listed publicly.
    type: Data Processing Agreement
  - framework: other
    issuer: App Defense Alliance
    period: null
    report_access: unstated
    scope: cloud application
    text: Our cloud application passed the App Defense Alliance's Cloud Application Security Assessment at Tier 2, a lab-verified review against the OWASP Application Security Verification Standard.
    type: Cloud Application Security Assessment (CASA) Tier 2
  trust_center:
    url: https://www.getdynamiq.ai/security
frameworks:
- GDPR
- HIPAA
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Dynamiq
provenance_date: '2026-11-09'
provider_name: Dynamiq
provider_slug: getdynamiq
slug: getdynamiq-compliance
source_date: '2026-11-09'
source_filename: getdynamiq-compliance.yml
source_heading: Compliance
source_page: https://www.getdynamiq.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Dynamiq\naid: getdynamiq\nurl: https://www.getdynamiq.ai/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.getdynamiq.ai/security\nattestations:\n- framework: SOC2\n  type: independent audit of security controls\n  scope: security controls\n  period: null\n  issuer: null\n  report_access: nda\n  text: The report is available on request under NDA.\n- framework: HIPAA\n  type: Business Associate Agreement\n  scope: HIPAA workloads\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We sign a Business Associate Agreement (BAA) with covered entities.\n- framework: GDPR\n  type:\
  \ Data Processing Agreement\n  scope: personal data processing\n  period: null\n  issuer: null\n  report_access: unstated\n  text: A Data Processing Agreement (DPA) is available, and our sub-processors are listed publicly.\n- framework: other\n  type: Cloud Application Security Assessment (CASA) Tier 2\n  scope: cloud application\n  period: null\n  issuer: App Defense Alliance\n  report_access: unstated\n  text: Our cloud application passed the App Defense Alliance's Cloud Application Security Assessment at Tier 2,\n    a lab-verified review against the OWASP Application Security Verification Standard.\n"
source_yaml_url: https://artifacts.apis.io/getdynamiq/compliance/getdynamiq-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Dynamiq's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Enterprise
- Platform
- Agents
---
