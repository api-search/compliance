---
api_specs:
- filename: docuseal-submissions-api-openapi.yml
  format: yaml
  label: DocuSeal Submissions API
  slug: docuseal-submissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docuseal/openapi/docuseal-submissions-api-openapi.yml
- filename: docuseal-submitters-api-openapi.yml
  format: yaml
  label: DocuSeal Submitters API
  slug: docuseal-submitters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docuseal/openapi/docuseal-submitters-api-openapi.yml
- filename: docuseal-templates-api-openapi.yml
  format: yaml
  label: DocuSeal Templates API
  slug: docuseal-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docuseal/openapi/docuseal-templates-api-openapi.yml
claim_count: 9
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Compliant
    type: compliance statement
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA Compliant
    type: compliance statement
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliant
    type: compliance statement
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001 Compliant
    type: compliance statement
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ESIGN & UETA Compliant
    type: compliance statement
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: eIDAS Compliant
    type: compliance statement
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: 21 CFR Part 11 Compliant
    type: compliance statement
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CPRA (formerly CCPA) Compliant
    type: compliance statement
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: KBA Compliant
    type: compliance statement
  trust_center:
    url: https://trust.docuseal.com/
frameworks:
- CCPA
- GDPR
- HIPAA
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: DocuSeal
provenance_date: '2026-11-09'
provider_name: DocuSeal
provider_slug: docuseal
slug: docuseal-compliance
source_date: '2026-11-09'
source_filename: docuseal-compliance.yml
source_heading: Compliance
source_page: https://trust.docuseal.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: DocuSeal\naid: docuseal\nurl: https://trust.docuseal.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/docuseal-trust-center.yml\ntrust_center:\n  url: https://trust.docuseal.com/\nattestations:\n- framework: SOC2\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Compliant\n- framework: HIPAA\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Compliant\n- framework: GDPR\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: GDPR Compliant\n- framework: ISO27001\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 Compliant\n- framework: other\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ESIGN & UETA Compliant\n- framework: other\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: eIDAS Compliant\n- framework: other\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 21 CFR Part 11 Compliant\n- framework: CCPA\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CPRA (formerly CCPA) Compliant\n- framework: other\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: KBA Compliant\n"
source_yaml_url: https://artifacts.apis.io/docuseal/compliance/docuseal-compliance.yml
stated_fields:
- attestations
summary_line: 9 quoted statements, read from DocuSeal's own page on 2026-11-09.
synthetic: false
tags:
- E-Signature
- Document Management
- PDF
- Templates
- Open Source
- Webhook
- Embeddings
---
