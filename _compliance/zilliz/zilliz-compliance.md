---
api_specs:
- filename: zilliz-cloud-providers-api-openapi.yml
  format: yaml
  label: Zilliz Cloud Providers API
  slug: zilliz-cloud-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zilliz/openapi/zilliz-cloud-providers-api-openapi.yml
- filename: zilliz-clusters-api-openapi.yml
  format: yaml
  label: Zilliz Clusters API
  slug: zilliz-clusters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zilliz/openapi/zilliz-clusters-api-openapi.yml
- filename: zilliz-collections-api-openapi.yml
  format: yaml
  label: Zilliz Collections API
  slug: zilliz-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zilliz/openapi/zilliz-collections-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II Security and organizational controls for cloud providers.
    type: SOC 2 Type II
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO/IEC 27001 Global standard for information security management systems.
    type: ISO/IEC 27001
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Privacy protections for EU and EEA data.
    type: null
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA U.S privacy regulation safeguarding health information.
    type: null
  trust_center:
    url: https://zilliz.com/trust-center
frameworks:
- GDPR
- HIPAA
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Zilliz
provenance_date: '2026-11-10'
provider_name: Zilliz
provider_slug: zilliz
slug: zilliz-compliance
source_date: '2026-11-10'
source_filename: zilliz-compliance.yml
source_heading: Compliance
source_page: https://zilliz.com/trust-center
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Zilliz\naid: zilliz\nurl: https://zilliz.com/trust-center\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/zilliz-trust-center.yml\ntrust_center:\n  url: https://zilliz.com/trust-center\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II Security and organizational controls for cloud providers.\n- framework: ISO27001\n  type: ISO/IEC 27001\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 27001 Global standard for information security management systems.\n- framework:\
  \ GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Privacy protections for EU and EEA data.\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA U.S privacy regulation safeguarding health information.\n"
source_yaml_url: https://artifacts.apis.io/zilliz/compliance/zilliz-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Zilliz's own page on 2026-11-10.
synthetic: false
tags:
- Vector Search
- Artificial Intelligence
- Cloud
- Milvus
- Managed
---
