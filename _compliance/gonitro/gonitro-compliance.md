---
api_specs:
- filename: gonitro-authentication-api-openapi.yml
  format: yaml
  label: GoNitro Authentication API
  slug: gonitro-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gonitro/openapi/gonitro-authentication-api-openapi.yml
- filename: gonitro-platform-api-openapi.yml
  format: yaml
  label: GoNitro Platform API
  slug: gonitro-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gonitro/openapi/gonitro-platform-api-openapi.yml
- filename: gonitro-sign-api-openapi.yml
  format: yaml
  label: GoNitro Sign API
  slug: gonitro-sign-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gonitro/openapi/gonitro-sign-api-openapi.yml
- filename: gonitro-webhooks-api-openapi.yml
  format: yaml
  label: GoNitro Webhooks API
  slug: gonitro-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gonitro/openapi/gonitro-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Nitro products and services
    text: Nitro is certified under ISO 27001, the leading international standard for information security management.
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: cloud services
    text: Nitro undergoes regular independent audits to maintain SOC 2 compliance, which evaluates the security, availability, processing integrity, confidentiality, and privacy of our cloud services.
    type: independent audit
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: protected health information
    text: Nitro complies with the Health Insurance Portability and Accountability Act (HIPAA)
    type: compliance
  - framework: other
    issuer: LSTI
    period: null
    report_access: unstated
    scope: Nitro Sign electronic trust services under eIDAS
    text: Nitro Software Belgium is accredited as a Qualified Trust Service Provider (QTSP) by LSTI.
    type: QTSP accreditation
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: cross-border data transfers (EU-U.S., UK and Swiss extensions)
    text: Nitro participates in the EU–U.S. Data Privacy Framework, including the U.K. and Swiss extensions.
    type: Data Privacy Framework certification
  trust_center:
    url: https://www.gonitro.com/security-compliance/compliance
frameworks:
- HIPAA
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: GoNitro
provenance_date: '2026-11-09'
provider_name: GoNitro
provider_slug: gonitro
slug: gonitro-compliance
source_date: '2026-11-09'
source_filename: gonitro-compliance.yml
source_heading: Compliance
source_page: https://www.gonitro.com/security-compliance/compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: GoNitro\naid: gonitro\nurl: https://www.gonitro.com/security-compliance/compliance\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.gonitro.com/security-compliance/compliance\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Nitro products and services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Nitro is certified under ISO 27001, the leading international standard for information security management.\n- framework: SOC2\n  type: independent audit\n  scope: cloud services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Nitro undergoes\
  \ regular independent audits to maintain SOC 2 compliance, which evaluates the security, availability,\n    processing integrity, confidentiality, and privacy of our cloud services.\n- framework: HIPAA\n  type: compliance\n  scope: protected health information\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Nitro complies with the Health Insurance Portability and Accountability Act (HIPAA)\n- framework: other\n  type: QTSP accreditation\n  scope: Nitro Sign electronic trust services under eIDAS\n  period: null\n  issuer: LSTI\n  report_access: unstated\n  text: Nitro Software Belgium is accredited as a Qualified Trust Service Provider (QTSP) by LSTI.\n- framework: other\n  type: Data Privacy Framework certification\n  scope: cross-border data transfers (EU-U.S., UK and Swiss extensions)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Nitro participates in the EU–U.S. Data Privacy Framework, including the U.K. and Swiss extensions.\n"
source_yaml_url: https://artifacts.apis.io/gonitro/compliance/gonitro-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from GoNitro's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Documents
- PDF
- E-Signature
- Document Automation
- Document Conversion
- Data Extraction
- Redaction
- OCR
- Productivity
- Compliance
---
