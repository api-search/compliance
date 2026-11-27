---
api_specs:
- filename: storyblok-webhooks-asyncapi.yml
  format: yaml
  label: Storyblok Webhooks
  slug: storyblok-webhooks
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/storyblok/asyncapi/storyblok-webhooks-asyncapi.yml
- filename: storyblok-assets-api-openapi.yml
  format: yaml
  label: Storyblok Assets API
  slug: storyblok-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/storyblok/openapi/storyblok-assets-api-openapi.yml
- filename: storyblok-collaborators-api-openapi.yml
  format: yaml
  label: Storyblok Collaborators API
  slug: storyblok-collaborators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/storyblok/openapi/storyblok-collaborators-api-openapi.yml
- filename: storyblok-components-api-openapi.yml
  format: yaml
  label: Storyblok Components API
  slug: storyblok-components-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/storyblok/openapi/storyblok-components-api-openapi.yml
- filename: storyblok-image-transformation-api-openapi.yml
  format: yaml
  label: Storyblok Image Transformation API
  slug: storyblok-image-transformation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/storyblok/openapi/storyblok-image-transformation-api-openapi.yml
- filename: storyblok-links-api-openapi.yml
  format: yaml
  label: Storyblok Links API
  slug: storyblok-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/storyblok/openapi/storyblok-links-api-openapi.yml
- filename: storyblok-spaces-api-openapi.yml
  format: yaml
  label: Storyblok Spaces API
  slug: storyblok-spaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/storyblok/openapi/storyblok-spaces-api-openapi.yml
- filename: storyblok-stories-api-openapi.yml
  format: yaml
  label: Storyblok Stories API
  slug: storyblok-stories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/storyblok/openapi/storyblok-stories-api-openapi.yml
- filename: storyblok-tags-api-openapi.yml
  format: yaml
  label: Storyblok Tags API
  slug: storyblok-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/storyblok/openapi/storyblok-tags-api-openapi.yml
- filename: storyblok-webhooks-api-openapi.yml
  format: yaml
  label: Storyblok Webhooks API
  slug: storyblok-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/storyblok/openapi/storyblok-webhooks-api-openapi.yml
- filename: storyblok-data-sources-api-openapi.yml
  format: yaml
  label: Storyblok Data Sources API
  slug: storyblok-data-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/storyblok/openapi/storyblok-data-sources-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: ISMS and data center compliance
    text: Adheres to ISO 27001 , TISAX and industry standards for data security and compliance.
    type: certification
  - framework: TISAX
    issuer: null
    period: null
    report_access: unstated
    scope: ISMS policies
    text: Adheres to ISO 27001 , TISAX and industry standards for data security and compliance.
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: privacy
    text: Storyblok is fully compliant with GDPR and other applicable privacy laws.
    type: regulatory compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: EU-U.S. Data Privacy Framework
    text: We are also self-certified under the EU-U.S. Data Privacy Framework.
    type: self-certification
  trust_center:
    url: https://www.storyblok.com/trust-center
frameworks:
- GDPR
- ISO27001
- TISAX
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Storyblok
provenance_date: '2026-11-10'
provider_name: Storyblok
provider_slug: storyblok
slug: storyblok-compliance
source_date: '2026-11-10'
source_filename: storyblok-compliance.yml
source_heading: Compliance
source_page: https://www.storyblok.com/trust-center
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Storyblok\naid: storyblok\nurl: https://www.storyblok.com/trust-center\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/storyblok-trust-center.yml\ntrust_center:\n  url: https://www.storyblok.com/trust-center\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: ISMS and data center compliance\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Adheres to ISO 27001 , TISAX and industry standards for data security and compliance.\n- framework: TISAX\n  type: certification\n  scope: ISMS policies\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Adheres\
  \ to ISO 27001 , TISAX and industry standards for data security and compliance.\n- framework: GDPR\n  type: regulatory compliance\n  scope: privacy\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Storyblok is fully compliant with GDPR and other applicable privacy laws.\n- framework: other\n  type: self-certification\n  scope: EU-U.S. Data Privacy Framework\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are also self-certified under the EU-U.S. Data Privacy Framework.\n"
source_yaml_url: https://artifacts.apis.io/storyblok/compliance/storyblok-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Storyblok's own page on 2026-11-10.
synthetic: false
tags:
- CMS
- Content Delivery
- Content Management
- Headless CMS
- Image Optimization
- REST API
- Visual Editor
- Webhook
---
