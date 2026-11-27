---
api_specs:
- filename: blacksmith-sh-openapi.yml
  format: yaml
  label: Blacksmith GitHub Actions Runners
  slug: github-actions-runners
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blacksmith-sh/openapi/_original/blacksmith-sh-openapi.yml
- filename: blacksmith-sh-openapi.yml
  format: yaml
  label: Blacksmith Docker Builds
  slug: docker-builds
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blacksmith-sh/openapi/_original/blacksmith-sh-openapi.yml
- filename: blacksmith-sh-openapi.yml
  format: yaml
  label: Blacksmith Cache
  slug: cache
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blacksmith-sh/openapi/_original/blacksmith-sh-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: we are SOC 2 Type 2, GDPR compliant, and our hardware runs in ISO 27001 data centers.
    type: GDPR compliance
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: hardware hosting data centers
    text: our hardware runs in ISO 27001 data centers
    type: ISO 27001 data centers
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: are in the process of becoming HIPAA compliant in the coming weeks
    type: HIPAA compliance (in progress)
  trust_center:
    url: https://www.blacksmith.sh/security
frameworks:
- GDPR
- HIPAA
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Blacksmith
provenance_date: '2026-11-09'
provider_name: Blacksmith
provider_slug: blacksmith-sh
slug: blacksmith-sh-compliance
source_date: '2026-11-09'
source_filename: blacksmith-sh-compliance.yml
source_heading: Compliance
source_page: https://www.blacksmith.sh/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Blacksmith\naid: blacksmith-sh\nurl: https://www.blacksmith.sh/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/blacksmith-sh-trust-center.yml\ntrust_center:\n  url: https://www.blacksmith.sh/security\nattestations:\n- framework: GDPR\n  type: GDPR compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: we are SOC 2 Type 2, GDPR compliant, and our hardware runs in ISO 27001 data centers.\n- framework: ISO27001\n  type: ISO 27001 data centers\n  scope: hardware hosting data centers\n  period: null\n  issuer: null\n  report_access: unstated\n  text: our hardware\
  \ runs in ISO 27001 data centers\n- framework: HIPAA\n  type: HIPAA compliance (in progress)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: are in the process of becoming HIPAA compliant in the coming weeks\n"
source_yaml_url: https://artifacts.apis.io/blacksmith-sh/compliance/blacksmith-sh-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Blacksmith's own page on 2026-11-09.
synthetic: false
tags:
- CI/CD
- GitHub Actions
- Runners
- Caching
- Docker
- Developer Tools
---
