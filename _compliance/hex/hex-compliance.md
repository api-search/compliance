---
api_specs:
- filename: hex-cells-api-openapi.yml
  format: yaml
  label: Hex Cells API
  slug: hex-cells-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hex/openapi/hex-cells-api-openapi.yml
- filename: hex-collections-api-openapi.yml
  format: yaml
  label: Hex Collections API
  slug: hex-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hex/openapi/hex-collections-api-openapi.yml
- filename: hex-context-api-openapi.yml
  format: yaml
  label: Hex Context API
  slug: hex-context-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hex/openapi/hex-context-api-openapi.yml
- filename: hex-data-connections-api-openapi.yml
  format: yaml
  label: Hex Data Connections API
  slug: hex-data-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hex/openapi/hex-data-connections-api-openapi.yml
- filename: hex-embedding-api-openapi.yml
  format: yaml
  label: Hex Embedding API
  slug: hex-embedding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hex/openapi/hex-embedding-api-openapi.yml
- filename: hex-groups-api-openapi.yml
  format: yaml
  label: Hex Groups API
  slug: hex-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hex/openapi/hex-groups-api-openapi.yml
- filename: hex-guides-api-openapi.yml
  format: yaml
  label: Hex Guides API
  slug: hex-guides-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hex/openapi/hex-guides-api-openapi.yml
- filename: hex-projects-api-openapi.yml
  format: yaml
  label: Hex Projects API
  slug: hex-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hex/openapi/hex-projects-api-openapi.yml
- filename: hex-semantic-projects-models-api-openapi.yml
  format: yaml
  label: Hex Semantic (projects|models) API
  slug: hex-semantic-projects-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hex/openapi/hex-semantic-projects-models-api-openapi.yml
- filename: hex-threads-api-openapi.yml
  format: yaml
  label: Hex Threads API
  slug: hex-threads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hex/openapi/hex-threads-api-openapi.yml
- filename: hex-users-api-openapi.yml
  format: yaml
  label: Hex Users API
  slug: hex-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hex/openapi/hex-users-api-openapi.yml
- filename: hex-suggestions-api-openapi.yml
  format: yaml
  label: Hex Suggestions API
  slug: hex-suggestions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hex/openapi/hex-suggestions-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: October 1, 2025 - September 30, 2026
    report_access: on_request
    scope: null
    text: Authorized trust center visitors can now view & download Hex's SOC 1 Type II, SOC 2 Type II, and HIPAA audit reports covering the period October 1, 2025 - September 30, 2026.
    type: SOC 2 Type II audit report
  - framework: SOC1
    issuer: null
    period: October 1, 2025 - September 30, 2026
    report_access: on_request
    scope: null
    text: Authorized trust center visitors can now view & download Hex's SOC 1 Type II, SOC 2 Type II, and HIPAA audit reports covering the period October 1, 2025 - September 30, 2026.
    type: SOC 1 Type II audit report
  - framework: HIPAA
    issuer: null
    period: October 1, 2025 - September 30, 2026
    report_access: on_request
    scope: null
    text: Authorized trust center visitors can now view & download Hex's SOC 1 Type II, SOC 2 Type II, and HIPAA audit reports covering the period October 1, 2025 - September 30, 2026.
    type: HIPAA audit report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Badges CCPA EU-US DPF GDPR HIPAA PCI SOC 2 Type II Swiss-US DPF UK-US DPF
    type: badge
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Badges CCPA EU-US DPF GDPR HIPAA PCI SOC 2 Type II Swiss-US DPF UK-US DPF
    type: badge
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Badges CCPA EU-US DPF GDPR HIPAA PCI SOC 2 Type II Swiss-US DPF UK-US DPF
    type: badge
  trust_center:
    url: https://trust.hex.tech/
frameworks:
- CCPA
- GDPR
- HIPAA
- PCI-DSS
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Hex
provenance_date: '2026-11-09'
provider_name: Hex
provider_slug: hex
slug: hex-compliance
source_date: '2026-11-09'
source_filename: hex-compliance.yml
source_heading: Compliance
source_page: https://trust.hex.tech/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Hex\naid: hex\nurl: https://trust.hex.tech/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/hex-trust-center.yml\ntrust_center:\n  url: https://trust.hex.tech/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II audit report\n  scope: null\n  period: October 1, 2025 - September 30, 2026\n  issuer: null\n  report_access: on_request\n  text: Authorized trust center visitors can now view & download Hex's SOC 1 Type II, SOC 2 Type II, and HIPAA audit\n    reports covering the period October 1, 2025 - September 30, 2026.\n- framework: SOC1\n  type: SOC 1 Type II audit report\n  scope: null\n  period:\
  \ October 1, 2025 - September 30, 2026\n  issuer: null\n  report_access: on_request\n  text: Authorized trust center visitors can now view & download Hex's SOC 1 Type II, SOC 2 Type II, and HIPAA audit\n    reports covering the period October 1, 2025 - September 30, 2026.\n- framework: HIPAA\n  type: HIPAA audit report\n  scope: null\n  period: October 1, 2025 - September 30, 2026\n  issuer: null\n  report_access: on_request\n  text: Authorized trust center visitors can now view & download Hex's SOC 1 Type II, SOC 2 Type II, and HIPAA audit\n    reports covering the period October 1, 2025 - September 30, 2026.\n- framework: GDPR\n  type: badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Badges CCPA EU-US DPF GDPR HIPAA PCI SOC 2 Type II Swiss-US DPF UK-US DPF\n- framework: CCPA\n  type: badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Badges CCPA EU-US DPF GDPR HIPAA PCI SOC 2 Type II Swiss-US DPF UK-US DPF\n\
  - framework: PCI-DSS\n  type: badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Badges CCPA EU-US DPF GDPR HIPAA PCI SOC 2 Type II Swiss-US DPF UK-US DPF\n"
source_yaml_url: https://artifacts.apis.io/hex/compliance/hex-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Hex's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Analytics
- Data Science
- Notebooks
- Business Intelligence
- Data Apps
- Artificial Intelligence
- Agents
- Semantic Layer
- Developer Tools
---
