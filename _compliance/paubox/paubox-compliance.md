---
api_specs:
- filename: paubox-analytics-api-openapi.yml
  format: yaml
  label: Paubox Analytics API
  slug: paubox-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-analytics-api-openapi.yml
- filename: paubox-campaign-mailings-api-openapi.yml
  format: yaml
  label: Paubox Campaign Mailings API
  slug: paubox-campaign-mailings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-campaign-mailings-api-openapi.yml
- filename: paubox-drip-campaigns-api-openapi.yml
  format: yaml
  label: Paubox Drip Campaigns API
  slug: paubox-drip-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-drip-campaigns-api-openapi.yml
- filename: paubox-dynamic-templates-api-openapi.yml
  format: yaml
  label: Paubox Dynamic Templates API
  slug: paubox-dynamic-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-dynamic-templates-api-openapi.yml
- filename: paubox-form-management-api-openapi.yml
  format: yaml
  label: Paubox Form management API
  slug: paubox-form-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-form-management-api-openapi.yml
- filename: paubox-forms-api-openapi.yml
  format: yaml
  label: Paubox Forms API
  slug: paubox-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-forms-api-openapi.yml
- filename: paubox-messages-api-openapi.yml
  format: yaml
  label: Paubox Messages API
  slug: paubox-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-messages-api-openapi.yml
- filename: paubox-submissions-api-openapi.yml
  format: yaml
  label: Paubox Submissions API
  slug: paubox-submissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-submissions-api-openapi.yml
- filename: paubox-subscribers-api-openapi.yml
  format: yaml
  label: Paubox Subscribers API
  slug: paubox-subscribers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-subscribers-api-openapi.yml
- filename: paubox-subscription-lists-api-openapi.yml
  format: yaml
  label: Paubox Subscription Lists API
  slug: paubox-subscription-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-subscription-lists-api-openapi.yml
- filename: paubox-subscriptions-api-openapi.yml
  format: yaml
  label: Paubox Subscriptions API
  slug: paubox-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-subscriptions-api-openapi.yml
- filename: paubox-tracking-links-api-openapi.yml
  format: yaml
  label: Paubox Tracking Links API
  slug: paubox-tracking-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-tracking-links-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Encrypted Email, Secure Email API, Email DLP Suite and Inbound Security solutions
    text: HITRUST CSF Certified status demonstrates that our Encrypted Email, Secure Email API, Email DLP Suite and Inbound Security solutions have met key regulatory requirements and industry-defined requirements and is appropriately managing risk.
    type: HITRUST CSF Certified
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: AWS platform used by Paubox
    text: the AWS platform provides industry recognized certifications and audits such as ISO 27001 , FedRAMP , and the Service Organization Control Reports (SOC1, SOC2, and SOC3)
    type: certification referenced for AWS platform
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: AWS platform used by Paubox
    text: the Service Organization Control Reports (SOC1, SOC2, and SOC3)
    type: Service Organization Control report referenced for AWS platform
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: AWS platform used by Paubox
    text: The AWS platform also meets the requirements set forth by GDPR
    type: stated compliance for AWS platform
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: AWS platform used by Paubox
    text: adherence and compliance with the CISPE Code of Conduct as a mechanism for demonstrating sufficient guarantees of requirements that GDPR places on data processors
    type: CISPE Code of Conduct adherence
  trust_center:
    url: https://www.paubox.com/security
frameworks:
- GDPR
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Paubox
provenance_date: '2026-11-10'
provider_name: Paubox
provider_slug: paubox
slug: paubox-compliance
source_date: '2026-11-10'
source_filename: paubox-compliance.yml
source_heading: Compliance
source_page: https://www.paubox.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Paubox\naid: paubox\nurl: https://www.paubox.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.paubox.com/security\nattestations:\n- framework: other\n  type: HITRUST CSF Certified\n  scope: Encrypted Email, Secure Email API, Email DLP Suite and Inbound Security solutions\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HITRUST CSF Certified status demonstrates that our Encrypted Email, Secure Email API, Email DLP Suite and\n    Inbound Security solutions have met key regulatory requirements and industry-defined requirements and is appropriately\n    managing risk.\n\
  - framework: ISO27001\n  type: certification referenced for AWS platform\n  scope: AWS platform used by Paubox\n  period: null\n  issuer: null\n  report_access: unstated\n  text: the AWS platform provides industry recognized certifications and audits such as ISO 27001 , FedRAMP , and\n    the Service Organization Control Reports (SOC1, SOC2, and SOC3)\n- framework: SOC2\n  type: Service Organization Control report referenced for AWS platform\n  scope: AWS platform used by Paubox\n  period: null\n  issuer: null\n  report_access: unstated\n  text: the Service Organization Control Reports (SOC1, SOC2, and SOC3)\n- framework: GDPR\n  type: stated compliance for AWS platform\n  scope: AWS platform used by Paubox\n  period: null\n  issuer: null\n  report_access: unstated\n  text: The AWS platform also meets the requirements set forth by GDPR\n- framework: other\n  type: CISPE Code of Conduct adherence\n  scope: AWS platform used by Paubox\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: adherence and compliance with the CISPE Code of Conduct as a mechanism for demonstrating sufficient guarantees\n    of requirements that GDPR places on data processors\n"
source_yaml_url: https://artifacts.apis.io/paubox/compliance/paubox-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Paubox's own page on 2026-11-10.
synthetic: false
tags:
- Email
- HIPAA
- Healthcare
- Compliance
- Transactional Email
- Email Marketing
- Forms
- Security
- Encryption
- Messaging
- A2A
---
