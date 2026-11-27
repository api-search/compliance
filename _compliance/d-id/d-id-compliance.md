---
api_specs:
- filename: d-id-agents-api-openapi.yml
  format: yaml
  label: D-ID Agents API
  slug: d-id-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/d-id/openapi/d-id-agents-api-openapi.yml
- filename: d-id-chat-api-openapi.yml
  format: yaml
  label: D-ID Chat API
  slug: d-id-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/d-id/openapi/d-id-chat-api-openapi.yml
- filename: d-id-credits-api-openapi.yml
  format: yaml
  label: D-ID Credits API
  slug: d-id-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/d-id/openapi/d-id-credits-api-openapi.yml
- filename: d-id-knowledge-api-openapi.yml
  format: yaml
  label: D-ID Knowledge API
  slug: d-id-knowledge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/d-id/openapi/d-id-knowledge-api-openapi.yml
- filename: d-id-sessions-api-openapi.yml
  format: yaml
  label: D-ID Sessions API
  slug: d-id-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/d-id/openapi/d-id-sessions-api-openapi.yml
- filename: d-id-talks-api-openapi.yml
  format: yaml
  label: D-ID Talks API
  slug: d-id-talks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/d-id/openapi/d-id-talks-api-openapi.yml
- filename: d-id-translations-api-openapi.yml
  format: yaml
  label: D-ID Translations API
  slug: d-id-translations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/d-id/openapi/d-id-translations-api-openapi.yml
- filename: d-id-videos-v4-api-openapi.yml
  format: yaml
  label: D-ID Videos V4 API
  slug: d-id-videos-v4-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/d-id/openapi/d-id-videos-v4-api-openapi.yml
- filename: d-id-voices-api-openapi.yml
  format: yaml
  label: D-ID Voices API
  slug: d-id-voices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/d-id/openapi/d-id-voices-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: 'ISO/IEC 27001:2022 : A testament to our robust information security management.'
    type: ISO/IEC 27001:2022 certification
  - framework: ISO27017
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: 'ISO/IEC 27017:2015 : Sets the benchmark for best practices in cloud security.'
    type: ISO/IEC 27017:2015 certification
  - framework: ISO27018
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: 'ISO/IEC 27018:2019 : Ensures the protection of personally identifiable information (PII) in cloud environments and compliance with data protection laws like the GDPR.'
    type: ISO/IEC 27018:2019 certification
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: 'ISO/IEC 42001:2023 : An international standard that specifies requirements for establishing, implementing, maintaining, and continually improving an Artificial Intelligence Management System (AIMS) within organizations.'
    type: ISO/IEC 42001:2023 certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We fully comply with ISO 27799 Health Informatics — Information Security Management in Health using ISO/IEC 27002.
    type: ISO/IEC 27799 compliance
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: 'SOC 2 Certification : This framework ensures that data stored, processed, and shared in the cloud is protected against unauthorized access and with verified uninterrupted continued service level.'
    type: SOC 2 certification
  trust_center:
    url: https://www.d-id.com/security-and-privacy-compliance/
frameworks:
- ISO27001
- ISO27017
- ISO27018
- ISO42001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: D-ID
provenance_date: '2026-11-09'
provider_name: D-ID
provider_slug: d-id
slug: d-id-compliance
source_date: '2026-11-09'
source_filename: d-id-compliance.yml
source_heading: Compliance
source_page: https://www.d-id.com/security-and-privacy-compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: D-ID\naid: d-id\nurl: https://www.d-id.com/security-and-privacy-compliance/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/d-id-trust-center.yml\ntrust_center:\n  url: https://www.d-id.com/security-and-privacy-compliance/\nattestations:\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'ISO/IEC 27001:2022 : A testament to our robust information security management.'\n- framework: ISO27017\n  type: ISO/IEC 27017:2015 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: 'ISO/IEC 27017:2015 : Sets the benchmark for best practices in cloud security.'\n- framework: ISO27018\n  type: ISO/IEC 27018:2019 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'ISO/IEC 27018:2019 : Ensures the protection of personally identifiable information (PII) in cloud environments\n    and compliance with data protection laws like the GDPR.'\n- framework: ISO42001\n  type: ISO/IEC 42001:2023 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'ISO/IEC 42001:2023 : An international standard that specifies requirements for establishing, implementing,\n    maintaining, and continually improving an Artificial Intelligence Management System (AIMS) within organizations.'\n- framework: other\n  type: ISO/IEC 27799 compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We fully comply with ISO 27799 Health Informatics — Information Security Management\
  \ in Health using ISO/IEC\n    27002.\n- framework: SOC2\n  type: SOC 2 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'SOC 2 Certification : This framework ensures that data stored, processed, and shared in the cloud is protected\n    against unauthorized access and with verified uninterrupted continued service level.'\n"
source_yaml_url: https://artifacts.apis.io/d-id/compliance/d-id-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from D-ID's own page on 2026-11-09.
synthetic: false
tags:
- Avatars
- DID
- AI Video
- Digital Humans
- Talking Head
- Generative AI
- Video Generation
- Real-Time Streaming
- Video Translation
- Voice Cloning
---
