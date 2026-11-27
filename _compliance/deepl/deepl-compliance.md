---
api_specs:
- filename: deepl-voice-api-openapi.yml
  format: yaml
  label: DeepL Voice API
  slug: deepl-voice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-voice-api-openapi.yml
- filename: deepl-adminapi-api-openapi.yml
  format: yaml
  label: DeepL Admin API
  slug: deepl-adminapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-adminapi-api-openapi.yml
- filename: deepl-correcttext-api-openapi.yml
  format: yaml
  label: DeepL Correct Text API
  slug: deepl-correcttext-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-correcttext-api-openapi.yml
- filename: deepl-manageglossaries-api-openapi.yml
  format: yaml
  label: DeepL Manage Glossaries API
  slug: deepl-manageglossaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-manageglossaries-api-openapi.yml
- filename: deepl-managemultilingualglossaries-api-openapi.yml
  format: yaml
  label: DeepL Manage Multilingual Glossaries API
  slug: deepl-managemultilingualglossaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-managemultilingualglossaries-api-openapi.yml
- filename: deepl-managespokenterms-api-openapi.yml
  format: yaml
  label: DeepL Manage Spoken Terms API
  slug: deepl-managespokenterms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-managespokenterms-api-openapi.yml
- filename: deepl-metainformation-api-openapi.yml
  format: yaml
  label: DeepL Meta Information API
  slug: deepl-metainformation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-metainformation-api-openapi.yml
- filename: deepl-qualityevaluation-api-openapi.yml
  format: yaml
  label: DeepL Quality Evaluation API
  slug: deepl-qualityevaluation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-qualityevaluation-api-openapi.yml
- filename: deepl-rephrasetext-api-openapi.yml
  format: yaml
  label: DeepL Rephrase Text API
  slug: deepl-rephrasetext-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-rephrasetext-api-openapi.yml
- filename: deepl-style-rules-api-openapi.yml
  format: yaml
  label: DeepL Style Rules API
  slug: deepl-style-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-style-rules-api-openapi.yml
- filename: deepl-translatedocuments-api-openapi.yml
  format: yaml
  label: DeepL Translate Documents API
  slug: deepl-translatedocuments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-translatedocuments-api-openapi.yml
- filename: deepl-translatetext-api-openapi.yml
  format: yaml
  label: DeepL Translate Text API
  slug: deepl-translatetext-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-translatetext-api-openapi.yml
- filename: deepl-translationmemories-api-openapi.yml
  format: yaml
  label: DeepL Translation Memories API
  slug: deepl-translationmemories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-translationmemories-api-openapi.yml
- filename: deepl-voiceapi-api-openapi.yml
  format: yaml
  label: DeepL Voice API
  slug: deepl-voiceapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-voiceapi-api-openapi.yml
- filename: deepl-voicetranslatejob-api-openapi.yml
  format: yaml
  label: DeepL Voice Translate Job API
  slug: deepl-voicetranslatejob-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-voicetranslatejob-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: C5
    issuer: German Federal Office for Information Security (BSI)
    period: null
    report_access: unstated
    scope: DeepL
    text: We are proud to announce that DeepL has successfully achieved the C5 Type 2 attestation and renewed its SOC 2 Type 2 report
    type: Type 2 attestation
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: DeepL
    text: We are proud to announce that DeepL has successfully achieved the C5 Type 2 attestation and renewed its SOC 2 Type 2 report
    type: Type 2 report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: DeepL Agent
    text: Customers and partners can request a copy of our ISO 27001 certificate through our Trust Center.
    type: certification (ISO/IEC 27001:2022)
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: DeepL
    text: We are thrilled to announce that DeepL has achieved HIPAA compliance
    type: compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: DeepL
    text: DeepL remains fully GDPR compliant.
    type: compliance
  trust_center:
    url: https://deepl.safebase.us/
frameworks:
- C5
- GDPR
- HIPAA
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: DeepL
provenance_date: '2026-11-09'
provider_name: DeepL
provider_slug: deepl
slug: deepl-compliance
source_date: '2026-11-09'
source_filename: deepl-compliance.yml
source_heading: Compliance
source_page: https://deepl.safebase.us/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: DeepL\naid: deepl\nurl: https://deepl.safebase.us/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/deepl-trust-center.yml\ntrust_center:\n  url: https://deepl.safebase.us/\nattestations:\n- framework: C5\n  type: Type 2 attestation\n  scope: DeepL\n  period: null\n  issuer: German Federal Office for Information Security (BSI)\n  report_access: unstated\n  text: We are proud to announce that DeepL has successfully achieved the C5 Type 2 attestation and renewed its\n    SOC 2 Type 2 report\n- framework: SOC2\n  type: Type 2 report\n  scope: DeepL\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: We are proud to announce that DeepL has successfully achieved the C5 Type 2 attestation and renewed its\n    SOC 2 Type 2 report\n- framework: ISO27001\n  type: certification (ISO/IEC 27001:2022)\n  scope: DeepL Agent\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Customers and partners can request a copy of our ISO 27001 certificate through our Trust Center.\n- framework: HIPAA\n  type: compliance\n  scope: DeepL\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are thrilled to announce that DeepL has achieved HIPAA compliance\n- framework: GDPR\n  type: compliance\n  scope: DeepL\n  period: null\n  issuer: null\n  report_access: unstated\n  text: DeepL remains fully GDPR compliant.\n"
source_yaml_url: https://artifacts.apis.io/deepl/compliance/deepl-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from DeepL's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Deep Learning
- Glossary
- Localization
- Machine Learning
- Machine Translation
- Translation
- Real-Time
---
