---
api_specs:
- filename: databook-batch-create-api-openapi.yml
  format: yaml
  label: Databook batch - create API
  slug: databook-batch-create-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/databook/openapi/databook-batch-create-api-openapi.yml
- filename: databook-batch-query-api-openapi.yml
  format: yaml
  label: Databook batch - query API
  slug: databook-batch-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/databook/openapi/databook-batch-query-api-openapi.yml
- filename: databook-chat-api-openapi.yml
  format: yaml
  label: Databook Chat API
  slug: databook-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/databook/openapi/databook-chat-api-openapi.yml
- filename: databook-reasoning-api-openapi.yml
  format: yaml
  label: Databook Reasoning API
  slug: databook-reasoning-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/databook/openapi/databook-reasoning-api-openapi.yml
- filename: databook-asset-studio-api-openapi.yml
  format: yaml
  label: Databook Asset Studio API
  slug: databook-asset-studio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/databook/openapi/databook-asset-studio-api-openapi.yml
claim_count: 10
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: Databook maintains SOC 2 Type II attestation, supports GDPR and CCPA obligations, and aligns to NIST CSF and ISO 27001 control families.
    type: Type II attestation
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: supports GDPR and CCPA obligations
    type: obligations support
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: supports GDPR and CCPA obligations
    type: obligations support
  - framework: NIST-CSF
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: aligns to NIST CSF and ISO 27001 control families
    type: control family alignment
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: aligns to NIST CSF and ISO 27001 control families
    type: control family alignment
  - framework: SOC2
    issuer: independent third-party auditor
    period: null
    report_access: on_request
    scope: application and API
    source: https://trust.databook.com/
    text: Databook is SOC 2 Type 2 certified
    type: Type 2
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.databook.com/
    text: GDPR
    type: null
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.databook.com/
    text: CCPA COMPLIANT
    type: null
  - framework: NIST-CSF
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.databook.com/
    text: NIST Cybersecurity Framework
    type: null
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.databook.com/
    text: Microsoft Supplier Security & Privacy Assurance Program
    type: Microsoft Supplier Security & Privacy Assurance Program
  trust_center:
    url: https://databook.com/security
frameworks:
- CCPA
- GDPR
- ISO27001
- NIST-CSF
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Databook
provenance_date: '2026-11-09'
provider_name: Databook
provider_slug: databook
slug: databook-compliance
source_date: '2026-11-09'
source_filename: databook-compliance.yml
source_heading: Compliance
source_page: https://databook.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Databook\naid: databook\nurl: https://databook.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://databook.com/security\n  - https://trust.databook.com/\ntrust_center:\n  url: https://databook.com/security\nattestations:\n- framework: SOC2\n  type: Type II attestation\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: Databook maintains SOC 2 Type II attestation, supports GDPR and CCPA obligations, and aligns to NIST CSF\n    and ISO 27001 control families.\n- framework: GDPR\n  type: obligations support\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: supports GDPR and CCPA obligations\n- framework: CCPA\n  type: obligations support\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: supports GDPR and CCPA obligations\n- framework: NIST-CSF\n  type: control family alignment\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: aligns to NIST CSF and ISO 27001 control families\n- framework: ISO27001\n  type: control family alignment\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: aligns to NIST CSF and ISO 27001 control families\n- framework: SOC2\n  type: Type 2\n  scope: application and API\n  period: null\n  issuer: independent third-party auditor\n  report_access: on_request\n  text: Databook is SOC 2 Type 2 certified\n  source: https://trust.databook.com/\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n  source: https://trust.databook.com/\n- framework:\
  \ CCPA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA COMPLIANT\n  source: https://trust.databook.com/\n- framework: NIST-CSF\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: NIST Cybersecurity Framework\n  source: https://trust.databook.com/\n- framework: other\n  type: Microsoft Supplier Security & Privacy Assurance Program\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Microsoft Supplier Security & Privacy Assurance Program\n  source: https://trust.databook.com/\n"
source_yaml_url: https://artifacts.apis.io/databook/compliance/databook-compliance.yml
stated_fields:
- attestations
summary_line: 10 quoted statements, read from Databook's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Vertical Software
- Sales Intelligence
- Account Intelligence
- Sales Enablement
- Enterprise Sales
- Artificial Intelligence
- Revenue Operations
- REST API
- OpenAPI
- Batch Processing
- Agents
- Reasoning
- Company Data
- Data Platform
- Business Intelligence
---
