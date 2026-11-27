---
api_specs:
- filename: regal-reporting-webhooks-asyncapi.yml
  format: yaml
  label: Regal Reporting Webhooks
  slug: regal-reporting-webhooks
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/regal-ai/asyncapi/regal-reporting-webhooks-asyncapi.yml
- filename: regal-ai-campaigns-api-openapi.yml
  format: yaml
  label: Regal Campaigns API
  slug: regal-ai-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regal-ai/openapi/regal-ai-campaigns-api-openapi.yml
- filename: regal-ai-dispositions-api-openapi.yml
  format: yaml
  label: Regal Dispositions API
  slug: regal-ai-dispositions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regal-ai/openapi/regal-ai-dispositions-api-openapi.yml
- filename: regal-ai-events-api-openapi.yml
  format: yaml
  label: Regal Events API
  slug: regal-ai-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regal-ai/openapi/regal-ai-events-api-openapi.yml
- filename: regal-ai-messages-api-openapi.yml
  format: yaml
  label: Regal Messages API
  slug: regal-ai-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regal-ai/openapi/regal-ai-messages-api-openapi.yml
- filename: regal-ai-users-api-openapi.yml
  format: yaml
  label: Regal Users API
  slug: regal-ai-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regal-ai/openapi/regal-ai-users-api-openapi.yml
- filename: regal-ai-activephonenumbers-api-openapi.yml
  format: yaml
  label: Regal Active Phone Numbers API
  slug: regal-ai-activephonenumbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regal-ai/openapi/regal-ai-activephonenumbers-api-openapi.yml
- filename: regal-ai-brandedphonenumbers-api-openapi.yml
  format: yaml
  label: Regal Branded Phone Numbers API
  slug: regal-ai-brandedphonenumbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regal-ai/openapi/regal-ai-brandedphonenumbers-api-openapi.yml
- filename: regal-ai-businessprofiles-api-openapi.yml
  format: yaml
  label: Regal Business Profiles API
  slug: regal-ai-businessprofiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regal-ai/openapi/regal-ai-businessprofiles-api-openapi.yml
- filename: regal-ai-callhandoffs-api-openapi.yml
  format: yaml
  label: Regal Call Handoffs API
  slug: regal-ai-callhandoffs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regal-ai/openapi/regal-ai-callhandoffs-api-openapi.yml
claim_count: 8
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: null
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II
    type: Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: null
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA COMPLIANT
    type: null
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI DSS - SAQ D, SP and ROC Prep
    type: SAQ D, SP and ROC Prep
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://www.regal.ai/security
    text: including SOC2 certification
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://www.regal.ai/security
    text: we adhere to relevant standards including GDPR and CCPA
    type: standard adherence
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://www.regal.ai/security
    text: we adhere to relevant standards including GDPR and CCPA
    type: standard adherence
  trust_center:
    url: https://trust.regal.ai/
frameworks:
- CCPA
- GDPR
- HIPAA
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Regal
provenance_date: '2026-11-10'
provider_name: Regal
provider_slug: regal-ai
slug: regal-ai-compliance
source_date: '2026-11-10'
source_filename: regal-ai-compliance.yml
source_heading: Compliance
source_page: https://trust.regal.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Regal\naid: regal-ai\nurl: https://trust.regal.ai/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://trust.regal.ai/\n  - https://www.regal.ai/security\ntrust_center:\n  url: https://trust.regal.ai/\nattestations:\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: CCPA\n  type:\
  \ null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA COMPLIANT\n- framework: PCI-DSS\n  type: SAQ D, SP and ROC Prep\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS - SAQ D, SP and ROC Prep\n- framework: SOC2\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: including SOC2 certification\n  source: https://www.regal.ai/security\n- framework: GDPR\n  type: standard adherence\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: we adhere to relevant standards including GDPR and CCPA\n  source: https://www.regal.ai/security\n- framework: CCPA\n  type: standard adherence\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: we adhere to relevant standards including GDPR and CCPA\n  source: https://www.regal.ai/security\n"
source_yaml_url: https://artifacts.apis.io/regal-ai/compliance/regal-ai-compliance.yml
stated_fields:
- attestations
summary_line: 8 quoted statements, read from Regal's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- AI Agents
- Voice AI
- Contact Center
- Outbound Calling
- Inbound Calling
- Phone Agents
- SMS
- Chat
- WebRTC
- Conversation Intelligence
- Journey Orchestration
- Branded Caller ID
- CCaaS
- CPaaS
- Sales Dialer
- Customer Engagement
---
