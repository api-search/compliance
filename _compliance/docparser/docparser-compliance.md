---
api_specs:
- filename: docparser-documents-api-openapi.yml
  format: yaml
  label: Docparser Documents API
  slug: docparser-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docparser/openapi/docparser-documents-api-openapi.yml
- filename: docparser-parsers-api-openapi.yml
  format: yaml
  label: Docparser Parsers API
  slug: docparser-parsers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docparser/openapi/docparser-parsers-api-openapi.yml
- filename: docparser-ping-api-openapi.yml
  format: yaml
  label: Docparser Ping API
  slug: docparser-ping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docparser/openapi/docparser-ping-api-openapi.yml
- filename: docparser-results-api-openapi.yml
  format: yaml
  label: Docparser Results API
  slug: docparser-results-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docparser/openapi/docparser-results-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Docparser service for EU-based companies
    text: We are GDPR compliant and leverage Standard Contractual Clauses as our legal basis of transfer.
    type: self-stated compliance
  trust_center:
    url: https://docparser.com/security
frameworks:
- GDPR
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Docparser
provenance_date: '2026-11-09'
provider_name: Docparser
provider_slug: docparser
slug: docparser-compliance
source_date: '2026-11-09'
source_filename: docparser-compliance.yml
source_heading: Compliance
source_page: https://docparser.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Docparser\naid: docparser\nurl: https://docparser.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/docparser-trust-center.yml\ntrust_center:\n  url: https://docparser.com/security\nattestations:\n- framework: GDPR\n  type: self-stated compliance\n  scope: Docparser service for EU-based companies\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are GDPR compliant and leverage Standard Contractual Clauses as our legal basis of transfer.\n"
source_yaml_url: https://artifacts.apis.io/docparser/compliance/docparser-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Docparser's own page on 2026-11-09.
synthetic: false
tags:
- Document Parsing
- Data Extraction
- PDF
- OCR
- Document Automation
- Invoices
- Contracts
- REST API
---
