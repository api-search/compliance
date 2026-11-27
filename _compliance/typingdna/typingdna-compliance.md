---
api_specs:
- filename: typingdna-advanced-api-openapi.yml
  format: yaml
  label: TypingDNA Advanced API
  slug: typingdna-advanced-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/typingdna/openapi/typingdna-advanced-api-openapi.yml
- filename: typingdna-optional-api-openapi.yml
  format: yaml
  label: TypingDNA Optional API
  slug: typingdna-optional-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/typingdna/openapi/typingdna-optional-api-openapi.yml
- filename: typingdna-standard-api-openapi.yml
  format: yaml
  label: TypingDNA Standard API
  slug: typingdna-standard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/typingdna/openapi/typingdna-standard-api-openapi.yml
claim_count: 7
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: unstated
    text: TypingDNA is certified for ISO 27001, ISO 27017, and ISO 27018.
    type: certification
  - framework: ISO27017
    issuer: null
    period: null
    report_access: unstated
    scope: unstated
    text: TypingDNA is certified for ISO 27001, ISO 27017, and ISO 27018.
    type: certification
  - framework: ISO27018
    issuer: null
    period: null
    report_access: unstated
    scope: unstated
    text: TypingDNA is certified for ISO 27001, ISO 27017, and ISO 27018.
    type: certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: unstated
    text: TypingDNA is enrolled in the EU-U.S. Privacy Shield Framework.
    type: privacy framework enrollment (EU-U.S. Privacy Shield)
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://www.typingdna.com/about
    text: TypingDNA fulfills high standards of information, and security management (ISO 27001), information security for cloud services (ISO 27017), and the protection of Personally Identifiable Information (PII) in line with the privacy principles (ISO 27018).
    type: stated compliance
  - framework: ISO27017
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://www.typingdna.com/about
    text: TypingDNA fulfills high standards of information, and security management (ISO 27001), information security for cloud services (ISO 27017), and the protection of Personally Identifiable Information (PII) in line with the privacy principles (ISO 27018).
    type: stated compliance
  - framework: ISO27018
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://www.typingdna.com/about
    text: TypingDNA fulfills high standards of information, and security management (ISO 27001), information security for cloud services (ISO 27017), and the protection of Personally Identifiable Information (PII) in line with the privacy principles (ISO 27018).
    type: stated compliance
  trust_center:
    url: https://www.typingdna.com/pricing/auth-api
frameworks:
- ISO27001
- ISO27017
- ISO27018
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: TypingDNA
provenance_date: '2026-11-10'
provider_name: TypingDNA
provider_slug: typingdna
slug: typingdna-compliance
source_date: '2026-11-10'
source_filename: typingdna-compliance.yml
source_heading: Compliance
source_page: https://www.typingdna.com/pricing/auth-api
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: TypingDNA\naid: typingdna\nurl: https://www.typingdna.com/pricing/auth-api\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/typingdna-trust-center.yml\n  sources:\n  - https://www.typingdna.com/about\n  - https://www.typingdna.com/pricing/auth-api\ntrust_center:\n  url: https://www.typingdna.com/pricing/auth-api\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: unstated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TypingDNA is certified for ISO 27001, ISO 27017, and ISO 27018.\n- framework: ISO27017\n  type: certification\n  scope: unstated\n  period: null\n\
  \  issuer: null\n  report_access: unstated\n  text: TypingDNA is certified for ISO 27001, ISO 27017, and ISO 27018.\n- framework: ISO27018\n  type: certification\n  scope: unstated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TypingDNA is certified for ISO 27001, ISO 27017, and ISO 27018.\n- framework: other\n  type: privacy framework enrollment (EU-U.S. Privacy Shield)\n  scope: unstated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TypingDNA is enrolled in the EU-U.S. Privacy Shield Framework.\n- framework: ISO27001\n  type: stated compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TypingDNA fulfills high standards of information, and security management (ISO 27001), information security\n    for cloud services (ISO 27017), and the protection of Personally Identifiable Information (PII) in line with\n    the privacy principles (ISO 27018).\n  source: https://www.typingdna.com/about\n- framework: ISO27017\n\
  \  type: stated compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TypingDNA fulfills high standards of information, and security management (ISO 27001), information security\n    for cloud services (ISO 27017), and the protection of Personally Identifiable Information (PII) in line with\n    the privacy principles (ISO 27018).\n  source: https://www.typingdna.com/about\n- framework: ISO27018\n  type: stated compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TypingDNA fulfills high standards of information, and security management (ISO 27001), information security\n    for cloud services (ISO 27017), and the protection of Personally Identifiable Information (PII) in line with\n    the privacy principles (ISO 27018).\n  source: https://www.typingdna.com/about\n"
source_yaml_url: https://artifacts.apis.io/typingdna/compliance/typingdna-compliance.yml
stated_fields:
- attestations
summary_line: 7 quoted statements, read from TypingDNA's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Authentication
- Biometrics
- Typing Biometrics
- Two-Factor Authentication
- Identity
- Security
- Fraud Prevention
---
