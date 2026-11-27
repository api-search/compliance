---
api_specs:
- filename: mailerlite-webhook-api-openapi.yml
  format: yaml
  label: MailerLite Webhook API
  slug: mailerlite-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailerlite/openapi/mailerlite-webhook-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: Bureau Veritas
    period: null
    report_access: unstated
    scope: Information Security Management System (ISMS)
    text: MailerLite is certified to ISO/IEC 27001:2022 , the leading standard for Information Security Management Systems (ISMS).
    type: certification
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: payment processing vendors
    text: Our payment processing vendors are Payment Card Industry Data Security Standard (PCI-DSS) compliant.
    type: compliance of payment vendors
  - framework: other
    issuer: U.S. Department of Commerce
    period: null
    report_access: unstated
    scope: EU-U.S. and Swiss-U.S. Data Privacy Frameworks
    text: MailerLite, Inc. complies with the EU-U.S. and Swiss-U.S. Data Privacy Frameworks (DPF), including the UK Extension to the EU-U.S. DPF.
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data processing controls
    text: We have incorporated all the necessary controls and procedures for personal data processing security derived from the GDPR into our systems.
    type: compliance claim
  trust_center:
    url: https://www.mailerlite.com/trust-page
frameworks:
- GDPR
- ISO27001
- PCI-DSS
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: MailerLite
provenance_date: '2026-11-10'
provider_name: MailerLite
provider_slug: mailerlite
slug: mailerlite-compliance
source_date: '2026-11-10'
source_filename: mailerlite-compliance.yml
source_heading: Compliance
source_page: https://www.mailerlite.com/trust-page
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: MailerLite\naid: mailerlite\nurl: https://www.mailerlite.com/trust-page\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.mailerlite.com/trust-page\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Information Security Management System (ISMS)\n  period: null\n  issuer: Bureau Veritas\n  report_access: unstated\n  text: MailerLite is certified to ISO/IEC 27001:2022 , the leading standard for Information Security Management\n    Systems (ISMS).\n- framework: PCI-DSS\n  type: compliance of payment vendors\n  scope: payment processing vendors\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: Our payment processing vendors are Payment Card Industry Data Security Standard (PCI-DSS) compliant.\n- framework: other\n  type: certification\n  scope: EU-U.S. and Swiss-U.S. Data Privacy Frameworks\n  period: null\n  issuer: U.S. Department of Commerce\n  report_access: unstated\n  text: MailerLite, Inc. complies with the EU-U.S. and Swiss-U.S. Data Privacy Frameworks (DPF), including the UK\n    Extension to the EU-U.S. DPF.\n- framework: GDPR\n  type: compliance claim\n  scope: personal data processing controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We have incorporated all the necessary controls and procedures for personal data processing security derived\n    from the GDPR into our systems.\n"
source_yaml_url: https://artifacts.apis.io/mailerlite/compliance/mailerlite-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from MailerLite's own page on 2026-11-10.
synthetic: false
tags:
- Email Marketing
- Automation
- Newsletters
- Subscribers
- Campaigns
- Webhook
- E-Commerce
- Segmentation
- Transactional Email
- MCP
- Email
---
