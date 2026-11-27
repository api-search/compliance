---
api_specs:
- filename: landingai-classes-api-openapi.yml
  format: yaml
  label: Landing.ai Classes API
  slug: landingai-classes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landingai/openapi/landingai-classes-api-openapi.yml
- filename: landingai-deployment-api-openapi.yml
  format: yaml
  label: Landing.ai Deployment API
  slug: landingai-deployment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landingai/openapi/landingai-deployment-api-openapi.yml
- filename: landingai-extract-api-openapi.yml
  format: yaml
  label: Landing.ai Extract API
  slug: landingai-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landingai/openapi/landingai-extract-api-openapi.yml
- filename: landingai-image-api-openapi.yml
  format: yaml
  label: Landing.ai Image API
  slug: landingai-image-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landingai/openapi/landingai-image-api-openapi.yml
- filename: landingai-metadata-api-openapi.yml
  format: yaml
  label: Landing.ai Metadata API
  slug: landingai-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landingai/openapi/landingai-metadata-api-openapi.yml
- filename: landingai-metrics-api-openapi.yml
  format: yaml
  label: Landing.ai Metrics API
  slug: landingai-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landingai/openapi/landingai-metrics-api-openapi.yml
- filename: landingai-model-api-openapi.yml
  format: yaml
  label: Landing.ai Model API
  slug: landingai-model-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landingai/openapi/landingai-model-api-openapi.yml
- filename: landingai-parse-api-openapi.yml
  format: yaml
  label: Landing.ai Parse API
  slug: landingai-parse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landingai/openapi/landingai-parse-api-openapi.yml
- filename: landingai-project-api-openapi.yml
  format: yaml
  label: Landing.ai Project API
  slug: landingai-project-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landingai/openapi/landingai-project-api-openapi.yml
- filename: landingai-snapshot-api-openapi.yml
  format: yaml
  label: Landing.ai Snapshot API
  slug: landingai-snapshot-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landingai/openapi/landingai-snapshot-api-openapi.yml
- filename: landingai-tags-api-openapi.yml
  format: yaml
  label: Landing.ai Tags API
  slug: landingai-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landingai/openapi/landingai-tags-api-openapi.yml
- filename: landingai-tools-api-openapi.yml
  format: yaml
  label: Landing.ai Tools API
  slug: landingai-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landingai/openapi/landingai-tools-api-openapi.yml
- filename: landingai-training-api-openapi.yml
  format: yaml
  label: Landing.ai Training API
  slug: landingai-training-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landingai/openapi/landingai-training-api-openapi.yml
claim_count: 7
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent third-party assessor
    period: null
    report_access: nda
    scope: Agentic Document Extraction and LandingLens
    text: Current and prospective customers can request the full report directly from our Trust Center after signing a Non-Disclosure Agreement (NDA).
    type: SOC 2 Type II audit
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliance SOC 2 Type II HIPAA GDPR
    type: compliance listing
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliance SOC 2 Type II HIPAA GDPR
    type: compliance listing
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: ADE SaaS and ADE VPC
    text: CAIQ v4.0.3 STAR Security Questionnaire (ADE SaaS)
    type: CAIQ v4.0.3 STAR Security Questionnaire
  - framework: SOC2
    issuer: independent, third-party assessor
    period: null
    report_access: nda
    scope: Agentic Document Extraction and LandingLens
    source: https://trust.landing.ai/
    text: Current and prospective customers can request the full report directly from our Trust Center after signing a Non-Disclosure Agreement (NDA).
    type: SOC 2 Type II
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.landing.ai/
    text: HIPAA
    type: listed compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.landing.ai/
    text: GDPR
    type: listed compliance
  trust_center:
    url: https://trust.landing.ai/
frameworks:
- CSA-STAR
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Landing.ai
provenance_date: '2026-11-09'
provider_name: Landing.ai
provider_slug: landingai
slug: landingai-compliance
source_date: '2026-11-09'
source_filename: landingai-compliance.yml
source_heading: Compliance
source_page: https://trust.landing.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Landing.ai\naid: landingai\nurl: https://trust.landing.ai/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/landingai-trust-center.yml\n  sources:\n  - https://trust.landing.ai/\ntrust_center:\n  url: https://trust.landing.ai/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: Agentic Document Extraction and LandingLens\n  period: null\n  issuer: independent third-party assessor\n  report_access: nda\n  text: Current and prospective customers can request the full report directly from our Trust Center after signing\n    a Non-Disclosure Agreement (NDA).\n- framework: HIPAA\n  type:\
  \ compliance listing\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance SOC 2 Type II HIPAA GDPR\n- framework: GDPR\n  type: compliance listing\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance SOC 2 Type II HIPAA GDPR\n- framework: CSA-STAR\n  type: CAIQ v4.0.3 STAR Security Questionnaire\n  scope: ADE SaaS and ADE VPC\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CAIQ v4.0.3 STAR Security Questionnaire (ADE SaaS)\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: Agentic Document Extraction and LandingLens\n  period: null\n  issuer: independent, third-party assessor\n  report_access: nda\n  text: Current and prospective customers can request the full report directly from our Trust Center after signing\n    a Non-Disclosure Agreement (NDA).\n  source: https://trust.landing.ai/\n- framework: HIPAA\n  type: listed compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: HIPAA\n  source: https://trust.landing.ai/\n- framework: GDPR\n  type: listed compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n  source: https://trust.landing.ai/\n"
source_yaml_url: https://artifacts.apis.io/landingai/compliance/landingai-compliance.yml
stated_fields:
- attestations
summary_line: 7 quoted statements, read from Landing.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Document Extraction
- Document Processing
- Computer Vision
- OCR
- Data Extraction
- Agents
- Developer Tools
---
