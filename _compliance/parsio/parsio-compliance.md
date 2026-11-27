---
api_specs:
- filename: parsio-documents-api-openapi.yml
  format: yaml
  label: Parsio Documents API
  slug: parsio-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parsio/openapi/parsio-documents-api-openapi.yml
- filename: parsio-mailboxes-api-openapi.yml
  format: yaml
  label: Parsio Mailboxes API
  slug: parsio-mailboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parsio/openapi/parsio-mailboxes-api-openapi.yml
- filename: parsio-templates-api-openapi.yml
  format: yaml
  label: Parsio Templates API
  slug: parsio-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parsio/openapi/parsio-templates-api-openapi.yml
- filename: parsio-webhooks-api-openapi.yml
  format: yaml
  label: Parsio Webhooks API
  slug: parsio-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parsio/openapi/parsio-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Parsio parsing services
    text: Parsio aligns with GDPR requirements.
    type: self-stated alignment
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Infrastructure providers (Hetzner data centers in Falkenstein and Nuremberg)
    text: Infrastructure providers hold ISO/IEC 27001 certification
    type: infrastructure provider certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Infrastructure providers
    text: Our infrastructure providers maintain widely recognized certifications (for example, ISO 27001 and SOC 2)
    type: infrastructure provider certification
  trust_center:
    url: https://parsio.io/security/
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Parsio
provenance_date: '2026-11-10'
provider_name: Parsio
provider_slug: parsio
slug: parsio-compliance
source_date: '2026-11-10'
source_filename: parsio-compliance.yml
source_heading: Compliance
source_page: https://parsio.io/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Parsio\naid: parsio\nurl: https://parsio.io/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/parsio-trust-center.yml\ntrust_center:\n  url: https://parsio.io/security/\nattestations:\n- framework: GDPR\n  type: self-stated alignment\n  scope: Parsio parsing services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Parsio aligns with GDPR requirements.\n- framework: ISO27001\n  type: infrastructure provider certification\n  scope: Infrastructure providers (Hetzner data centers in Falkenstein and Nuremberg)\n  period: null\n  issuer: null\n  report_access: unstated\n  text:\
  \ Infrastructure providers hold ISO/IEC 27001 certification\n- framework: SOC2\n  type: infrastructure provider certification\n  scope: Infrastructure providers\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our infrastructure providers maintain widely recognized certifications (for example, ISO 27001 and SOC 2)\n"
source_yaml_url: https://artifacts.apis.io/parsio/compliance/parsio-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Parsio's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Document Parsing
- Email Parsing
- OCR
- Data Extraction
---
