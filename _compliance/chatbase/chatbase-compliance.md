---
api_specs:
- filename: chatbase-chat-api-openapi.yml
  format: yaml
  label: Chatbase Chat API
  slug: chatbase-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatbase/openapi/chatbase-chat-api-openapi.yml
- filename: chatbase-chatbots-api-openapi.yml
  format: yaml
  label: Chatbase Chatbots API
  slug: chatbase-chatbots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatbase/openapi/chatbase-chatbots-api-openapi.yml
- filename: chatbase-contacts-api-openapi.yml
  format: yaml
  label: Chatbase Contacts API
  slug: chatbase-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatbase/openapi/chatbase-contacts-api-openapi.yml
- filename: chatbase-conversations-api-openapi.yml
  format: yaml
  label: Chatbase Conversations API
  slug: chatbase-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatbase/openapi/chatbase-conversations-api-openapi.yml
- filename: chatbase-leads-api-openapi.yml
  format: yaml
  label: Chatbase Leads API
  slug: chatbase-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatbase/openapi/chatbase-leads-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: Chatbase platform
    text: The Trust Center includes SOC 2 Type II report, HIPAA info, penetration testing, policies, subprocessors, updates, and common security answers. Access to certain documents may require a request.
    type: SOC 2 Type II
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Enterprise workspaces
    text: HIPAA support for eligible Enterprise workspaces provide a clear foundation for secure deployment.
    type: HIPAA-eligible Enterprise workspaces
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Chatbase is SOC 2 Type II compliant, supports GDPR requirements, and provides HIPAA-eligible Enterprise workspaces.
    type: GDPR support
  trust_center:
    url: https://www.chatbase.co/security
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Chatbase
provenance_date: '2026-11-09'
provider_name: Chatbase
provider_slug: chatbase
slug: chatbase-compliance
source_date: '2026-11-09'
source_filename: chatbase-compliance.yml
source_heading: Compliance
source_page: https://www.chatbase.co/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Chatbase\naid: chatbase\nurl: https://www.chatbase.co/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/chatbase-trust-center.yml\ntrust_center:\n  url: https://www.chatbase.co/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: Chatbase platform\n  period: null\n  issuer: null\n  report_access: nda\n  text: The Trust Center includes SOC 2 Type II report, HIPAA info, penetration testing, policies, subprocessors,\n    updates, and common security answers. Access to certain documents may require a request.\n- framework: HIPAA\n  type: HIPAA-eligible Enterprise workspaces\n\
  \  scope: Enterprise workspaces\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA support for eligible Enterprise workspaces provide a clear foundation for secure deployment.\n- framework: GDPR\n  type: GDPR support\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Chatbase is SOC 2 Type II compliant, supports GDPR requirements, and provides HIPAA-eligible Enterprise\n    workspaces.\n"
source_yaml_url: https://artifacts.apis.io/chatbase/compliance/chatbase-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Chatbase's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Chatbots
- AI Agents
- Customer Service
- Conversational AI
---
