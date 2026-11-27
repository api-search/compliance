---
api_specs:
- filename: zluri-data-upload-api-openapi.yml
  format: yaml
  label: Zluri Data Upload API
  slug: zluri-data-upload-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zluri/openapi/zluri-data-upload-api-openapi.yml
- filename: zluri-instances-api-openapi.yml
  format: yaml
  label: Zluri Instances API
  slug: zluri-instances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zluri/openapi/zluri-instances-api-openapi.yml
- filename: zluri-syncs-api-openapi.yml
  format: yaml
  label: Zluri Syncs API
  slug: zluri-syncs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zluri/openapi/zluri-syncs-api-openapi.yml
- filename: zluri-webhooks-api-openapi.yml
  format: yaml
  label: Zluri Webhooks API
  slug: zluri-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zluri/openapi/zluri-webhooks-api-openapi.yml
claim_count: 11
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022 3 documents
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliance GDPR 2 documents
    type: null
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliance ISO 27701:2019 2 documents
    type: null
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliance PCI DSS V4.0 2 documents
    type: null
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliance SOC 2 2 documents
    type: null
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: NIST SP 800-171 Revision 3
    text: Compliance NIST SP 800-171 REVI... 1 document
    type: null
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://www.zluri.com/security
    text: Zluri complies with GDPR, NIST, SOC 2 Type II, PCI-DSS, ISO/IEC 27001, and ISO 27701.
    type: SOC 2 Type II
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://www.zluri.com/security
    text: Zluri complies with GDPR, NIST, SOC 2 Type II, PCI-DSS, ISO/IEC 27001, and ISO 27701.
    type: ISO/IEC 27001
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://www.zluri.com/security
    text: Zluri complies with GDPR, NIST, SOC 2 Type II, PCI-DSS, ISO/IEC 27001, and ISO 27701.
    type: ISO 27701
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://www.zluri.com/security
    text: Zluri complies with GDPR, NIST, SOC 2 Type II, PCI-DSS, ISO/IEC 27001, and ISO 27701.
    type: PCI-DSS
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://www.zluri.com/security
    text: Zluri complies with GDPR, NIST, SOC 2 Type II, PCI-DSS, ISO/IEC 27001, and ISO 27701.
    type: GDPR
  trust_center:
    url: https://trust.zluri.com/
frameworks:
- GDPR
- ISO27001
- ISO27701
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Zluri
provenance_date: '2026-11-10'
provider_name: Zluri
provider_slug: zluri
slug: zluri-compliance
source_date: '2026-11-10'
source_filename: zluri-compliance.yml
source_heading: Compliance
source_page: https://trust.zluri.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Zluri\naid: zluri\nurl: https://trust.zluri.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/zluri-trust-center.yml\n  sources:\n  - https://trust.zluri.com/\n  - https://www.zluri.com/security\ntrust_center:\n  url: https://trust.zluri.com/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022 3 documents\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance GDPR 2 documents\n- framework: ISO27701\n  type: null\n  scope:\
  \ null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance ISO 27701:2019 2 documents\n- framework: PCI-DSS\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance PCI DSS V4.0 2 documents\n- framework: SOC2\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance SOC 2 2 documents\n- framework: other\n  type: null\n  scope: NIST SP 800-171 Revision 3\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance NIST SP 800-171 REVI... 1 document\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Zluri complies with GDPR, NIST, SOC 2 Type II, PCI-DSS, ISO/IEC 27001, and ISO 27701.\n  source: https://www.zluri.com/security\n- framework: ISO27001\n  type: ISO/IEC 27001\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Zluri complies with\
  \ GDPR, NIST, SOC 2 Type II, PCI-DSS, ISO/IEC 27001, and ISO 27701.\n  source: https://www.zluri.com/security\n- framework: ISO27701\n  type: ISO 27701\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Zluri complies with GDPR, NIST, SOC 2 Type II, PCI-DSS, ISO/IEC 27001, and ISO 27701.\n  source: https://www.zluri.com/security\n- framework: PCI-DSS\n  type: PCI-DSS\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Zluri complies with GDPR, NIST, SOC 2 Type II, PCI-DSS, ISO/IEC 27001, and ISO 27701.\n  source: https://www.zluri.com/security\n- framework: GDPR\n  type: GDPR\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Zluri complies with GDPR, NIST, SOC 2 Type II, PCI-DSS, ISO/IEC 27001, and ISO 27701.\n  source: https://www.zluri.com/security\n"
source_yaml_url: https://artifacts.apis.io/zluri/compliance/zluri-compliance.yml
stated_fields:
- attestations
summary_line: 11 quoted statements, read from Zluri's own page on 2026-11-10.
synthetic: false
tags:
- Identity and Access Management
- SaaS Management
---
